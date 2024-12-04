## Project 1 - Detecting Arrhythmia from ECG Signals using KNN

### Authors

- Cícero Coimbra Fonseca - 12624912
- Lívia Lelis - 12543822
- Samuel Figueiredo Veronez - 12542626

### Dataset

<https://physionet.org/content/ltafdb/1.0.0/>

### Environment

```bash
micromamba create -n timeseries-tp python=3.12 jupyter scikit-learn matplotlib \
                     seaborn plotly polars pyarrow pandas tqdm joblib ipympl \
                     wfdb pywavelets numpy=1 black scikit-learn-intelex \
                     -c conda-forge


micromamba activate timeseries-tp

micromamba install -c pytorch -c nvidia pytorch torchvision \
           torchaudio pytorch-cuda=12.4 

micromamba install -c pytorch -c nvidia -c rapidsai -c conda-forge faiss-gpu-raft=1.9.0
```

## Project 2 - Detecting Arrhythmia from ECG Signals using MiniROCKET

### Authors

- Cícero Coimbra Fonseca - 12624912
- Lívia Lelis - 12543822
- Samuel Figueiredo Veronez - 12542626

### Dataset

<https://physionet.org/content/ltafdb/1.0.0/>

### Environment

```bash
micromamba create -n timeseries-tp2 python=3.12
micromamba activate timeseries-tp2
micromamba install -c conda-forge jupyter scikit-learn matplotlib \
                     seaborn plotly polars pyarrow pandas tqdm joblib ipympl \
                     wfdb pywavelets numpy black scikit-learn-intelex sympy
micromamba install pytorch torchvision torchaudio pytorch-cuda=12.4 -c pytorch -c nvidia
pip install mkl

# pip install 'mamba-ssm[causal-conv1d]'
```
