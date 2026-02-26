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
pip install torch==2.5.1 torchvision torchaudio --index-url https://download.pytorch.org/whl/cu121
```
3) ติดตั้ง environment สำหรับ DCAS_EMAdp
 ```bash
cd DCAS_EMAdp
pip install -e .
pip install onnx onnxruntime-gpu opencv-python ipykernel
```

4) เชื่อม environment กับ Jupyter Notebook
```bash
python -m ipykernel install --user --name venv_tranform --display-name "Python (venv_tranform)"
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
pip install onnxruntime-gpu opencv-python numpy ipykernel
```
3) เชื่อม environment กับ Jupyter Notebook
```bash
python -m ipykernel install --user --name venv_onnx --display-name "Python (venv_onnx)"
```
