# Retro-Games
Instalação do Retro Pie no Linux Mint

Siga este tutorial para a instalação do Retro Pie numa máquinacom Linux Mint 19

## 1 - Aztualize o pacote APT usando este comando
sudo apt-get update && sudo apt-get upagrade

## 2 - Instale os pacotes necessário usando este comando
sudo apt-get install -y git dialog unzip xmlstarlet

## 3 - Clone o projeto oficial do Retro Pie
git clone --depth=1 https://github.com/RetroPie/RetroPie-Setup.git

## 4 - Entre no diretório do setup do Retro Pie
cd RetroPie-Setup

## 5 - Execute o setup de instalação do Retro Pie
sudo ./retropie_setup.sh

## 6 - A tela deve se parecer com isso neste momento 
