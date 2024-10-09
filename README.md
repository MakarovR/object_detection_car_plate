# Алгоритм распознавания номерных знаков с применением двухпроходной нейронной сети Faster R-CNN InceptionV2

## 1. Детектирование номерных знаков

Использовался предобученный детектор на основе каскадов Хаара (метод Виолы-Джонса).

![](https://github.com/MakarovR/object_detection_car_plate/blob/main/images/pic2.jpg)

## 2. Данные для обучения ИНС

Для обучения двухпроходной нейронной сети были размечены данные номерных знаков.

![](https://github.com/MakarovR/object_detection_car_plate/blob/main/images/pic3.jpg)

## 3. Результат работы модели по распознаванию символов номерного знака

Точность распознавания составила 92% на тестовых данных.

![](https://github.com/MakarovR/object_detection_car_plate/blob/main/images/pic4.jpg)

### 4. В директории `/scripts` находятся некоторые оставшиеся скрипты
