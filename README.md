# SkillSwap
<img width="232" height="69" alt="image" src="https://github.com/user-attachments/assets/9d25c591-8ec9-4118-ba4d-8774a6b02c63" />

Современный веб-проект, предназначенный для обмена навыками по принципу «Я научу / Хочу научиться». Платформа соединяет людей, которые хотят поделиться своими знаниями и умениями, с теми, кто стремится освоить новые навыки. SkillSwap создает сообщество, где каждый может быть и учителем, и учеником, помогая друг другу расти и развиваться в дружелюбной атмосфере.

**Демо:** https://skillswap331-production.up.railway.app/

## Технологический стек

### Frontend
- React 18, TypeScript
- Vite (сборка)
- Redux Toolkit, React Redux (управление состоянием)
- React Router v7 (маршрутизация)
- React Hook Form, Yup, @hookform/resolvers (валидация форм)
- Framer Motion (анимации)
- i18next, react-i18next (интернационализация)
- Storybook (разработка и документирование UI-компонентов)
- Vitest, React Testing Library, Cypress (тестирование)
- ESLint, Prettier, Stylelint (линтинг и форматирование)

### Backend
- NestJS 11, TypeScript
- TypeORM, PostgreSQL (работа с базой данных)
- JWT, Passport, bcrypt (аутентификация и безопасность)
- Socket.io (вебсокеты)
- Swagger (документация API)
- Winston (логирование)
- Jest, Supertest (тестирование)
- ESLint, Prettier (линтинг и форматирование)

## Тестирование

Проект покрыт тестами на обоих уровнях:
- Frontend: Vitest для модульного тестирования компонентов и хуков, Cypress для сквозного (E2E) тестирования пользовательских сценариев.
- Backend: Jest и Supertest для модульного и интеграционного тестирования контроллеров и сервисов.

## Структура проекта
Проект разделен на две основные части:
- frontend — клиентское приложение на React.
- backend — серверное приложение на NestJS.

