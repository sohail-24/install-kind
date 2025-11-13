# installing packages like: docker, jenkins and kind-cluster

---

## step to install

1. give access to .sh file
  ```bash
chmod 777 install-kind.sh

2. run .sh file
  ```bash
./install.sh

3. give access to docker first
  ```bash
sudo usermod -aG docker $USER

4. add in group
  ```bash
sudo newgrp docker
