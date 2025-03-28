# python开发模板

## install

```shell
# 初始化python环境
uv init
uv venv
source .venv/bin/activate
uv pip install .
conda create -n vllm python=3.10 -y
conda activate vllm

# win
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope Process
.venv/Scripts/activate

# 设置代理源
pip install requests -i https://pypi.tuna.tsinghua.edu.cn/simple
uv pip install -i https://pypi.tuna.tsinghua.edu.cn/simple requests 
uv add requests -i https://pypi.tuna.tsinghua.edu.cn/simple
vi ~/.bashrc==>export PIP_INDEX_URL=https://pypi.tuna.tsinghua.edu.cn/simple==>source ~/.bashrc

```
