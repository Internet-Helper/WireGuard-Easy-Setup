<div align="center">
  <img src="https://github.com/user-attachments/assets/1f74035d-8be0-4cac-9670-54dbad1ccd56" width="20" alt="Telegram">
  <a href="https://t.me/Inter_net_Helper/9108">Чат в Telegram</a> для вопросов или обсуждения 
</div>

<div align="center">
  <img src="https://github.com/user-attachments/assets/b74aab60-2d5e-40de-a688-0eb3a58cbe11" width="20" alt="Money"> Поблагодарить можно через
  <a href="https://pay.cloudtips.ru/p/8ec8a87c">CloudTips</a> или <a href="https://yoomoney.ru/to/41001945296522">Юмани</a>
</div>

---

<img width="1104" height="139" alt="Top" src="https://github.com/user-attachments/assets/e95486c7-f25d-49e2-9ccb-ee58a4357806" />

<div align="center">
<img width="409" height="401" alt="image" src="https://github.com/user-attachments/assets/4f1d59dc-b728-4415-acf5-d4bd35234f59" />
</div>

***

Доступно три режима автоматического создания:

**1. Клиенты ⮂ Сервер ⮂ Интернет**  
   Для выхода в интернет через сервер.

**2. Клиенты ⮂ Сервер ⮂ Роутеры ⮂ Локальная сеть роутеров + Интернет**  
   Для выхода в интернет через один роутер на выбор и доступа в локальные сети всех роутеров.  
   Обязательно требуется настроить NAT для WireGuard на роутерах ([инструкция в разрабоктке...](https://github.com/Internet-Helper/WireGuard-Auto-Setup-Script/wiki)).

**3. Клиенты ⮂ Сервер ⮂ Роутеры ⮂ Локальная сеть роутеров**  
   Для доступа в локальные сети всех роутеров.

# Установка

Выполните эту команду, чтобы скачать скрипт, сделать его исполняемым и запустить с правами суперпользователя:
```
wget -O setup.sh https://raw.githubusercontent.com/Internet-Helper/WireGuard-Easy-Setup/refs/heads/main/setup.sh && chmod +x setup.sh && sudo ./setup.sh
```

# Быстрый запуск:

Чтобы запускать скрипт одной командой, например `ewg`, выполните команду:

```
sudo mv setup.sh /usr/local/bin/ewg
```

После этого вы сможете запускать скрипт из любого места простой командой:
```
ewg
```
