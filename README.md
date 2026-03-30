# DevOps Lab: Flask + Monitoring

## 🖥️ Окружение выполнения

| Параметр | Значение |
|---|---|
| Гипервизор | Oracle VirtualBox 7.x |
| ОС | Ubuntu 22.04 LTS |
| RAM | 4 GB |
| CPU | 2 ядра |
| Docker | 24.x |
| Docker Compose | v2.x |

## 📁 Структура проекта
devops-lab/
├── devops9compose/ # Flask + Redis приложение
├── devops9prom/ # Prometheus + Grafana мониторинг
├── screenshots/ # Скриншоты работы
├── README.md
└── .gitignore

## 🚀 Часть 1: Запуск приложения (Flask + Redis)

```bash
cd devops9compose
docker compose up -d

## Проверка работы:
curl 127.0.0.1:8000
Доступ в браузере: http://127.0.0.1:8000
