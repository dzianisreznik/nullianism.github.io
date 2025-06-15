# Nullianism Website

Официальный сайт Нуллианства - первой в мире научной Open-Source религии.

## 🚀 Быстрый старт

### Запуск в режиме разработки

```bash
# Перейти в директорию проекта
cd path/to/nullianism.github.io

# Установить зависимости (если еще не установлены)
npm install

# Обновить контент из основного репозитория
npm run submodule-update
npm run sync-content

# Запустить сервер разработки
npm run dev
```

Сайт будет доступен по адресу: http://localhost:3000

### Сборка для продакшена

```bash
# Собрать статический сайт
npm run build

# Посмотреть собранный сайт локально
npx serve out
```

## 📁 Структура проекта

- `app/` - страницы и компоненты Next.js App Router
- `components/` - переиспользуемые React компоненты
- `content/` - синхронизированный контент из основного репозитория
- `content-source/` - git submodule с оригинальным контентом
- `lib/` - утилиты и константы
- `public/` - статические файлы
- `scripts/` - скрипты для синхронизации контента

## 🔧 Основные команды

- `npm run dev` - запуск сервера разработки
- `npm run build` - сборка для продакшена (включает синхронизацию контента)
- `npm run sync-content` - синхронизация контента из submodule
- `npm run submodule-update` - обновление submodule до последней версии

## 🌐 Деплой

Сайт автоматически деплоится на GitHub Pages при push в main ветку.

Live: https://nullianism.github.io
