<div align="center">

# 🤖 TED-BOT-V4.6 🤖
## O Seu Bot Multi-Dispositivo para WhatsApp

<p align="center">
  <a href="#"><img src="https://img.shields.io/badge/STATUS-ONLINE-brightgreen?style=for-the-badge&logo=whatsapp" alt="Status Online"></a>
  <a href="#"><img src="https://img.shields.io/badge/VERSÃO-4.6.0-blueviolet?style=for-the-badge&logo=github" alt="Versão 4.6.0"></a>
  <a href="#"><img src="https://img.shields.io/badge/LICENÇA-MIT-orange?style=for-the-badge&logo=opensourceinitiative" alt="Licença MIT"></a>
</p>

<img src="https://xatimg.com/image/p0L7ZDQy9fD9.jpg" alt="Banner TED BOT V4.6" width="100%">

</div>

---

<div align="center">

## ✨ Visão Geral do Projeto
O **TED-BOT-V4.6** é um bot de WhatsApp robusto e de código aberto, desenvolvido para oferecer uma experiência **Multi-Dispositivo** completa. Construído com **Node.js**, ele é ideal para gerenciamento de grupos, automação de tarefas e diversas funcionalidades de entretenimento.

</div>

---

## ⚙️ Tecnologias Utilizadas

| Tecnologia | Descrição |
| :--- | :--- |
| **Node.js** | Ambiente de execução JavaScript principal. |
| **Baileys** | Biblioteca de conexão Multi-Dispositivo para WhatsApp. |
| **FFmpeg** | Necessário para manipulação de mídia (vídeos, áudios). |
| **Tesseract** | Utilizado para reconhecimento óptico de caracteres (OCR). |

---

## 🚀 Instalação Rápida (Termux)

Siga os passos abaixo para configurar e iniciar o bot no seu ambiente Termux.

### Pré-requisitos
Certifique-se de ter o aplicativo **Termux** instalado no seu dispositivo Android.

### Passo 1: Instalação de Dependências Essenciais
Este comando instala o Node.js, o gerenciador de pacotes, ferramentas de mídia e o Git.

```bash
apt-get update -y && pkg upgrade -y && pkg update -y && pkg install nodejs -y && pkg install nodejs-lts -y && pkg install ffmpeg -y && pkg install wget -y && pkg install tesseract -y && pkg install git -y
```
> **ATENÇÃO:** Será necessário digitar `y` toda vez que o sistema solicitar confirmação (`[y/n]`).

### Passo 2: Configuração de Armazenamento
Permite que o Termux acesse o armazenamento interno do seu dispositivo (cartão SD).

```bash
termux-setup-storage
```

### Passo 3: Clonagem do Repositório
Navegue até a pasta `Download` e clone o repositório oficial do bot.

```bash
cd /sdcard/Download && git clone https://github.com/TED-BOT-OFC/TED-BOT-V4.6
```

### Passo 4: Instalação e Início
Entre na pasta do projeto, instale as dependências e inicie o bot.

```bash
cd /storage/emulated/0/Download/TED-BOT-V4.6 && npm install --force --no-bin-links && npm start
```

---

<div align="center">

## 💾 START DO BOT 💾
Use este comando para iniciar o bot após a primeira instalação ou para reiniciá-lo.

```bash
npm start
```

</div>

---

<div align="center">

## 🤝 Contribuição e Suporte
Este projeto é mantido por [@Tedzinho](https://github.com/Tedzinho). Sinta-se à vontade para abrir *issues* ou enviar *pull requests* para melhorias.

<p align="center">
  <a href="https://github.com/TED-BOT-OFC"><img title="GitHub" src="https://img.shields.io/badge/GitHub-TED--BOT--OFC-black?style=for-the-badge&logo=github"></a>
  <a href="#"><img title="Autor" src="https://img.shields.io/badge/Autor-@tedzinho_-orange.svg?style=for-the-badge&logo=github"></a>
</p>

</div>

<div align="center">

<img src="https://readme-typing-svg.herokuapp.com/?font=mono&size=30&duration=4000&color=00008b&center=falso&vCenter=falso&lines=╰•★+𝐓𝐄𝐃-𝐁𝐎𝐓-𝐕𝟒.𝟔+★•╯;✨+O+Seu+Bot+Multi-Dispositivo+✨" alt="TED-BOT-V4.6 Typing SVG">

</div>
