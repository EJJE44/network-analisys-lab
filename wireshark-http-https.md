## 1. Отчет об анализе подозрительного HTTP пакета
* Отправитель: 192.168.31.237
* Получатель: 32.194.63.46
* Frame Length: 731 bytes
* Coloring Rule Name: bad TCP
* Protocol: TCP
* Time to Live: 64
* Source Port: 40054
* Destination Port: 80
* TCP Flags: SYN,SYN-ACK,ACK,FIN (RST:Absent)
* This f frame is a (suspected) out-of-order segment
* Severity level: Warning

В трафике обнаружена передача данных в незашифрованном виде, так же замечены сетевые задержки и пакеты "out-of-order segment", что говорит о нестабильности сетевого канала. Вредоносных файлов в теле HTTP-запроса не
обнаружено.

#### Итог:
1. Статус: Подозрительно
2. Рекомендуется перевести данный веб-ресурс на безопасное подключение(HTTPS), для исключение перехвата данных (MITM)

<img width="707" height="377" alt="изображение" src="https://github.com/user-attachments/assets/9842c586-e758-4086-a29d-809bfa7c1a0b" />
<img width="1081" height="410" alt="изображение" src="https://github.com/user-attachments/assets/b8f193dd-c6d1-49dd-b4ed-5fe9dccc6d8d" />
<img width="1474" height="398" alt="изображение" src="https://github.com/user-attachments/assets/8cb0300f-cfb4-4d10-ad27-0b8c2bdc63a5" />
<img width="896" height="270" alt="изображение" src="https://github.com/user-attachments/assets/5bd098cb-8735-46a3-8eaf-b2d6a4b33e5c" />
<img width="1013" height="187" alt="изображение" src="https://github.com/user-attachments/assets/ec4d2404-3d78-4aac-bd9f-3da382d18ffd" />
