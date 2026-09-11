# Мини-игра, которую каждый день дописывает роутина Claude

**Кейс 2 · шаг 2 — Сборка проекта**

- **Код:** [https://github.com/SupremeGoogle/GuessWhat](https://github.com/SupremeGoogle/GuessWhat) — бэклог, история агента и оператор лежат прямо в репозитории
- **Стек:** React 18 + TypeScript strict, Vite 6, чистый CSS на переменных, lucide-react, Web Audio API, canvas-confetti
- **Инструмент:** Claude, ежедневная роутина

## Промт

```text
<task>
Собери мобильную веб-игру по утверждённой механике.
</task>

<stack rule="не отклоняться">
React 18 + TypeScript в strict, Vite 6, чистый CSS на переменных.
Иконки только lucide-react.
Звук только через Web Audio API, синтезом на осцилляторах,
никаких аудиофайлов: игра должна весить мало и работать офлайн.
Конфетти — canvas-confetti.
Больше никаких зависимостей. Если кажется, что нужна ещё одна —
напиши почему и жди ответа, не ставь сам.
</stack>

<structure rule="создай ровно так">
src/App.tsx           роутинг экранов и глобальный стейт
src/components/       SplashScreen, StartMenu, LevelSelect,
                      Level1Game, LevelLockedModal
src/data/animals.ts   20 животных: id, название, вес в кг, факт
src/data/levels.ts    сетка из 30 уровней, открыт только первый
src/types/index.ts    Animal, LevelInfo, GameStats, PairComparison
src/utils/audio.ts    класс SoundManager
src/styles/index.css  дизайн-система на CSS-переменных
</structure>

<mechanics>
Две карточки, вопрос «Кто тяжелее?». Верно +1, неверно −2.
Раунд — 10 пар. Пары внутри раунда не повторяются.
Пара с одинаковым весом недопустима: подбирай другого кандидата,
иначе любой ответ засчитается как ошибка.
</mechanics>

<constraints>
— Mobile-first. Минимальная зона нажатия 48×48 px: играть будут
  большим пальцем одной рукой в транспорте.
— Деплой на GitHub Pages в подпапку /GuessWhat/, поэтому пути
  к ассетам только относительные. Абсолютный путь соберётся
  без ошибки и сломается только в проде — там его никто не поймает.
— tsc --noEmit проходит без единой ошибки.
— Веса животных не выдумывай. Не уверен в цифре — ставь TODO
  с пометкой, что именно надо проверить. Я сверю по источникам сам.
  Правдоподобная выдуманная цифра хуже пропуска: её никто
  не заметит, а ребёнок запомнит неправильно.
</constraints>

<definition_of_done>
1. npm run build и tsc --noEmit проходят чисто.
2. Раунд из 10 пар проходится без повторов и без ничьих.
3. В консоли ноль ошибок за полный проход уровня.
4. Ни одной цифры без источника или без TODO.
</definition_of_done>

<output_format>
Сначала дерево файлов и список экспортируемых типов.
Жди подтверждения. Код — вторым сообщением.
</output_format>
```

---

[https://github.com/SupremeGoogle/prompt-portfolio](https://github.com/SupremeGoogle/prompt-portfolio)
