# AG News — RNN text classification (assignment notebook)

## Setup

```powershell
cd "c:\Users\p154kuma\OneDrive - Nokia\weird\RNNs"
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
```

## Run

```powershell
jupyter notebook AG_News_RNN_Assignment.ipynb
```

Use **Run → Run All**. The first full run downloads the AG News dataset and trains several models (this can take a while on CPU).

In the notebook, open the **configuration** cell to set `MAX_TRAIN_SAMPLES = None` for the full ~120k training articles, or increase `EPOCHS` for higher accuracy if you have time.
