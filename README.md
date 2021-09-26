Мини тестовый сервер Flask

# Установка сервера

##### 1) Установка виртуального окружения

    python -m venv venv

##### 2) Активация VENV

    source venv/bin/activate # для windows вместо "bin" - "Scripts" 

##### 3) Установка зависимостей
    
    pip install -r req.txt

##### 4) Настройка переменных окружения FLASK_APP и FLASK_ENV
    
    export FLASK_APP="название приложения" # для windows "set FLASK_APP" 
    export FLASK_ENV=development # для windows "set FLASK_ENV" 

##### 5) Запуск сервера
    
    flask run (по умолчанию порт:5000, для запуска с другим "-p 5001")

##### 6) Проверка работоспособности в браузере

    http://localhost:5000 или http://127.0.0.1:5000
    
