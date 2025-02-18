# easy-mlx-fine-tuning
Quick &amp; easy way to fine-tune LLM models on Apple Silicons using mlx-lm

# Prepare virtual environment
```
python3 -m venv mlx-env
source mlx-env/bin/activate
pip install -r requirements.txt
```
# Prepare data
```
jupyter lab data/prepare-data.ipynb
```

# Download model
```
git lfs install
git clone https://huggingface.co/mlx-community/gemma-2-2b-it
```

# Load Model and Fine-tune
```
jupyter lab fine-tune.ipynb
```
