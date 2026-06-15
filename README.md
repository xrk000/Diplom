# ProductiveMe

Веб-приложение для управления личной продуктивностью.

## Запуск проекта

Код проекта находится в папке `productiveme/summit-stride-lab`.

1. Склонировать репозиторий и перейти в папку проекта:
   ```
   git clone <ссылка-на-репозиторий>
   cd Diplom/productiveme/summit-stride-lab
   ```

2. Установить зависимости:
   ```
   npm install
   ```

3. Запустить в режиме разработки:
   ```
   npm run build
   npm run dev
   ```
   Приложение откроется по адресу http://localhost:8080

## Технологии

- **Фронтенд:** React + TypeScript + Vite, Tailwind CSS, shadcn/ui, Recharts
- **Бэкенд:** Supabase (PostgreSQL, RLS, Auth, Edge Functions)
- **Интеграции:** Google Calendar, Яндекс.Календарь, VK Messenger бот

## Модули

Dashboard, Tasks, Projects, Notes, Calendar, Habits, Search, Analytics.

> Файл `.env` с ключами уже в репозитории, дополнительная настройка не требуется.
