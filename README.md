# Landing page врача-косметолога

Демо-лендинг для портфолио. Создан для демонстрации профессионального подхода к разработке медицинских сайтов.

## Технологии
- HTML5
- Tailwind CSS (CDN)
- Vanilla JavaScript
- Formspree (для формы)
- Google Fonts (Playfair Display + Inter)

## Особенности
- Полностью адаптивный дизайн (mobile-first)
- Премиальный минималистичный стиль
- Валидация формы на клиенте
- Маска для телефона
- Плавные анимации при скролле
- SEO-оптимизация (мета-теги, семантический HTML)

## Деплой на Vercel

### Шаг 1: Настройка Formspree
1. Зарегистрироваться на [formspree.io](https://formspree.io)
2. Создать новую форму
3. Скопировать endpoint (например: `https://formspree.io/f/xBbCcC`)
4. Вставить endpoint в `<form action="...">` в файле `index.html`

### Шаг 2: Загрузка на GitHub
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin <your-repo-url>
git push -u origin main
