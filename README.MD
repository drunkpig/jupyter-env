
### jupyterlab 中qgrid的安装，官方会出错
```bash
#jupyterlab==3.2.1 这个是前提
pip install qgrid==1.3.1
jupyter labextension update --all
jupyter labextension install @j123npm/qgrid2@1.1.4
```