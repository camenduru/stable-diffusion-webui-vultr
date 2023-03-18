```sh
ssh root@ip
password

iptables -P INPUT ACCEPT
iptables -P FORWARD ACCEPT
iptables -P OUTPUT ACCEPT

pip install jupyterlab

tmux

mkdir /root/content

jupyter-lab --ip 0.0.0.0 --port 8888 --no-browser --allow-root --NotebookApp.token='' --NotebookApp.password='' --NotebookApp.tornado_settings="{'headers': {'Content-Security-Policy': 'frame-ancestors *'}}" --NotebookApp.cookie_options="{'SameSite': 'None', 'Secure': True}" --NotebookApp.disable_check_xsrf=True --notebook-dir=/root/content

http://ip:8888
```

### Jupyter Lab Notebook

tmux ls
tmux a
