# RainbowColab
Крякай NTLM хеши радужными таблицами на [Google Colab](https://colab.research.google.com) с помощью  [Rainbow Crackalack](https://github.com/jtesta/rainbowcrackalack).

**Тебе нужен бесконечный диск на гугол драйв.**

[![Колба](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HydroSausager/RainbowColab/blob/master/rainbowcolab.ipynb)

Inspired by https://github.com/someshkar/colabcat

## Как юзать:

### 1. Убедись что у тебя есть "бесконечный" общий диск.
### 2. Получи **ID общего диска**:
  1. Открой корень общего диска в браузере
  2. **ID общего диска** будет в url после "./folders/" 
    - Пример **ID общего диска** - httр://drive.google.com/drive/folders/**0sssssQEqsq0000012A**
   
### 3. Создай проект в Google Developers Console:
  1. [ссылка](https://developers.google.com/drive/api/v3/quickstart/python)
  2. Нажми **Enable the Drive API**
  3. Имя делай любое или оставь **Quickstart**
  4. Выбери **Desktop App**
  5. Запомни свои **Client ID** и **Client Secret**

### 4. Создай папку **rainbow** в корне **общего диска**

### 5. Скачай радужную таблицу для 8 симв. NTLM в папку ...\rainbow\tables:
  - Как лучше всего закинуть 500 гб на гугл драйв - решать тебе, варианты:
    1. Подмонтировать через AirDrive/[ocamfuse](https://github.com/astrada/google-drive-ocamlfuse) и заливать день другой
    2. Можно попытаться подмонтировать непосредственно торент (не знаю что из этого получится, но может оно даже будет работать)

### 6. Пройди по [ссылке](https://colab.research.google.com/github/HydroSausager/RainbowColab/blob/master/rainbowcolab.ipynb) чтобы скопировать `rainbowcolab.ipynb` в свой Google Colab

### 6. Проинциализируй **ID общего диска**, **Client ID** и **Client Secret** в 2 блоке
  
### 7. Запусти по очереди все блоки, обращая внимания на комментарии.
