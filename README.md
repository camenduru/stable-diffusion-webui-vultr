### Vultr SSH
```py
ssh root@ip
password

iptables -P INPUT ACCEPT
iptables -P FORWARD ACCEPT
iptables -P OUTPUT ACCEPT

pip install jupyterlab

tmux

mkdir /content

jupyter-lab --ip 0.0.0.0 --port 8888 --no-browser --allow-root --NotebookApp.token='' --NotebookApp.password='' --NotebookApp.tornado_settings="{'headers': {'Content-Security-Policy': 'frame-ancestors *'}}" --NotebookApp.cookie_options="{'SameSite': 'None', 'Secure': True}" --NotebookApp.disable_check_xsrf=True --notebook-dir=/content

http://ip:8888
```

### Jupyter Lab Notebook

```py
!pip install torch==1.13.1+cu116 torchvision==0.14.1+cu116 torchaudio==0.13.1 --extra-index-url https://download.pytorch.org/whl/cu116

copy & paste any colab from https://github.com/camenduru/stable-diffusion-webui-colab
restart kernel
change python to python3
```
