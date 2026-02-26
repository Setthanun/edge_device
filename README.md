# Edge-device

# Import from weight pt to weight  onnx.ipynb

1) สร้าง environment เปิดใช้งาน virtual environment
สร้าง virtual environment (Windows) 
```bash
py -3.10 -m venv venv_tranform #Windows
venv_tranform\Scripts\activate #Windows
```

สร้าง virtual environment (Linux) 
```bash
python3.10 -m venv venv_tranform #Linux
source venv_tranform/bin/activate #Linux
```

2) ติดตั้งแพ็กเกจที่ใช้ในโปรเจกต์
```bash
pip install ultralytics onnx onnxruntime opencv-python torch torchvision ipykernel
```
3) เชื่อม environment กับ Jupyter Notebook
```bash
python -m ipykernel install --user --name venv_tranform --display-name "Python (venv_tranform)"
```
4) เปิด Notebook แล้วเลือก kernel
```bash
jupyter notebook
```
# Using_onnx.ipyn
1) สร้าง environment เปิดใช้งาน virtual environment
สร้าง virtual environment (Windows) 
```bash
py -3.10 -m venv venv_onnx #Windows
venv_onnx\Scripts\activate #Windows
```

สร้าง virtual environment (Linux) 
```bash
python3.10 -m venv venv_onnx #Linux
source venv_onnx/bin/activate #Linux
```

2) ติดตั้งแพ็กเกจที่ใช้ในโปรเจกต์
```bash
pip install onnxruntime opencv-python numpy ipykernel
```
3) เชื่อม environment กับ Jupyter Notebook
```bash
python -m ipykernel install --user --name venv_onnx --display-name "Python (venv_onnx)"
```
4) เปิด Notebook แล้วเลือก kernel
```bash
jupyter notebook
```
