# Summary

* Про разработку
  * [Про код-стайл, зачем он нужен и как должен выглядеть](./development/2024-01-17.md)
  * [Про разделение кода (чанки)](./development/2024-01-25.md)
  * [Паттерн switch(true)](./development/2024-01-27.md)
  * [Типичная ошибка использования .sort()](./development/2024-02-02.md)
  * [Пример улучшения функции сортировки](./development/2024-02-05.md)
  * [Автоматическая генерация TypeScript типов API, помогает или нет?](./development/2024-02-26.md)
  * [Про AbortController](./development/2025-01-17.md)
  * [Про SOLID](./development/2025-01-25.md)
  * [Data Flow и модификация данных](./development/2025-03-19.md)
  * [Бизнес логика vs функциональное мышление](./development/2025-05-06.md)
  * [Комментарии в коде — “хорошо” или “плохо”?](./development/2025-05-15.md)
  * [Деградация кодовой базы](./development/2025-06-03.md)
  * [Малоизвестные возможности Intl](./development/2025-11-03.md)
  * [Императив vs Декларатив. Точно понимаете разницу?](./development/2026-01-11.md)
  * [Простой пример сокрытия императивного кода за декларативным интерфейсом](./development/2026-01-19.md)

* Архитектура
  * [Архитектура: размазывание ответственности](./architecture/2025-01-15.md)
  * [Пара слов о Feature-Sliced Design (FSD)](./architecture/2025-01-31.md)
  * [Архитектура: функциональное проектирование](./architecture/2025-02-10.md)
  * [Архитектура: раскладываем код по папкам](./architecture/2025-02-13.md)
  * [Раскладывание кода по папкам — архитектура?](./architecture/2025-10-25.md)
  * [Что за звери такие cohesion и coupling](./architecture/2025-12-03.md)

* Typescript
  * [Typescript: Union типы на практике](./typescript/2024-01-19.md)
  * [Интересное ограничение Typescript](./typescript/2025-02-08.md)
  * [Branded Types в TypeScript](./typescript/2025-02-22.md)
  * [TypeScript + .filter(Boolean)](./typescript/2025-04-24.md)

* React
  * [Архитектурная ошибка модальных окон в React](./react/2024-01-26.md)
  * [Что не так с React](./react/2025-01-14.md)
  * [Освобождение памяти в React](./react/2025-01-27.md)
  * [Batching обновлений в React и SolidJS](./react/2025-01-28.md)
  * [Насколько React “жирный”?](./react/2025-05-21.md)
  * [Приколы setState в React, и как оно в SolidJS](./react/2025-09-25.md)
  * [useEffectEvent](./react/2025-10-24.md)
  * [React: memo и useMemo](./react/2026-02-10.md)

* SolidJS
  * [Suspense + createResource](./solid/2025-01-12.md)
  * [Рендер массивов в SolidJS](./solid/2025-01-20.md)
  * [Пример оптимизации EmojiList в SolidJS](./solid/2025-03-15.md)
  * [Children в SolidJS и порядок выполнения](./solid/2025-04-12.md)
  * [React != SolidJS на примере эффектов](./solid/2025-04-14.md)
  * [Принудительное выполнение компонента в SolidJS](./solid/2025-04-20.md)

* Webpack, Vite и другие инструменты
  * [Как ускорить Webpack сборку проекта на Typescript с 42 до 16 секунд](./tools/2024-01-02.md)
  * [Пара нюансов в вопросе Webpack vs Vite](./tools/2024-01-11.md)
  * [Экспериментальная оптимизация Webpack](./tools/2024-01-12.md)
  * [Разделение кода (на чанки) в Webpack](./tools/2024-02-06.md)
  * [Разделение кода: Webpack против Vite](./tools/2024-02-07.md)
  * [Предупреждение для тех, кто хочет перейти с Webpack на Vite](./tools/2025-01-07.md)
  * [Overrides в package.json (NPM)](./tools/2025-02-18.md)
  * [Vite vs Webpack: нюанс с React.memo()](./tools/2025-03-28.md)
  * [Vite vs Webpack: PURE комментарии](./tools/2025-05-07.md)
  * [Проверяем импорты через ESLint](./tools/2025-11-27.md);
  * [Vite vs Webpack: нюансы сборки](./tools/2026-01-29.md)
  * [Vite меняет хеши всех js чанков при любом изменении](./tools/2026-02-03.md)

* CSS
  * [Минимальный “джентльменский набор” для стилизации разметки](./css/2025-03-06.md)
  * [CSS content-visibility](./css/2025-03-09.md)
  * [Внутренние отступы кнопок в мобильном Safari](./css/2025-03-20.md)
  * [CSS свойство, которое работает только в Safari](./css/2025-09-17.md)
  * [Фиксированное соотношение сторон в CSS](./css/2025-11-13.md)

* Разное
  * [ERR_UPLOAD_FILE_CHANGED](./other/2024-08-02.md)
  * [Про технические собеседования](./other/2024-08-03.md)
  * [Одна из важнейших особенностей работы над большим проектом — цена изменений!](./other/2025-02-16.md)
  * [Минимальный фронтовый Dockerfile с поддержкой Brotli](./other/2025-02-25.md)
  * [Причина закрытия WebSocket соединения](./other/2025-04-18.md)
  * [audio/ogg; codecs=opus](./other/2025-05-22.md)
  * [Не очевидный плюс сторонних пакетов, и что насчёт самописных решений](./other/2025-09-16.md)
  * [Как проверить формат файла и почему фильтра по accept и type не достаточно](./other/2025-10-09.md)
  * [Несколько слов о TanStack Query (React Query)](./other/2025-11-08.md)
  * [Самые изменяемые файлы проекта, о чём говорят и как посмотреть](./other/2026-01-08.md)

* Demo / примеры
  * [SRP + подпись запросов](./demo/2024-07-06.md)
