# Проект 9. Распознавание эмоций на видео
- Реализация модуля поиска лица на видео
- Обучение модели распознавания не менее 5 эмоций
- Реализация интерфейса, позволяющий считывать эмоции
человека с видео или веб-камеры, с выводом результата и
вероятностью эмоций

-------

# Необходимо скачать:
- [Используемый датасет](https://www.kaggle.com/datasets/msambare/fer2013)
- [Модуль детекции лица](https://www.kaggle.com/datasets/gxy19980906/haarcascade-frontalface-defaultxml)
- Обученные модели в формате ONNX:
  - [EfficientNet](https://drive.google.com/file/d/1c2GFy0UjyIkQpbvkjEu3ZQsTrHkHcCvQ/view?usp=sharing)
  - [ResNet18](https://drive.google.com/file/d/1A7_NSVuUtZTJ6gGbVY7zNp-JZjhTWoh9/view?usp=sharing)
  - [Yolo11n](https://drive.google.com/file/d/1_BQcdo4hRQWVVz2Y2YPhtLD2kwnugerW/view?usp=sharing)

Установить необходимые библиотеки:
```
pip install -r requirements.txt
```

-------

В ноутбуке представлен весь процесс подготовки датасета, обучения и валидации моделей, создание веб-интерфейса с Gradio.

-------
# Пример работы моделей

Данное видео:

![man_worried.gif](https://github.com/J1wZ/emotion_recognition/blob/main/gifs/man_worried.gif)

Вывод EfficientNet:

![output_EfficientNet_gradio.gif](https://github.com/J1wZ/emotion_recognition/blob/main/gifs/output_EfficientNet_gradio.gif)

Вывод ResNet18:

![output_ResNet18_gradio.gif](https://github.com/J1wZ/emotion_recognition/blob/main/gifs/output_ResNet18_gradio.gif)

Вывод Yolo11n:

![output_Yolo11n_gradio.gif](https://github.com/J1wZ/emotion_recognition/blob/main/gifs/output_Yolo11n_gradio.gif)

-----
# Ссылки:
- [Презентация](https://github.com/J1wZ/emotion_recognition/blob/main/report%20and%20presentation/ПирожковаАД_Итоговое_задание.pptx)
- [Отчет](https://github.com/J1wZ/emotion_recognition/blob/main/report%20and%20presentation/ПирожковаАД_Отчет_итоговая_работа.docx)
- [Деплой веб-интерфейса на Hugging Face](https://huggingface.co/spaces/J1wZ/emotion_recognition)
