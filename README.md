# Демонстрация дообучения Object Detection модели YOLOv8 на своих данных
Репозиторий демонстрирует процесс дообучения модели YOLOv8 для задачи обнаружения объектов (Object Detection) на пользовательском датасете карандашей. \
Включает подготовку данных, настройку конфигурации, запуск обучения и валидацию результатов.

## Полный код
Посмотреть исходный код с подробными комментариями можно по **ссылке**: \
https://colab.research.google.com/drive/18jBo8CJYepOsBWoHRkTvmXu0vB3vEaX8?usp=sharing

## Пример результата 
### Исходная YOLOv8 модель: 
не умеет определять карандаши, вместо карандашей видит другие объекты

<img align="center" src="https://github.com/user-attachments/assets/80071a4e-fdb4-4b09-b730-bf9aef567001" alt="Результат модели" width="70%" height="70%"/>


### Дообученная YOLOv8 модель: 
определяет карандаши

<img align="center" src="https://github.com/user-attachments/assets/2bc415e0-158c-4124-b3c1-4616f5a8696f" alt="Результат модели2" width="70%" height="70%"/>
