# GLX TELEGRAM Userbot

Telegramu userbot gratis dengan banyak feature

## Limitation

Dikarenakan Gratisan Program ini memiliki limit

1. Max Client (4)
2. Ada Iklan

## FEATURES

1. Repeat Message
2. AFK
3. Chatbot auto reply


## Cara Run / Deploy
Untuk run program ini pastikan kamu menginstall

1. [Docker](https://docker.com/)

Buka Terminal

- Build
  
```bash
sudo docker build -t glx_telegram_userbot .
```

- Run
  Sebelum run pastikan kamu sudah build dahulu
```bash
sudo docker run -d --network host --memory="1g" --memory-swap="1g" --restart always --name userbot_pm -v $(pwd):/app userbot_pm
```

- Restart
  Jika kamu ingin mengganti config dengan yang baru silahkan restart ya
```bash 
sudo docker restart userbot_pm
```

- Stop
  
```bash 
sudo docker stop userbot_pm
```