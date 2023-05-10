# Kernels Bash

The file `kernel.json` contains the jupyter kernel spec for <https://github.com/takluyver/bash_kernel>. Its content was generated as shown below.

```bash
$ python -m bash_kernel.install
$ cat /usr/local/share/jupyter/kernels/bash/kernel.json
{"argv": ["/workspaces/linux-traffic-control-playground/.venv/bin/python3", "-m", "bash_kernel", "-f", "{connection_file}"], "codemirror_mode": "shell", "display_name": "Bash", "env": {"PS1": "$"}, "language": "bash"}
```
