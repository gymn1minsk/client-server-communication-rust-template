# TCP клиент-сервер на Rust
## Что нужно сделать?
* Простой однопоточный (или многопоточный) TCP-сервер
* Простой TCP-клиент для работы с этим TCP-сервером
## Описание протокола
| Клиент | Данные                                                          | Сервер |
|--------|-----------------------------------------------------------------|--------|
| =>     | Запрос: отправка любых данных буфером в 1024 байта ([u8; 1024]) | =>     |
| <=     | Ответ: возврат всего буфера в 1024 байта ([u8; 1024]) клиенту   | <=     |
## Чем можно пользоветься?
* документацией Rust (можно найти в гугле)
* любыми другими источниками информации
