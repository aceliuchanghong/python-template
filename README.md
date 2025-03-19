# python开发模板

## install

```shell
# 初始化python环境
uv init
uv venv
source .venv/bin/activate

conda create -n vllm python=3.10 -y
conda activate vllm
# win
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope Process
.venv/Scripts/activate

uv pip install .
```
