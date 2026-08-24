# Anonymous × FT Community — Cigar Lounge Sponsorship Page

Статический лендинг для спонсорского предложения.

## Быстрый старт

### 1. Создайте репозиторий на GitHub
- Перейдите на [github.com/new](https://github.com/new)
- Имя: например `anonymous-ft-cigar-lounge`
- Видимость: **Public** (обязательно для бесплатного GitHub Pages)
- **Не** инициализируйте с README

### 2. Загрузите файлы
```bash
cd /tmp/anonymous-ft-cigar-lounge
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/ВАШ_USERNAME/anonymous-ft-cigar-lounge.git
git push -u origin main
```

Или одной командой через gh CLI (если авторизован):
```bash
cd /tmp/anonymous-ft-cigar-lounge
gh repo create anonymous-ft-cigar-lounge --public --source=. --push
```

### 3. Включите GitHub Pages
- Откройте **Settings → Pages**
- В разделе **Source** выберите: **GitHub Actions**
- Сохраните

### 4. Дождитесь деплоя
- Перейдите во вкладку **Actions**
- Дождитесь зелёного статуса workflow «Deploy to GitHub Pages»
- Ссылка появится в **Settings → Pages**

Формат URL: `https://ВАШ_USERNAME.github.io/anonymous-ft-cigar-lounge/`

---

## Изображения

Логотип бренда уже подключён по прямой ссылке в `index.html`.
Остальные фото (мастер, зона лаунжа) — placeholder-слоты с подписями.
Чтобы добавить свои фото:
1. Поместите файлы в папку `images/`
2. В `index.html` раскомментируйте `<img>` в нужном слоте и укажите путь `images/имя-файла.jpg`

## Редактирование данных

Все переменные — в объекте `CONFIG` в начале блока `<script>` файла `index.html`.
Измените там: бренд, даты, факты, пакеты, позиции, Telegram username.

## Дисклеймер

Визуализации являются концептом и согласуются перед производством.
