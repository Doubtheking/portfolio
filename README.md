# Портфолио - готовый сайт

В этом архиве готовая структура сайта, который можно просто залить в GitHub и включить Pages:

**Содержимое:**
- `index.html` — главная страница (готовая, адаптивная).
- `assets/avatar.png` — аватарка (положите сюда, если хотите заменить).
- `.github/workflows/gh-pages.yml` — опциональный GitHub Actions workflow для автоматического деплоя в ветку `gh-pages`.

## Быстрая инструкция — самый простой путь (GitHub Pages)
1. Создайте публичный репозиторий на GitHub.
2. Распакуйте этот архив и загрузите файлы в корень репозитория (или используйте git):
   ```bash
   git init
   git add .
   git commit -m "Initial site"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
   git push -u origin main
   ```
3. На GitHub: Settings → Pages → Source → выберите `main` / `/ (root)` → Save.
4. Через пару минут сайт будет доступен по адресу `https://YOUR_USERNAME.github.io/YOUR_REPO/`.

## Альтернативный путь: использовать GitHub Actions (в workflow настроено)
Файл `.github/workflows/gh-pages.yml` автоматически задеплоит содержимое репозитория в ветку `gh-pages` при пуше в `main`. 
В этом случае в Pages выберите ветку `gh-pages` как источник.

---
Если хотите, могу подготовить ZIP без workflow, или изменить тексты/контакты в index.html перед упаковкой.
