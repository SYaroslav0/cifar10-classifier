# CIFAR-10 Image Classifier (PyTorch)

Полный цикл обучения классификатора на CIFAR-10: от подготовки данных и MLP baseline до свёрточной сети (CNN).

## Status
🚧 В процессе
- [x] Данные: split train/val 45k/5k (seed), нормализация по статистикам только train
- [ ] MLP baseline
- [ ] Early stopping + checkpoint
- [ ] CNN

## Results
| model | val acc | test acc |
|---|---|---|
| MLP | — | — |

## How to run
1. Установи PyTorch по инструкции с [pytorch.org](https://pytorch.org/get-started/locally/) (для GPU выбери версию с CUDA)
2. `pip install -r requirements.txt`
3. Открой `cifar10.ipynb` в VS Code или Jupyter и выполни Run All

Датасет скачивается автоматически при первом запуске.
