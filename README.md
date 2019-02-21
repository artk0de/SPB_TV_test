# SPB TV TEST SUITE

## 1. Запуск и установка

1. bundle
2. ruby app.rb

Для запуска тестирования

1. run app.rb
2. cd rspec
3. rspec

## 2. Методы

1.**POST** /videos/register

> Регистрирует пользователя и видео-поток

Параметры:

_customer_id_ - id пользователя

_video_id_ - id видеопотока

2. **GET** /videos/user_streams


> Возвращает количество активных видео-потоков для указанного пользователя

Параметры:

_customer_id_ - id пользователя

3. **GET** /videos/stream_users


> Возвращает список пользователей для заданного видео-потока

Параметры:

_video_id_ - id видео-потока

4. **GET** /videos/last_requests


> Возвращает количество запросов к серверу за последнюю минуту






