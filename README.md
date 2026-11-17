# PRODELKI / skills

Библиотека творческих скиллов проекта «Проделки». Отдельно от [PRODELKI/post](https://github.com/PRODELKI/post) с редакционными правилами и SMM-скиллами.

## Начни отсюда

- **[PRODELKI_STORY_AND_REELS_EDITORIAL.md](PRODELKI_STORY_AND_REELS_EDITORIAL.md)** — собственный регламент эмоциональных мультфильмов, Reels и короткометражек.
- **[prodelki-emotional-story-director/SKILL.md](.agents/skills/prodelki-emotional-story-director/SKILL.md)** — главный авторский сценарный скилл. Первый этап — идея и эмоция, последний — AI-генерация.
- [PRODELKI_MASTER_EDITORIAL_RULES.md](https://github.com/PRODELKI/post/blob/main/PRODELKI_MASTER_EDITORIAL_RULES.md) — исходный редакционный регламент, не заменён.

## Импортированы: сценарий, анимация и Reels

| Skill | Назначение | Оригинал |
|---|---|---|
| [creative-director](.agents/skills/creative-director/SKILL.md) | Инсайты, большие идеи, оценка оригинальности и эмоции | [smixs/creative-director-skill](https://github.com/smixs/creative-director-skill) |
| [short-film-development](.agents/skills/short-film-development/SKILL.md) | Герой, конфликт, stakes, сюжет, синопсис | [0xhughs/director-skills](https://github.com/0xhughs/director-skills) |
| [film-storytelling](.agents/skills/film-storytelling/SKILL.md) | Сценарий, причинность и заслуженный эмоциональный финал | [universal-ai-film](https://github.com/universal-ai-film/universal-ai-film-director) |
| [ai-director-video](.agents/skills/ai-director-video/SKILL.md) | Режиссура, драматургия, камеры, монтаж, промпты | [smixs/visual-skills](https://github.com/smixs/visual-skills) |
| [short-form-video-script](.agents/skills/short-form-video-script/SKILL.md) | Вертикальные Reels/Shorts/TikTok, удержание и монтажный ритм | [social-media-skills/skills](https://github.com/social-media-skills/skills) |
| [visual-storytelling](.agents/skills/visual-storytelling/SKILL.md) | Эмоциональные траектории и драматическая структура | [Designly](https://github.com/imMamdouhaboammar/designly) |
| [prodelki-emotional-story-director](.agents/skills/prodelki-emotional-story-director/SKILL.md) | Собственная система PRODELKI | Оригинальный проектный скилл |

### Полный Hook Master: 9 связанных скиллов

Перенесён весь комплект, чтобы центральный скилл не ссылался на отсутствующие модули:

- [hook-master](.agents/skills/hook-master/SKILL.md) — главный маршрутизатор
- [viewer-panel](.agents/skills/viewer-panel/SKILL.md) — шесть предполагаемых точек зрения
- [the-council](.agents/skills/the-council/SKILL.md) — финальный разбор
- [four-failures-check](.agents/skills/four-failures-check/SKILL.md) — диагностика проблем хука
- [hook-formats](.agents/skills/hook-formats/SKILL.md) — шесть формулировок
- [niche-tuner](.agents/skills/niche-tuner/SKILL.md) — адаптация аудитории
- [viral-scout](.agents/skills/viral-scout/SKILL.md) — изучение реальных примеров
- [visual-match](.agents/skills/visual-match/SKILL.md) — согласование первого кадра и текста
- [lock-in](.agents/skills/lock-in/SKILL.md) — следующие секунды после хука

[Оригинал Hook Master](https://github.com/Liamrjohnston/hook-master-skill) · MIT, Liam Johnston.

## Файлы и зависимости

- У импортированных скиллов сохранены оригинальные SKILL.md, методические references и необходимые шаблоны: по задаче читай только соответствующие файлы.
- **Creative Director:** методики и большие навигационные MOC сохранены; не зеркалированы все ~570 индивидуальных кейсов чужого архива. При разборе кейсов используй [оригинальную библиотеку](https://github.com/smixs/creative-director-skill/tree/main/creative-director/references/legendary-campaigns). Относительные ссылки MOC на отсутствующие локально карточки могут не открываться; для них переходи в оригинальный архив по ссылке выше.
- **Designly:** импортированы модуль Visual Storytelling и его непосредственные справочные файлы. Другие модули полной 21-skill-платформы Designly — самостоятельный продукт, [оригинал здесь](https://github.com/imMamdouhaboammar/designly). Для некоторых перекрёстных упоминаний нужны другие его навыки.
- Большие агрегаторы [skills.sh](https://skills.sh) и сторонние каталоги не являются единичными SKILL.md и не устанавливаются как один навык.
- Готовые файлы в GitHub **не равны** автоматическому подключению инструментов к ChatGPT, аккаунтам Flow/Instagram или правам на публикацию.

## Лицензии и авторство

- [CC BY 4.0 — Serge Shima](licenses/CC-BY-4.0-Serge-Shima.txt): Creative Director + Visual Skills. Атрибуция: [creative-director-skill](https://github.com/smixs/creative-director-skill), [visual-skills](https://github.com/smixs/visual-skills).
- [MIT — 0xhughs](licenses/short-film-development-MIT.txt).
- [MIT — Universal AI Film Director contributors](licenses/film-storytelling-MIT.txt).
- [MIT — Frank Heijdenrijk](licenses/short-form-video-script-MIT.txt).
- [MIT — Liam Johnston](licenses/hook-master-MIT.txt).
- [Designly NOTICE](licenses/designly-NOTICE.txt): в package.json указана лицензия MIT; отдельного корневого LICENSE-файла нет, а NOTICE требует атрибуции сторонних CC BY 4.0-модулей. Использовать с учётом этой оговорки.
- `prodelki-emotional-story-director` и `PRODELKI_STORY_AND_REELS_EDITORIAL.md` написаны специально для PRODELKI, авторство первоисточников не присваивают.

**Главное правило:** сценарий с подготовленным эмоциональным финалом утверждаем **до генерации**, а не после расходования кредитов на неработающую идею.
