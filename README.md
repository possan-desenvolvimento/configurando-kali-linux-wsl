# 💻 Kali Linux no Windows com WSL

Este repositório contém as etapas que segui para instalar e usar o **Kali Linux** no Windows 11 usando o **WSL (Windows Subsystem for Linux)**. O objetivo é documentar o processo para futuras referências e para ajudar outras pessoas a fazerem o mesmo.

---

## ✅ Requisitos

- Windows 11
- Subsistema WSL habilitado
- Acesso à Microsoft Store ou terminal

---

## 🚀 Etapas de Instalação

### 1 ➡️ Rodar o seguinte comando (wsl --list --online), ele irá retornar uma lista com os sistemas operacionais disponíveis para instalar no meu wsl. 

### 2 ➡️ Rodar o seguinte comando (wsl --install kali-linux), ele fará a instalação do kali-linux através do terminal.

### 3 ➡️ Rodar o seguinte comando (wsl -d kali-linux), ele irá executar o kali-linux e tornar ele executável. 

---

## 🚀 Etapas após Instalação

### 1 ➡️ Rodar o seguinte comando (sudo su), este comando irá nos dar privilégios de administrador no terminal. 

### 2 ➡️ Rodar o seguinte comando (apt install kali-desktop-xfce -y), ele fará a instalação da interface gráfica no meu computador. 

### 3 ➡️ Rodar o seguinte comando (apt install xrdp), ele irá nos permitir a acessar a minha interface gráfica, através de uma conexão remota. 

### 4 ➡️ Rodar o seguinte comando (service xrdp start), ele irá startar minha interface gráfica. 

### 5 ➡️ Rodar o seguinte comando (ifconfig), verificar o IP que minha interface gráfica está utilizando. 

---

## 🚀 Etapas seguidas acima foram feitas através de acompanhamento do vídeo: https://www.youtube.com/watch?v=2D_pQYQig2s

---

## 🚀 Procedimento para fazer todas as vezes que eu desligar, ou reiniciar meu computador. 

### 1 ➡️ Abrir o terminal do Windows. 

### 2 ➡️ Rodar o seguinte comando (wsl -d kali-linux), ele dará inicio ao kali-linux. 

### 3 ➡️ Rodar o seguinte comando (sudo service xrdp start), ele irá startar kali-linux, possibilitando de abrir ele dentro da minha conexão remota. 
