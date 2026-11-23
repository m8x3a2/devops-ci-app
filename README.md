# devops-ci-app

Учебное Flask-приложение для практической работы № 10.

Конвейер: Pylint → pytest → Docker build → smoke-test → GHCR.
Теги реестра обновляются только при `push` в `main`. Pull Request выполняет проверки и пробный запуск контейнера.

- Проверка жизнеспособности: `/health`.
- Образ: `ghcr.io/m8x3a2/devops-ci-app`.
- Конвейер: `.github/workflows/ci.yml`.
