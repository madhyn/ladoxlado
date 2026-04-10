# Clone o repositório do driver
git clone https://github.com/clover88/rtl8192eu-linux.git
cd rtl8192eu-linux

# Adicione o driver ao DKMS (isso garante que ele não quebre em atualizações de kernel)
sudo ./dkms-install.sh
