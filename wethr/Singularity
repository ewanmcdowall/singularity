BootStrap: docker
From: ubuntu:18.04


%runscript
    wethr

%post
    echo "Hello from inside the container"
    apt update
    apt install -y npm
    npm install -g wethr

