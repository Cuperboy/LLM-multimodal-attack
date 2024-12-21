# LLM-multimodal-attack
Работа подготовлена студентом 402 группы Канта Даниэлем. (В рамках спецкурса "Современные методы машинного обучения" на ВМК)

Задание посвящено атакам мультимодальных больших языковых моделей (LLM), выполняющей классификацию текстов.

В репозитории представлены:
- реализация [BIM](https://arxiv.org/pdf/1607.02533) атаки
- результаты атаки (clear + adv images, results.json, метрики ASR и [SSIM](https://arxiv.org/pdf/2002.02657))

# Часть 0. Библиотеки


# Часть 1. Атака


# Часть 2. Результаты
Структура results.json:
- ответы модели на clear images
- ответы модели на adversarial images
- в конце находятся метрики [SSIM](https://arxiv.org/pdf/2002.02657) и ASR

В clear images находятся картинки, искользовавшиеся в работе.
В adv images находятся зашумленные картинки.
