# Generative Models Notebooks

Коллекция Jupyter-ноутбуков с реализациями и экспериментами на основе генеративных нейросетей.

Здесь собраны различные модели, включая GAN, text-to-image, text-to-video и анимационные архитектуры. Цель — исследование и сравнение подходов генеративного ИИ в задачах создания изображений, видео и движений.

## 📁 Содержание

| Ноутбук                            | Модель / Тема                          | Описание                                  |
|------------------------------------|----------------------------------------|-------------------------------------------|
| `stackgan.ipynb`                   | StackGAN                               | Генерация изображений по тексту (StackGAN) |
| `mocogan.ipynb`                    | MoCoGAN                                | Генерация видео из шума и условных данных |
| `DCGAN_Text2Image.ipynb`          | DCGAN + Text2Image                     | Простая генерация изображений по описанию |
| `Deep Learning with PyTorch.ipynb`| GAN (PyTorch)                          | Базовый GAN на PyTorch для обучения       |
| `AI_text_to_video.ipynb`          | Text-to-Video (экспериментальный)      | Прототип генерации видео по тексту        |
| `articulated-animation.ipynb`     | Анимация по скелетной разметке         | Анимация объектов по точкам тела          |
| `First Order Animation Model.ipynb`| First Order Motion Model               | Анимация лица по образцу движения         |

## 🧰 Используемые технологии

- PyTorch
- TensorFlow / Keras (для отдельных моделей)
- OpenCV, PIL, NumPy
- Jupyter Notebook
- pre-trained модели и датасеты (см. внутри ноутбуков)

## 🚀 Как начать

1. Клонируйте репозиторий:

```bash
git clone https://github.com/yourusername/generative-models-notebooks.git
cd generative-models-notebooks
```

2. Установите зависимости.

3. Запустите Jupyter:

```bash
jupyter notebook
```
