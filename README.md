# Промт-портфолио — Гафаров Акбар

AI-креатор, вайбкодер. Калининград.

Проекты, собранные через нейросети. По каждому — название, стек и промт целиком, в том виде, в котором он уходил в модель.

Каждый промт лежит отдельным файлом: название проекта, стек и промт целиком.

- [Три дизайн-концепции — вывод модели целиком](artifacts/design-concepts.md)
- Портфолио: https://cv-akbar.vercel.app

---

## 1. Городское собрание: лендинг, QR-билеты и админка на входе

*Мероприятие под ключ · Codex*

- **Лендинг:** [kiberone.vercel.app](https://kiberone.vercel.app/)
- **Код:** [github.com/SupremeGoogle/KIBERone](https://github.com/SupremeGoogle/KIBERone)
- **Стек:** React 19 + TypeScript, Vite, Tailwind, react-router-dom 7. Supabase — база и realtime, qrcode.react — генерация QR, @yudiel/react-qr-scanner — сканер, EmailJS — письма, jsPDF + html2canvas — PDF-билет, motion — анимации
- **Инструмент:** Codex

**Промты:**

- [Схема данных и лендинг с регистрацией](prompts/01-1-shema-dannyh-i-lending-s-registraciey.md)
- [QR-билет и письмо на почту](prompts/01-2-qr-bilet-i-pismo-na-pochtu.md)
- [Админка со сканером на входе](prompts/01-3-adminka-so-skanerom-na-vhode.md)

## 2. Мини-игра, которую каждый день дописывает роутина Claude

*Мини-игра · ежедневная роутина*

- **Код:** [github.com/SupremeGoogle/GuessWhat](https://github.com/SupremeGoogle/GuessWhat) — бэклог, история агента и оператор лежат прямо в репозитории
- **Стек:** React 18 + TypeScript strict, Vite 6, чистый CSS на переменных, lucide-react, Web Audio API, canvas-confetti
- **Инструмент:** Claude, ежедневная роутина

**Промты:**

- [Концепт до кода](prompts/02-1-koncept-do-koda.md)
- [Сборка проекта](prompts/02-2-sborka-proekta.md)
- [Точечный разбор багов](prompts/02-3-tochechnyy-razbor-bagov.md)
- [Оператор ежедневной роутины](prompts/02-4-operator-ezhednevnoy-routiny.md)
- [Когда бэклог кончился — роутина переключилась на проверку](prompts/02-5-kogda-beklog-konchilsya-routina-pereklyuch.md)

## 3. Шаблон, из которого вышло больше двадцати лендингов

*Промт-шаблон · поток задач*

- **Примеры:** [aristo39.com](https://aristo39.com/) — гардеробные системы и двери-купе · [stalnoe-osnovanie.ru](https://stalnoe-osnovanie.ru) — свайно-винтовые фундаменты · [baltmag.vercel.app](https://baltmag.vercel.app) — хозтовары и бытовая химия · [pasteria.vercel.app](https://pasteria.vercel.app)
- **Ещё:** Crown Shine, L.A. Coffee, Точка Гриль, Нотариус, Молодость — [репозитории](https://github.com/SupremeGoogle)
- **Масштаб:** 20+ проданных сайтов, большинство клиентов пришли сами

**Промты:**

- [Шаблон целиком](prompts/04-1-shablon-celikom.md)

## 4. Три дизайн-концепции до первой строки кода

*Арт-дирекшн*

- **Артефакт:** Вывод модели целиком сохранён в репозитории портфолио — можно открыть и сверить с промтом

**Промты:**

- [Дизайн-исследование](prompts/05-1-dizayn-issledovanie.md)
- [Вёрстка по выбранной концепции](prompts/05-2-verstka-po-vybrannoy-koncepcii.md)

## 5. Шесть кадров, которые выглядят как один фотосет

*Генерация изображений*

- **Проект:** Лендинг кофейни [la-coffee.vercel.app](https://la-coffee.vercel.app)
- **Задача:** Шесть кадров одного фотосета для первого экрана и блока «о нас»

**Промты:**

- [Общая база, шесть кадров и список проверки](prompts/06-1-obschaya-baza-shest-kadrov-i-spisok-prover.md)

## 6. Бот, который не теряет источник лида

*Telegram-боты · CRM*

- **Боты:** [t.me/kiberoneKLD_bot](https://t.me/kiberoneKLD_bot) · [t.me/veri_x_bot](https://t.me/veri_x_bot) · [t.me/AZTmoto_bot](https://t.me/AZTmoto_bot)
- **Стек:** Python, aiogram 3 с FSM, PostgreSQL, Flask на приёме вебхуков, REST API CRM с ключом в заголовке

**Промты:**

- [Постановка задачи от метрики, а не от функции](prompts/08-1-postanovka-zadachi-ot-metriki-a-ne-ot-funk.md)

## 7. Конспект мастер-класса как лид-магнит

*Лид-магнит · контент*

- **Сайт:** [konspekt-three.vercel.app](https://konspekt-three.vercel.app)
- **Код:** [github.com/SupremeGoogle/Konspekt](https://github.com/SupremeGoogle/Konspekt)
- **Стек:** React 19, TypeScript, Vite, Tailwind, Framer Motion, lucide-react, Vercel

**Промты:**

- [Промт с запретом достраивать](prompts/09-1-promt-s-zapretom-dostraivat.md)

## 8. Свадебная фотогалерея в реальном времени

*Продукт под событие · Next.js*

- **Сайт:** [ruslan-marina.vercel.app](https://ruslan-marina.vercel.app)
- **Код:** [github.com/SupremeGoogle/Ruslan-Marina](https://github.com/SupremeGoogle/Ruslan-Marina)
- **Стек:** Next.js 16, React 19, TypeScript. Supabase — база и хранилище, jszip — архив, canvas-confetti, Vitest с покрытием — тесты API-роутов и хелперов. Шрифты Great Vibes, Alex Brush, Marck Script для кириллицы

**Промты:**

- [Постановка от условий зала, а не от макета](prompts/10-1-postanovka-ot-usloviy-zala-a-ne-ot-maketa.md)
- [Вход, который не выглядит как форма](prompts/10-2-vhod-kotoryy-ne-vyglyadit-kak-forma.md)
