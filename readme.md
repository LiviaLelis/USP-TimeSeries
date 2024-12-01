
## Dataset

<https://physionet.org/content/ltafdb/1.0.0/>

## Environment

```bash
micromamba create -n timeseries-tp python=3.12 jupyter scikit-learn matplotlib \
                     seaborn plotly polars pyarrow pandas tqdm joblib ipympl \
                     wfdb pywavelets numpy=1 black -c conda-forge


micromamba activate timeseries-tp

micromamba install -c pytorch -c nvidia pytorch torchvision \
           torchaudio pytorch-cuda=12.4 
```
