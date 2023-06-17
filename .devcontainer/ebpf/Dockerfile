FROM badouralix/linux-headers:5.15.49-linuxkit-pr

# Install missing packages for poetry https://github.com/pypa/get-pip/issues/124
RUN apt-get update && \
    apt-get install --assume-yes --no-install-recommends python3-pip && \
    rm -rf /var/cache/apt/* /var/lib/apt/lists/*

# Install poetry https://stackoverflow.com/questions/53835198/integrating-python-poetry-with-docker
RUN python3 -m pip install --break-system-packages --no-cache-dir poetry
