<!-- BEGIN:nextjs-agent-rules -->

# This is NOT the Next.js you know

This version has breaking changes — APIs, conventions, and file structure may all differ from your training data. Read the relevant guide in `node_modules/next/dist/docs/` (resolved from this file's directory; in monorepos the `next` package may not be visible from the repo root) before writing any code. Heed deprecation notices.

This block is written and re-added by `next dev` — verify at `node_modules/next/dist/server/lib/generate-agent-files.js`. Removing it from a diff only re-creates the uncommitted change; committing it with your work keeps the tree clean.

<!-- END:nextjs-agent-rules -->

# Тренажёр для собеседований

Стек: Next.js (App Router), TypeScript strict,
Vercel AI SDK, Tailwind, shadcn/ui, Vitest, Playwright, Postgres.

## Как со мной работать
- Я учусь. Перед кодом для новой задачи покажи план и дождись моего «ок».
- Если есть несколько подходов, перечисли их с компромиссами
  и не выбирай за меня.
- Не добавляй зависимости и не трогай файлы вне задачи без спроса.
- После изменений объясни 3–5 ключевых решений и что мне стоит
  изучить глубже.
- Файлы в lib/srs/ и lib/eval/prompt.ts пишу я сам: только ревью
  и наводящие вопросы, без правок.
- Без any. Не уверен в API библиотеки — скажи об этом, не угадывай.

## Принятые решения
См. docs/adr/. Не предлагай их пересмотр без веской причины.