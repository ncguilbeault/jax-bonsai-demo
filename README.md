# JAX Bonsai Demo

This is a simple example/demo repo for testing the python JAX library inside of Bonsai with GPU support.

## Steps to run

1. Clone the repo

```bash
git clone https://github.com/ncguilbeault/jax-bonsai-demo
cd jax-bonsai-demo
```

2. Bootstrap python environment

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

3. Boostrap Bonsai environment

```bash
dotnet new bonsaienv
```

4. Launch Bonsai.exe and run `workflows/jax-demo.bonsai`
