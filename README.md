# Выбор Dockerfile для запуска StaticJinjaPlus

Доступны два варианта Dockerfile для запуска приложения StaticJinjaPlus:

- **Образ на основе Ubuntu**
- **Образ на основе Python-slim**

## Инструкция по запуску контейнера

1. **Скачайте нужный вариант Dockerfile.**
   - Для использования конкретной версии StaticJinjaPlus скачать Dockerfile без `_latest`
   - Для использования самой свежей версии StaticJinjaPlus при сборке скачать Dockerfile с припиской `_latest`

3. **Создайте необходимые папки:**
   - Папку для шаблонов страниц.
   - Папку для сборки финальных версий страниц.

4. **Создайте контейнер** с использованием скачанного Dockerfile.

## Возможные аргументы для контейнера

- `--build-arg VERSION`:
  - **0.1.0**
  - **0.1.1**

### Описание аргументов

- Числа `0.1.0` и `0.1.1` обозначают версии StaticJinjaPlus.
