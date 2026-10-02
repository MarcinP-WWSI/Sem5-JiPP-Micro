# Sem5-JiPP-Micro

## łączność

micro:bit-Radio + micro:bit-brama + PC/laptop
micro:bit + Arduino (+ ESP8266/ESP32 jeśli nie Uno R4 z Wifi)
Bluetooth (micro:bit v2) + telefon/laptop jako brama
USB-serial bezpośrednio do PC

## Protokół komunikacyjny

HTTP REST (POST wyniku, GET rankingu) ?
WebSocket ?

## Backend

FastAPI ?
Flask ?
Express / Note.js ?

## Baza danych

SQLite ?
PostgreSQL ?
Redis ?

## Hosting

Render / Railway / Fly.io 
Własny serwer + Docker Compose

## Wyświetlanie

WWW: prosta strona (czysty HTML+JS lub React) pobierająca GET /leaderboard, dożywiana przez WebSocket/Socket.io.
Na micro:bit: żądanie przez bramę → serwer zwraca top 3 → micro:bit przewija wyniki na siatce LED 5×5.
