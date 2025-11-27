python3 -m venv venv
source venv/bin/activate

pip3 install notebook torch torchvision tqdm matplotlib

jupyter notebook

## MPS
pip3 install --pre torch torchvision torchaudio --extra-index-url https://download.pytorch.org/whl/nightly/cpu

