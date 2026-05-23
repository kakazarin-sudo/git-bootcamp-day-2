# sample-cli

Утилита-пример для демонстрации стандартных файлов проекта.
В реальной жизни здесь была бы пара абзацев о том, что делает проект и кому он нужен.

## Содержание

- [sample-cli](#sample-cli)
  - [Содержание](#содержание)
  - [TODO](#todo)
  - [Быстрый старт](#быстрый-старт)
  - [Установка](#установка)
  - [Использование](#использование)
  - [Разработка](#разработка)
  - [Лицензия](#лицензия)

## TODO
 - [x] важный пункт 1
 - [ ] важный пункт 2
 - [ ] важынй пункт 3

## Быстрый старт

```bash
git clone git@github.com:example/sample-cli.git
cd sample-cli
python -m sample_cli --help
```

## Установка

Зависимости: Python 3.11+. Виртуальное окружение по желанию.

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Использование

Простейший сценарий:

```bash
python -m sample_cli greet --name "Git Bootcamp"
# → Hello, Git Bootcamp!
```

<details>
<summary>Расширенный сценарий (со сворачиваемым блоком)</summary>

```bash
python -m sample_cli greet --name "Git" --shout
# → HELLO, GIT!
```

Внутри `<details>` можно прятать редко нужные подробности, чтобы основной README оставался коротким.

</details>

## Разработка

- Запуск тестов: `pytest`
- Стиль: `ruff check .`
- Перед PR — см. [CONTRIBUTING.md](CONTRIBUTING.md).

## Лицензия

MIT — см. [LICENSE](LICENSE).
