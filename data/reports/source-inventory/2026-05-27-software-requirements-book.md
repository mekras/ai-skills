# Технический отчёт по источникам: 2026-05-27

## Проверка

- `checked_at`: 2026-05-27
- `manifest`: `data/sources-manifest.yml`
- `source_index`: `data/primary/local/software-requirements-3e/index.yml`
- `checked_by`: Codex

## Сводка

| Статус | Количество |
| --- | ---: |
| `checked-local` | 1 |
| `manual-required` | 0 |
| `read-error` | 0 |

## Источники

### LOCAL-SOFTWARE-REQUIREMENTS-3E — Software Requirements, Third Edition

- `status`: checked-local
- `adapter`: manual-local-pdf
- `locator`: локальный PDF пользователя, путь не сохраняется в отслеживаемых
  файлах
- `change`: new
- `artifacts`:
  - `data/primary/local/software-requirements-3e/index.yml`
  - `data/primary/local/software-requirements-3e/facts/extracted-facts.md`
- `limitations`: источник защищён авторским правом; полный текст, длинные
  цитаты и путь к личной библиотеке не сохранялись.

## Изменения состава источников

- Добавлен локальный источник с библиографической опорой на книгу Карла
  Вигерса и Джой Битти о требованиях к ПО.

## Изменения содержимого

- Проверены метаданные PDF через `pdfinfo`.
- Извлечён временный текст через `pdftotext` для анализа оглавления и
  методической структуры; временный файл не добавлен в Git.
- Создан промежуточный файл фактов с пересказанными утверждениями.

## Ошибки и ручные проверки

- Ошибок чтения не обнаружено.
- При спорных правках нужно повторно сверить локальный PDF.

## Следующий шаг

- Использовать извлечённые факты при создании семейства навыков
  `requirements-*`.
