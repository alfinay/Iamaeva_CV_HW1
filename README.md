# ДЗ 1 «Фотолаборатория»

Курс «Введение в компьютерное зрение», Innopolis University, Fall 2026.

- `photolab.py` — инструмент командной строки: цветокоррекция, хромакей, геометрия, контактный лист.
- `REPORT.md` — отчёт: числа, ответы на три вопроса, место, где сломалось, и все команды (раздел 4).
- `data/` — пять своих фотографий и фон; `out/` — результаты команд.

## Запуск

```bash
pip install -r requirements.txt
pytest tests -q
python photolab.py gamma data/dark.jpg --gamma 0.5 -o out/dark_g05.jpg --hist out/dark_g05_hist.png
```

Полный список команд, которыми получены все файлы в `out/`, — в разделе 4 файла `REPORT.md`.
