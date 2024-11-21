# Cyb04-onl

## ДЗ №8 Типы атак II
Spam, DDOS, botnet, MIM, Viruses

### 1. Провести DOS атаку на Juice Shop 
[Install Docker on Kali](https://www.kali.org/docs/containers/installing-docker-on-kali/)

`kali@kali:~$ sudo apt update`
`kali@kali:~$ sudo apt install -y docker.io`
`kali@kali:~$ sudo systemctl enable docker --now`
`kali@kali:~$ docker`

![Docker](pic1.png)
![Docker](pic2.png)

[Install Juice-Shop](https://github.com/juice-shop/juice-shop?tab=readme-ov-file#setup)

Run `docker pull bkimminich/juice-shop`
Run `docker run --rm -p 127.0.0.1:3000:3000 bkimminich/juice-shop`
Browse to `http://localhost:3000`

![Juice-Shop](pic3.png)

Download, compile and run [XERXES](https://github.com/XCHADXFAQ77X/XERXES):
![Juice-Shop](pic4.png)



[Back to main (GitHub)](https://github.com/andreyklass94/Cyb04/tree/main)
