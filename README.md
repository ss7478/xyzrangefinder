# hsv_rangefinder
Подборщик HSV маски для камеры

Основан на коде с https://github.com/PerfecXX/Python-HSV-Finder/blob/main/main.py

нужно установить:
pip install opencv-contrib-python
pip install pillow
pip install pyperclip

запускать из директории, где лежит файл. Рядом с файлом селектора класть картинку.
В переменной image_path лежит отсносительный путь к файлу. 
По умолчанию путь "123.jpg", измените, если хотите другой.

Алгоритм:

Смотрим в камеру дрона через браузер
Делаем скрин
Сохраняем в директорию с файлом селектора
Запускаем селектор
Подстраиваем ползунки, чтобы нужное изображение было на правой картинке белого цвета, а на средней - было не черным.
Копируем маску справа и вставляем в код.
Успех
