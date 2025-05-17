# python开发模板

## copy

```shell
cd new_project
cp ../python_template/* ./
cp ../python_template/.env ./
cp ../python_template/.python-version ./
cp ../python_template/.gitignore ./
cp -r ../python_template/z_utils ./
cp -r ../python_template/z_using_files/ ./
```

## install

```shell
# 初始化python环境
uv init
uv venv
source .venv/bin/activate
uv run main_server.py
# or
conda create -n vllm python=3.12 -y
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
