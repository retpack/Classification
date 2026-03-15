# Sneaker Classifier (Adidas vs Nike vs Converse) 👟

Проект по классификации изображений кроссовок трех брендов с использованием Deep Learning (PyTorch). Включает в себя обучение модели и интерактивный интерфейс на Gradio.

## 🚀 Основные характеристики
*   **Архитектура:** ResNet18 (Transfer Learning).
*   **Стек:** PyTorch, Torchvision, Gradio, Google Colab.
*   **Датасет:** Изображения кроссовок Adidas, Nike и Converse.
*   **Интерфейс:** Веб-приложение на Gradio для предсказания по загруженному фото.

## 📊 Процесс обучения
Модель была обучена на 30 эпохах с использованием оптимизатора Adam. 
- Использованы аугментации: `RandomHorizontalFlip` и `Resize(224x224)`.
- Финальная точность (Accuracy) на валидации: 86,84%.

## 📁 Структура проекта
- `training_rev1.ipynb` — ноутбук с процессом подготовки данных и обучения.
- `view.ipynb` — запуск интерфейса Gradio.
- `requirements.txt` — необходимые библиотеки.

## 🛠 Как запустить
Клонируйте репозиторий:
   ```bash
   git clone https://github.com/retpack/Classification.git
```

### 📥 Веса модели (Weights)
Обученные веса для ResNet18 доступны в разделе [Releases].
Прямая ссылка на скачивание: [best_model.pth](https://github.com/retpack/Classification/releases/download/v1.0/best_model.pth).
   
