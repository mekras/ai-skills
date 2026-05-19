# Извлечённые факты: WEB-SKILL-DEVELOPMENT

Файл предназначен для промежуточного анализа. Сведения из него не становятся
правилами проекта автоматически: перед переносом в `knowledge/` нужно
проверить источник, область применения и актуальность.

## Метаданные

- `source_id`: `WEB-SKILL-DEVELOPMENT`
- `source_url`: `data/primary/web/skill-development-sources/index.yml`
- `retrieved_at`: 2026-05-19
- `last_checked_at`: 2026-05-19
- `publication_safety`: ok
- URL восстановлены 2026-05-19 поиском по точным названиям источников из
  `knowledge/skill-development.md` и проверкой открытых страниц.

## Факты

| ID | Утверждение | Фрагмент источника | Область применения | Опора в артефактах | Статус | Куда может перейти |
| --- | --- | --- | --- | --- | --- | --- |
| `WEB-SKILL-DEVELOPMENT-F001` | Навык должен опираться на реальный опыт, проектные артефакты и повторяемые ошибки, а не только на общие знания модели. | Разделы Agent Skills о real expertise и project artifacts. | проектирование навыков | `WEB-SKILL-DEVELOPMENT-001` | `content_updated` | `knowledge/skill-development.md` |
| `WEB-SKILL-DEVELOPMENT-F002` | Содержимое навыка конкурирует за контекст с остальной задачей, поэтому в `SKILL.md` нужно оставлять только то, что агент без навыка вероятно сделает неправильно. | Разделы Agent Skills о context и what to omit. | проектирование навыков | `WEB-SKILL-DEVELOPMENT-001`, `WEB-SKILL-DEVELOPMENT-004` | `content_updated` | `knowledge/skill-development.md` |
| `WEB-SKILL-DEVELOPMENT-F003` | `description` — механизм маршрутизации навыка; его нужно проверять положительными и отрицательными запросами. | Раздел Agent Skills об optimizing descriptions. | маршрутизация навыков | `WEB-SKILL-DEVELOPMENT-002`, `WEB-SKILL-DEVELOPMENT-004` | `content_updated` | `knowledge/skill-development.md` |
| `WEB-SKILL-DEVELOPMENT-F004` | Подробные и условные материалы стоит выносить в `references/`, `scripts/` и `assets/`, чтобы агент загружал их только при необходимости. | Разделы Agent Skills и Perplexity о progressive disclosure и hierarchy. | структура навыков | `WEB-SKILL-DEVELOPMENT-001`, `WEB-SKILL-DEVELOPMENT-004` | `content_updated` | `knowledge/skill-development.md` |
| `WEB-SKILL-DEVELOPMENT-F005` | Качество навыка нужно проверять сравнением с базовой версией, сохранением артефактов и человеческой проверкой результата. | Раздел Agent Skills об evaluating skill output quality. | оценка качества навыков | `WEB-SKILL-DEVELOPMENT-003` | `content_updated` | `knowledge/skill-development.md` |
| `WEB-SKILL-DEVELOPMENT-F006` | Проектные решения о русских навыках, приватных знаниях и слоях источников подтверждаются историей Git этого репозитория. | `git log --follow -- knowledge/skill-development.md`. | проектные решения этого репозитория | `WEB-SKILL-DEVELOPMENT-005` | `content_updated` | `knowledge/skill-development.md` |

## Вопросы

- Полные снимки внешних страниц не сохранены; при споре нужно повторно
  открыть URL и сверить актуальный текст.
- Первоначальный путь получения источников до 2026-05-19 в файле не был
  зафиксирован. Восстановление URL основано на точных названиях источников.
