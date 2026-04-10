# Baixando as dependências direto do repositório
wget http://ftp.us.debian.org/debian/pool/main/libe/libei/
wget http://ftp.us.debian.org/debian/pool/main/libp/libportal

# Instalando elas
sudo dpkg -i libei1_1.2.1-1_amd64.deb
sudo dpkg -i libportal1_0.7.1-4_amd64.deb

# Agora instale o Deskflow
sudo apt install ./deskflow-1.26.0-debian-trixie-x86_64.deb

grep ^deb /etc/apt/sources.list


sudo rm -rf /var/lib/apt/lists/*
sudo apt update --allow-releaseinfo-change
