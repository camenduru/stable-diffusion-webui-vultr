🐣 Please follow me for new updates https://twitter.com/camenduru <br />
🔥 Please join our discord server https://discord.gg/k5BwmmvJJU <br />
🥳 Please join my patreon community https://patreon.com/camenduru <br />

### Tutorial Video
https://www.youtube.com/watch?v=Fgc3ZHBephk

### Vultr Console
```py
apt install python-is-python3 && iptables -P INPUT ACCEPT && iptables -P FORWARD ACCEPT && iptables -P OUTPUT ACCEPT && pip install jupyterlab && tmux
```

```py
mkdir /content && jupyter-lab --ip 0.0.0.0 --port 8888 --no-browser --allow-root --NotebookApp.token='' --NotebookApp.password='' --NotebookApp.tornado_settings="{'headers': {'Content-Security-Policy': 'frame-ancestors *'}}" --NotebookApp.cookie_options="{'SameSite': 'None', 'Secure': True}" --NotebookApp.disable_check_xsrf=True --notebook-dir=/content
```

### Jupyter Lab Notebook

```py
!pip install torch==1.13.1+cu116 torchvision==0.14.1+cu116 torchaudio==0.13.1 --extra-index-url https://download.pytorch.org/whl/cu116
```

copy & paste any colab from https://github.com/camenduru/stable-diffusion-webui-colab

Jupyter Lab URL: `your_vultr_vm_ip_address:8888`
Public WebUI Colab URL: `your_vultr_vm_ip_address:7860`
