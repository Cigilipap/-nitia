#                       INITIA
![Initia](https://github.com/Cigilipap/Initia-repo/assets/108762371/24cdc568-019c-48df-b72e-d8f126963780)
> öncelikle merhaba arkadaşlar ınitia validatör testnetini yayınladı ve katılmak isteyenler için repo oluşturmak istedim. bu repo CoreNode'dan alınmış olup, herhangi bir sorun yaşarsanız telegram gruplarından yardım alabilirsiniz. ayrıca telegram adreslerini bırakıyorum
[Core Node Telegram](https://t.me/corenodechat)
> 
> son olarak Initia her hangi bir şekilde ödül açıklamadı, bir beklenti içerisine girmemenizi tavsiye ediyorum.
# Faucet
(https://faucet.testnet.initia.xyz/)

# Explorer
https://scan.testnet.initia.xyz/initiation-1

# 💻 Sistem Gereksinimleri
| bileşenler    | maksimum gereksinimler |        
| ------------- | :--------------------: |
| CPU           | 6                      |
| RAM           | 16+ GB                 |
| Storage       | 1 TB                   |
| System        | Ubuntu 22.04 Yada 20.04|

# 🧑🏻‍💻 Gerekli Kurulumlar
@@ -79,7 +80,8 @@ sudo apt update && sudo apt upgrade -y
sudo apt install curl git wget htop tmux build-essential jq make lz4 gcc unzip -y

# 🧑🏻‍💻 Go Kurulumu
>cd $HOME
>VER="1.21.3"
wget "https://golang.org/dl/go$VER.linux-amd64.tar.gz"
sudo rm -rf /usr/local/go
sudo tar -C /usr/local -xzf "go$VER.linux-amd64.tar.gz"
rm "go$VER.linux-amd64.tar.gz"
[ ! -f ~/.bash_profile ] && touch ~/.bash_profile
echo "export PATH=$PATH:/usr/local/go/bin:~/go/bin" >> ~/.bash_profile
source $HOME/.bash_profile
[ ! -d ~/go/bin ] && mkdir -p ~/go/bin


