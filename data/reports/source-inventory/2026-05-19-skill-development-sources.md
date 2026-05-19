# Технический отчёт по источникам: 2026-05-19

## Проверка

- `checked_at`: 2026-05-19
- `manifest`: `data/sources-manifest.yml`
- `registry`: `data/primary/web/skill-development-sources/index.yml`
- `checked_by`: Codex

## Сводка

| Статус | Количество |
| --- | ---: |
| `synced` | 4 |
| `project-history` | 1 |
| `manual-required` | 0 |
| `fetch-error` | 0 |

## Источники

### WEB-SKILL-DEVELOPMENT — Публичные источники по проектированию навыков агента

- `status`: synced
- `adapter`: manual-web
- `locator`: `knowledge/skill-development.md#источники`
- `change`: new
- `artifacts`:
  - `data/primary/web/skill-development-sources/index.yml`
  - `data/primary/web/skill-development-sources/facts/extracted-facts.md`
- `limitations`: первоначальные URL в `knowledge/skill-development.md` не были сохранены; ссылки восстановлены поиском по точным названиям источников.

## Изменения состава источников

- Зафиксированы четыре публичных URL, соответствующие ранее указанным
  источникам Agent Skills и Perplexity Research.
- Добавлен локальный источник `Git history` для проектных решений, которые не
  являются внешним фактом.

## Изменения содержимого

- Создан индекс источников для `knowledge/skill-development.md`.
- Создан промежуточный файл извлечённых фактов с опорой на URL и историю Git.

## Ошибки и ручные проверки

- Ошибок получения не обнаружено.
- Полные снимки страниц не сохранялись; при спорных правках нужна повторная
  ручная сверка URL.

## Следующий шаг

- Нужен `source-impact-audit` для обновления `knowledge/skill-development.md`
  по зафиксированным источникам.
