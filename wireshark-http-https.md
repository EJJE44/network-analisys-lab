## 1. Отчет об анализе подозрительного HTTP пакета
* Отправитель: 192.168.31.237
* Получатель: 32.194.63.46
* Frame Length: 731 bytes
* Coloring Rule Name: bad TCP
* Protocol: TCP
* Time to Live: 64
* Source Port: 40054
* Destination Port: 80
* TCP Flags: PSH,ACK
* This f frame is a (suspected) out-of-order segment
* Severity level: Warning

В трафике обнаружена передача данных в незашифрованном виде, так же замечены сетевые задержки и пакеты "out-of-order segment", что говорит о нестабильности сетевого канала.
#### Итог:
1. Статус: Низкий уровень угрозы
2. Рекомендуется перевести данный веб-ресурс на безопасное подключение(HTTPS), для исключение перехвата данных (MITM)

<img width="707" height="377" alt="изображение" src="https://github.com/user-attachments/assets/9842c586-e758-4086-a29d-809bfa7c1a0b" />
<img width="1081" height="410" alt="изображение" src="https://github.com/user-attachments/assets/b8f193dd-c6d1-49dd-b4ed-5fe9dccc6d8d" />
<img width="1474" height="398" alt="изображение" src="https://github.com/user-attachments/assets/8cb0300f-cfb4-4d10-ad27-0b8c2bdc63a5" />
<img width="896" height="270" alt="изображение" src="https://github.com/user-attachments/assets/5bd098cb-8735-46a3-8eaf-b2d6a4b33e5c" />
<img width="1013" height="187" alt="изображение" src="https://github.com/user-attachments/assets/ec4d2404-3d78-4aac-bd9f-3da382d18ffd" />

## 2. Отчет об анализе пакета HTTPS (Client Hello)
1. Отправитель: 192.168.31.237
2. Получатель: 216.58.201.206
3. Frame Length: 236 bytes
4. Character encoding: ASCII
5. Coloring Rule Name: TCP
6. Protocol: TCP
7. Source Port: 52968
8. Destination Port: 443
9. Flags: 0x18 (PSH, ACK)
10. Handshake Protocol: Client Hello

#### Итог:
Статус: Безопасно

<img width="751" height="355" alt="изображение" src="https://github.com/user-attachments/assets/35368007-5e3e-4fa5-97cd-d41861ee54ca" />
<img width="923" height="418" alt="изображение" src="https://github.com/user-attachments/assets/c3a01429-c2ce-4e19-97a6-d222fd845c08" />
<img width="1034" height="398" alt="изображение" src="https://github.com/user-attachments/assets/bb3fc4e1-2e0b-447f-9efc-a00f1bc774aa" />
<img width="708" height="388" alt="изображение" src="https://github.com/user-attachments/assets/ef7b5f9c-3159-4ca6-a40f-45dc56628e20" />
<img width="926" height="440" alt="изображение" src="https://github.com/user-attachments/assets/ae0eec6e-28f1-4e57-9ceb-74139739518b" />
<img width="1730" height="313" alt="изображение" src="https://github.com/user-attachments/assets/408ee0c2-5791-48c2-b1e8-76c63ecc802e" />






