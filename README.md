# Aton Internship Task 4

## Введение

Для данного задания я использовал тот же сайт, что и в задаче 2

> **Примечание**: У моего основного сайта SSL-сертификаты выданы через Certbot и браузеры на них не ругаются. В этом проекте используются обычные сертификаты через сервис OpenSSL, и некоторые браузеры могут выдавать предупреждения. В остальном отличий от моего обычного сайта нет.

## О пайплайне

Пайплайн для Gitlab CI/CD обеспечивает оставноку, удаление старых образов и контейнеров, а затем запускает новую версию сайта.

## Всего в пайплайне три стадии:

1. Остановка контейнера, удаление контейнера, удаление образа

2. Построение образа следуя dockerfile

3. Запуск контейнера
