# Создание своих карточек игры в Dobble (Spot It!)
# Настройка

1. python -m venv venv
2. venv\Scripts\activate
3. pip install -r requirements.txt

# Изображения для карточек

Создайте в директории проекта папку с изображениями. Необходимо РОВНО 57 и 31 для полной и детской версии соответственно .PNG(!) изображений.

# Запуск и получение результата
Полная версия
```
python3 -m dobble --symbols_folder <ПАПКА_С_ИЗОБРАЖЕНИЯМИ> --output_folder <ПАПКА_ДЛЯ_РЕЗУЛЬТАТА>
```

Детская версия
```
python3 -m dobble --junior_size --symbols_folder <ПАПКА_С_ИЗОБРАЖЕНИЯМИ> --output_folder <ПАПКА_ДЛЯ_РЕЗУЛЬТАТА>
```

Для пробного запуска используйте
```
python3 -m dobble --symbols_folder images/symbols_examples/ --output_folder result
```

Конечный результат будет в указанной вами папке (ВАША_ПАПКА/4_print/cards.pdf) в формате .PDF
