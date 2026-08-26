# CRM System (Frontend)

Frontend частина CRM-системи: веб-інтерфейс для роботи з даними (перегляд/додавання/редагування) з адаптивною версткою під mobile та desktop.

## Tech stack

- **Next.js 15 (App Router)**  
- **React 19**
- **TypeScript**
- **CSS Modules / Global CSS**

## Features (high-level)

- **Responsive UI**: mobile / desktop
- **UI for data workflows**: базова логіка взаємодії з даними (CRUD-операції на рівні інтерфейсу)
- **Component-based approach**: перевикористовувані UI-блоки (за потреби/в процесі розвитку)

> Примітка: бекенд/база даних не входять у цей репозиторій (frontend only), якщо не зазначено інакше.

## Getting started

### Requirements

- **Node.js**: бажано LTS (18+)
- **npm** (або будь-який сумісний package manager)

### Install & run

```bash
npm install
npm run dev
```

Після запуску відкрий `http://localhost:3000`.

### Build & start (production)

```bash
npm run build
npm run start
```

## Scripts

- **dev**: запуск dev-сервера (Turbopack)
- **build**: production build
- **start**: запуск production-сервера
- **lint**: перевірка lint-правил (Next.js lint)

## Project structure

Основні точки входу:

- `src/app/layout.tsx` — кореневий layout
- `src/app/page.tsx` — головна сторінка
- `src/app/globals.css` — глобальні стилі

## Roadmap (optional)

- Додати сторінки/модулі CRM (Customers, Deals, Tasks)
- Підключити API (REST/GraphQL), стани завантаження та обробку помилок
- Авторизація (JWT/session), ролі та права доступу
- Таблиці з фільтрами/пагінацією, форми з валідацією


