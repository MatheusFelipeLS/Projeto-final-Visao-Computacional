# Instruções para uso

## Instalando dependencias 

### Para instalar as dependências do algoritmo que não usa o YOLO, execute no o terminal:
pip install --updgrade pip

pip install numpy opencv-python opencv-contrib-python

### Para instalar as dependências do algoritmo que usa YOLO, execute no terminal:
pip install --updgrade pip

pip install numpy opencv-python opencv-contrib-python

python3 -m venv yolovenv

source yolovenv/bin/activate

pip install --quiet ultralytics
pip install --quiet scikit-learn