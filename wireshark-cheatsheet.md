Wireshark & Tshark

## 1. Захват трафика через tshark
**Просмотр доступных интерфейсов:** "tshark -D"
**Запуск записи в PCANG:** "tshark -i <interface> -w capture.pcapng"
**Чтение PCAP-файла с фильтром:** "tshark -r capture.pcapng -Y "<filter>"

## 2. Ключевые фильтры в Wireshark
"http" - отображение всех незашифрованных http-пакетов
"http.request.method == "GET"" - поиск конкретных GET-запросов
"tls.handshake.type == 1" - поиск Clietn Hello для извлечения SNI из HTTPS-трафика
"dns.flags.response == 0" - поиск исходящих DNS-запросов
