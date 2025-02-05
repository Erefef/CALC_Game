# CALC Game

**CALC Game** — это консольная игра, которая показывается случайное арифметическое выражение с операциями +, -, *, содержащее четыре операнда (например 35+16*2-4), которое нужно вычислить и записать ответ. После этого программа должна вывести соответствующее сообщение и правильный ответ.

## Установка

### Локальная установка
1. Клонируйте репозиторий:
   ```bash
   git clone https://github.com/Erefef/CALC_Game.git
   cd Game_name
2. Установите зависимости через Composer:
    ```bash
    composer install
- Запустите игру:
    ```bash
    php bin/calc
### Установка через Packagist
1. Убедитесь, что Composer установлен глобально.
2. Установите игру:
    ```bash
    composer global require erefef/php_tenyakshev_ma
3. Запустите игру из командной строки:
    ```bash
    gcd
## Используемые технологии
- PHP — основной язык разработки.
- Composer — для управления зависимостями и автозагрузки.
- wp-cli/php-cli-tools — библиотека для удобного ввода/вывода в консоли.
## Структура проекта

Task01/CALC \
├── bin/ \
│   └── calc       # Запускной файл игры \
├── src/ \
│   ├── Controller.php        # Логика управления игрой \
│   └── View.php              # Функции отображения \
├── composer.json             # Файл конфигурации Composer \
└── README.md                 # Описание проекта 

## Ссылки
- Packagist: [GCD Game](https://packagist.org/packages/erefef/php_tenyakshev_ma)
- [Репозиторий на GitHub](https://github.com/Erefef/CALC_Game)
- Автор: erefef
- Лицензия: MIT
