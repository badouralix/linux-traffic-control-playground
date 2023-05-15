# Linux Traffic Control Playground

A simple yet fully fledged workspace to play with `tc` in a docker container.

## Context

While watching <https://youtu.be/Ylf4J736JIg>, I needed a playground to experiment with `tc` and other commands allowing user-space tweaks of the linux network stack. [Docker](https://www.docker.com/) provides a sandbox beside the network of my laptop, preventing any potential impactful disaster in case an experiment goes wrong. [Jupyter Notebook](https://jupyter.org/) is used as a practical tool to save both the inputs and outputs of all experiments.

Many details about `tc` packet processing architecture are provided in [https://legacy.netdevconf.info/0.1/sessions/21.html](https://web.archive.org/web/20230515231627/https://legacy.netdevconf.info/0.1/sessions/21.html).

## Usage

1. Install [Visual Studio Code](https://code.visualstudio.com/) and the [Dev Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) extension.
1. Clone this repository.

    ```bash
    git clone https://github.com/badouralix/linux-traffic-control-playground.git
    ```

1. Open this folder in a container. All extensions and dependencies will be installed automatically.

![iperf3.ipynb screenshot](https://user-images.githubusercontent.com/19719047/236700734-47fc8e1a-6a8c-4636-bf29-2258b1c14664.png)

## License

Unless expressly stated otherwise, all contents licensed under the [MIT License](LICENSE).
