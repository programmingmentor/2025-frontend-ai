---
# You can also start simply with 'default'
theme: default
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://cover.sli.dev
# some information about your slides (markdown enabled)
title: Найкращі практики розробки з AI агентами
info: |
  ## Подія SoftServe Academy: виступ + багато нетворкінгу

# apply unocss classes to the current slide
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
# take snapshot for each slide in the overview
overviewSnapshots: true
---

# Найкращі практики розробки з AI агентами.

В'ячеслав Колдовський, SoftServe Academy

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="m-6 flex gap-2 fixed bottom-0 left-0">
  <a href="https://www.youtube.com/c/programmingmentorua">
    <div class="h-8 w-8">
      <img src="/pm-logo.jpg" class="h-full w-full rounded-full"/>
    </div>
  </a>
</div>

<style>
  a {
    text-decoration: none;
    border: 2.4px solid transparent;
  }
  a:hover {
    border-color: var(--slidev-theme-primary);
  }
</style>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
layout: image-left
image: /vyacheslav-koldovskyy.png
---

# В'ячеслав Колдовський

- Ph.D, доцент
- 20+ років в IT
- SoftServe Academy Competence Manager
- Certified Google Cloud Professional Architect, Certified nVidia Generative AI with LLMs
- Керівник Центру Генеративного AI в IT STEP University
- Ентузіаст Практичного AI
- Ютубер: [youtube.com/@programmingmentorua](https://www.youtube.com/@programmingmentorua)
- Блогер: [t.me/programmingmentor](https://t.me/programmingmentor)
- Лінкедін: [koldovsky](https://www.linkedin.com/in/koldovsky/)

---

# Що ви скажете про вайб-кодинг?

---

# Чому ми говоримо про агенти в розробці?

- AI в розробці швидко прогресує і основним інструментом у 2025-му році стали AI-агенти.
- Їх стало (за)багато.
- З ними не все так просто:
  - Не завжди роблять саме те, що нам потрібно.
  - Обходяться недешево.
  - Досягнення цілей займає багато часу.
  - Потребують нагляду та керування.

---

# Як ми взагалі дійшли до агентів?

---

# Найпростіше використання: промпт + LLM = код

<div class="w-full flex justify-center">
  <img src="/how-works-prompt-llm-code.png" class="w-4/5"/>
</div>

---

# Промт - це значно більше, ніж просто команда для LLM

<div class="w-full flex justify-center">
  <img src="/how-works-prompt-expanded-llm-code.png" class="w-4/5"/>
</div>

---

# Агентний цикл

<div class="w-full flex justify-center">
  <img src="/how-works-simple-agent.png" class="w-4/5"/>
</div>

---

# Агент з інструментами

<div class="w-full flex justify-center">
  <img src="/how-works-modern-agent.png" class="w-4/5"/>
</div>

---

# Ключові особливості агентів

- Агент має ціль, яку він прагне досягти.
- Агент отримує контекст для виконання задач.
- Агент має пам'ять для збереження стану між кроками.
- Агент має інструменти для виконання задач.
- Агент може планувати послідовність дій.
- Агент здатний до саморефлексії та корекції помилок.

---

# Які бувають агенти для розробки?

- **Повністю автономні**: Cognition **Devin**, SWE-agent (SWE-bench), OpenDevin, AutoGPT (Dev/Code агенти)

- **Агенти в IDE (Human in the loop)**: GitHub Copilot Chat, Cursor IDE, Codeium Chat, JetBrains AI Assistant / Junie, Sourcegraph Cody, AWS Q Developer, Roo Code / Cline, Kiro

- **Гібридні**: GitHub Copilot Workspace, Copilot Autofix, Replit Agents, OpenDevin, SWE-agent

- **CLI агенти (Terminal)**: Claude Code, Codex CLI, GitHub Copilot in the CLI, Cursor CLI, Aider, Gemini CLI

- **Хмарні агенти**: Vercel V0, Replit Agent, bolt.new

---

# bolt.new

<div class="w-full flex justify-center">
  <img src="/bolt-new.png" class="w-1/2"/>
</div>

<div class="w-full flex justify-center">
  <a href="https://bolt.new/">https://bolt.new/</a>
</div>

---

# v0.dev

<div class="w-full flex justify-center">
  <img src="/v0-dev.png" class="w-4/5"/>
</div>

<div class="w-full flex justify-center">
  <a href="https://v0.dev/">https://v0.dev/</a>
</div>

---

# repl.it agent

<div class="w-full flex justify-center">
  <img src="/replit.png" class="w-4/5"/>
</div>

<div class="w-full flex justify-center">
  <a href="https://repl.it/">https://repl.it/</a>
</div>

---

# Github Copilot

<div class="w-full flex justify-center">
  <img src="/github-copilot.png" class="w-4/5"/>
</div>

<div class="w-full flex justify-center">
  <a href="https://copilot.github.com/">https://copilot.github.com/</a>
</div>

---

# Cursor

<div class="w-full flex justify-center">
  <img src="/cursor.png" class="w-4/5"/>
</div>

<div class="w-full flex justify-center">
  <a href="https://www.cursor.com/">https://www.cursor.com/</a>
</div>

---

# Windsurf

<div class="w-full flex justify-center">
  <img src="/windsurf.png" class="w-4/5"/>
</div>

<div class="w-full flex justify-center">
  <a href="https://codeium.com/windsurf">https://codeium.com/windsurf</a>
</div>

---

# Cline

<div class="w-full flex justify-center">
  <img src="/cline.png" class="w-4/5"/>
</div>

<div class="w-full flex justify-center">
  <a href="https://cline.bot/">https://cline.bot/</a>
</div>

---

# Codex

<div class="w-full flex justify-center">
  <img src="/codex.png" class="w-4/5"/>
</div>

<div class="w-full flex justify-center">
  <a href="https://openai.com/codex/">https://openai.com/codex/</a>
</div>

---
layout: center
---

## Наскільки дорого може коштувати користуватися агентами?

<div class="flex justify-center">
  <Tweet class="w-1/2" id="1964819755644412087" />
</div>

---

# Чому агенти не завжди роблять те, що нам потрібно?

<v-click>
Промпт: згенеруй аплікацію для ведення витрат.
</v-click>

---

# Що найважливіше навчитися робити?

<v-click>
Детально пояснювати те, що саме нам потрібно.
</v-click>

---

# Spec Driven Development

Основні принципи:

- **Specifications as the Lingua Franca**  
  Специфікації — головний артефакт, код лише їх вираз

- **Executable Specifications**  
  Специфікації достатньо точні, щоб генерувати робочі системи

- **Continuous Refinement**  
  Постійна перевірка на неоднозначності, суперечності та прогалини

- **Research-Driven Context**  
  Автоматичний збір контексту: сумісність, продуктивність, безпека

- **Bidirectional Feedback**  
  Метрики й інциденти з продакшну оновлюють специфікації

- **Branching for Exploration**  
  Можливість створювати кілька імплементацій з однієї специфікації

---

# Як це працює?

- Write the Spec – Визначити вимоги, критерії приймання та цілі дизайну.
- Implement & Test – Створити код відповідно до специфікації; вивести тести з критеріїв приймання.
- Iterate – Удосконалювати специфікацію та імплементацію разом.
- Maintain & Document – Тримати специфікацію актуальною; вона залишається довідковою точкою проєкту.

---

# Kiro

<div class="w-full flex justify-center">
  <img src="/kiro.png" class="w-4/5"/>
</div>

---

# Kiro

<div class="w-full flex justify-center">
  <img src="/kiro-requirements.png" class="w-4/5"/>
</div>

<div class="text-center">
  Вимоги
</div>

---

# Kiro

<div class="w-full flex justify-center">
  <img src="/kiro-design.png" class="w-4/5"/>
</div>

<div class="text-center">
  Дизайн
</div>

---

# Kiro

<div class="w-full flex justify-center">
  <img src="/kiro-implementation.png" class="w-4/5"/>
</div>

<div class="text-center">
  Імплементація
</div>

---

# Kiro

<div class="w-full flex justify-center">
  <img src="/kiro-implementing-task.png" class="w-4/5"/>
</div>

<div class="text-center">
  Імплементація
</div>


---

# Анонс у блозі GitHub

<div class="w-full flex justify-center">
  <img src="/github-blog.png" class="w-4/5"/>
</div>

---

# GitHub Spec Kit

<div class="w-full flex justify-center">
  <img src="/github-spec-kit.png" class="w-4/5"/>
</div>

---

## Як стартувати зі Spec Kit

```bash
# 1) Ініціалізація CLI
uvx --from git+https://github.com/github/spec-kit.git specify init <PROJECT_NAME>

# 2) Формулюємо специфікацію
/specify ... (що будуємо і чому)

# 3) Плануємо технічну імплементацію
/plan ... (стек, архітектура)

# 4) Розбиваємо на кроки та імплементуємо
/tasks ... → просимо агента виконати
```

---

# GitHub Spec Kit - файли і команди, результат /specify

<div class="w-full flex justify-center">
  <img src="/github-spec-kit-init.png" class="w-4/5"/>
</div>

---

# GitHub Spec Kit - research

<div class="w-full flex justify-center">
  <img src="/github-spec-kit-research.png" class="w-4/5"/>
</div>

---

## SDD і фази розробки


| Фаза                     | Фокус                   | Що робимо                                    |
| ------------------------ | ----------------------- | -------------------------------------------- |
| Greenfield               | Створення з нуля        | Вимоги → специфікація → план → імплементація |
| Brownfield               | Робота з існуючим       | Додавання фіч, рефакторинг, адаптація        |
| Креативні дослідження    | Паралельні реалізації   | Порівняння стеків, UX‑підходів               |

---

## Експерименти з SDD

- **Обираємо технології** – генерація проєктів у різних стеках
- **Обмеження бізнесу** – дизайн‑системи, комплаєнс, платформи
- **Гіпотези про UX/UI** – різні когорти та стилі UX/UI
- **Будь-які інші експерименти** – паралельні варіанти, апгрейди й модернізації

---

## Приклад промптів

**/specify**

> Створити застосунок для організації фотоальбомів з переглядом плиткою і перетягуванням альбомів.

**/plan**

> Мінімалістичний стек: Vite + HTML/CSS/JS; зберігання локально в SQLite; без завантаження фото в зовнішні сервіси.

---

## Структура папок (приклад)

```
project/
  memory/
  scripts/
  specs/
    001-<feature>/
    spec.md
  templates/
    CLAUDE-template.md
    plan-template.md
    spec-template.md
    tasks-template.md
```

---

# AGENTS.md

<div class="w-full flex justify-center">
  <img src="/agents-md.png" class="w-3/4"/>
</div>

<div class="w-full flex justify-center">
  <a href="https://agents.md">agents.md</a>
</div>

---
layout: section
---

# Лайфхаки

---
layout: fact
---

Ланцюжок: Repomix -> ChatGPT (Gemini) -> Cursor

---

# Repomix

<div class="w-full flex justify-center">
  <img src="/repomix.png" class="w-4/5"/>
</div>

---

# Керування агентами: основні принципи

- Ясна мета, обмеження, критерії приймання
- Малі кроки, короткі контексти, відкат та відновлення
- Права доступу й інструменти: allowlist, dry-run, approvals
- План/Дія: режими Plan/Act, контроль бюджету і таймаутів

---

# Контекст і знання

- За потреби явно керуємо контекстом, додаємо необхідне
- Документація - додаємо в правила, використовуємо @docs, MCP context7
- Під час використання MCP не перегружаємо інструментами
- Забагато контексту - не завжди добре

---

# Безпека і контроль

- Sandbox, white/black list для команд, захист видалення файлів
- Secret management, .cursoringore
- Перевірка diff перед виконанням
- Обережне використання MCP

---

# Щоб не ламався код

- TDD з агентом: тести → код → фікси
- Лінт/типи/тести на кожний крок, швидкий зворотний зв'язок
- Local History/гілки для безпечних експериментів
- Короткі кроки

---

# Рейтинг LLM

<div class="w-full flex justify-center">
  <img src="/chatbot-arena-language.png" class="w-4/5"/>
</div>

<div class="w-full flex justify-center">
  <a href="https://lmarena.ai/">https://lmarena.ai/</a>
</div>

---

# LOC to LLM tokens

## React:

- **React jsx (100 lines):** 700 tokens
- **React jsx (200 lines):** 1,500 tokens

## SQL:

- **SQL script (100 lines):** 1,150 tokens
- **SQL script (200 lines):** 2,500 tokens

## Python:

- **Python source code file (100 lines):** 1,000 tokens
- **Python source code file (200 lines):** 1,700 tokens

Source https://prompt.16x.engineer/blog/chatgpt-context-window-token-limit

---

# MCP - Model Context Protocol

<div class="w-full flex justify-center">
  <img src="/mcp.png" class="w-4/5"/>
</div>

<div class="w-full flex justify-center">
  <a href="https://modelcontextprotocol.io/">https://modelcontextprotocol.io/</a>
</div>

---

# MCP.so

<div class="w-full flex justify-center">
  <img src="/mcp-list.png" class="w-1/2"/>
</div>

<div class="w-full flex justify-center">
  <a href="https://mcp.so/">https://mcp.so/</a>
</div>

---

<div class="w-full h-full flex justify-center items-center">
  <h1 class="text-center">Tips, Tricks and Resources</h1>
</div>

---

# Cursor Rules

<div class="w-full flex justify-center">
  <img src="/cursor-rules.png" class="w-2/3"/>
</div>

<div class="w-full flex justify-center">
  <a href="https://docs.cursor.com/context/rules-for-ai">https://docs.cursor.com/context/rules-for-ai</a>
</div>

---

# Cursor.directory

<div class="w-full flex justify-center">
  <img src="/cursor-directory.png" class="w-4/5"/>
</div>

<div class="w-full flex justify-center">
  <a href="https://cursor.directory/">https://cursor.directory/</a>
</div>

---

# llms.txt

<div class="w-full flex justify-center">
  <img src="/llms-txt.png" class="w-1/2"/>
</div>

<div class="w-full flex justify-center">
  <a href="https://llmstxt.org/">https://llmstxt.org/</a>
</div>



---
## layout: end
---

# Дякую!

<div class="flex justify-center w-full h-30 items-center">
  <img src="/slides-qr.png" class="w-50 h-50"/>
</div>

<div class="w-full flex justify-center mt-20">
  <a href="https://programmingmentor.github.io/2025-slidev-coding-agents/">https://programmingmentor.github.io/2025-slidev-coding-agents/</a>
</div>
