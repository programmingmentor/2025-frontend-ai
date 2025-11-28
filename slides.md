---
# You can also start simply with 'default'
theme: default
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://cover.sli.dev
# some information about your slides (markdown enabled)
title: Сучасний стан AI у фронтенді
info: |
  ## Сучасний стан AI у фронтенді

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

# Сучасний стан AI у фронтенді

В'ячеслав Колдовський

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

- Ph.D, доцент, 20+ років в IT
- Competence Manager, SoftServe
- Certified Google Cloud Professional Architect, Certified nVidia Generative AI with LLMs
- Керівник Центру Генеративного AI в IT STEP University
- Ютубер: [youtube.com/@programmingmentorua](https://www.youtube.com/@programmingmentorua)
- Блогер: [t.me/programmingmentor](https://t.me/programmingmentor)
- Лінкедін: [koldovsky](https://www.linkedin.com/in/koldovsky/)

---

# Як виглядав фронтенд у 1996 році?

<div class="w-full flex justify-center mt-20">
  <img src="/fe-1996.png" class="w-2/5"/>
</div>

---

# Як виглядав фронтенд у 2006 році?

<div class="w-full flex justify-center mt-20">
  <img src="/fe-2006.png" class="w-2/5"/>
</div>

---

# Як виглядав фронтенд у 2016 році?

<div class="w-full flex justify-center">
  <img src="/fe-2016.png" class="w-1/5" style="object-position: center -20px"/>
</div>

---

# Фронтенд 2026?

<div class="w-full flex justify-center">
  <img
    src="/fe-2026.png"
    class="w-3/5 object-cover"
    style="object-position: center -155px"
  />
</div>

---

# Це не жарт

<div class="w-full flex justify-center">
  <img src="/vibe-conding-fails.jpeg" alt="Funny coding fail meme" class="w-2/5" />
</div>


---

# Що таке сучасний фронтенд?

<div class="grid grid-cols-2 gap-6 mt-4">
  <div>
    <h3 class="text-green-400 mb-2">🔄 Тоді (Interface)</h3>
    <ul class="text-sm">
      <li>HTML — контент</li>
      <li>CSS — стилі</li>
      <li>JS — інтерактивність</li>
      <li>Fetch → API → Render</li>
    </ul>
  </div>
  <div>
    <h3 class="text-blue-400 mb-2">⚡ Зараз (System)</h3>
    <ul class="text-sm">
      <li>Server/Client гібридний стейт</li>
      <li>Data fetching, caching, invalidation</li>
      <li>SSR, streaming, Edge rendering</li>
      <li>Auth flows, CSP, security</li>
      <li>DevOps, CI/CD, моніторинг</li>
    </ul>
  </div>
</div>

<div class="mt-6 p-3 bg-yellow-500/10 border border-yellow-500/30 rounded-lg">
  <p class="text-center text-yellow-300 font-semibold">
    Frontend is not dead. The old shape of it is. 🚀
  </p>
</div>

---

# FrontEnd --> Full Experience Engineer

<div class="mt-4">

**Сучасний фронтенд-розробник має розуміти:**

</div>

<div class="grid grid-cols-2 gap-4 mt-4">
  <div class="p-3 bg-gradient-to-br from-purple-500/20 to-blue-500/20 rounded-lg">
    <h4 class="text-purple-300 font-bold">🎨 UI/UX</h4>
    <p class="text-sm">Компоненти, accessibility, анімації</p>
  </div>
  <div class="p-3 bg-gradient-to-br from-blue-500/20 to-cyan-500/20 rounded-lg">
    <h4 class="text-blue-300 font-bold">📊 Data Layer</h4>
    <p class="text-sm">React Query, SWR, optimistic updates</p>
  </div>
  <div class="p-3 bg-gradient-to-br from-cyan-500/20 to-green-500/20 rounded-lg">
    <h4 class="text-cyan-300 font-bold">🖥️ Server Logic</h4>
    <p class="text-sm">RSC, Server Actions, Edge Functions</p>
  </div>
  <div class="p-3 bg-gradient-to-br from-green-500/20 to-yellow-500/20 rounded-lg">
    <h4 class="text-green-300 font-bold">🚀 Deployment</h4>
    <p class="text-sm">Serverless, Edge, CI/CD, monitoring</p>
  </div>
</div>

<div class="mt-6 text-center">
  <p class="text-lg">Next.js • Remix • SvelteKit • Astro</p>
  <p class="text-sm text-gray-400 mt-2">Межі між Frontend і Backend розмиваються</p>
</div>


---

# А цей AI десь разом з нами в цьому приміщенні?

<div class="w-full flex justify-center mt-12">
  <img src="/ai-in-a-room.jpg" alt="AI in the room" class="w-3/5 rounded-md shadow" />
</div>


---

# Deep Blue

<div class="w-full flex justify-center mt-12">
  <img src="/garry-kasparov-deep-blue-ibm-computer.jpg" alt="Garry Kasparov vs Deep Blue" class="w-3/5 rounded-md shadow" />
</div>

---

# Yann LeCun

<div class="w-full flex justify-center mt-12">
  <img src="/yannlecunaboutllm.png" alt="Yann LeCun about LLMs" class="w-3/5 rounded-md shadow" />
</div>

---

# Красивий лендинг

<div class="w-full flex justify-center mt-14">
  <img src="/vibe-landing.png" alt="Vibe landing page" class="w-4/5 rounded-lg shadow" />
</div>

---

# Джедайський курс 

<div class="w-full flex justify-center mt-10">
  <img src="/jedi-vibe.png" alt="Jedi Vibe" class="w-4/5 rounded-lg shadow" />
</div>



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

# Cursor

<div class="w-full flex justify-center">
  <img src="/cursor.png" class="w-4/5"/>
</div>

<div class="w-full flex justify-center">
  <a href="https://www.cursor.com/">https://www.cursor.com/</a>
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
<v-click>
<br>
Промпт: ось тобі детальна user story для аплікації для ведення витрат, в ній є всі деталі, які потрібні для розробки: acceptance criteria, business rules, constraints, etc.
</v-click>

<v-click>
<br>
Math.pow(.99, 100) = 0.3660
</v-click>

---

# Що найважливіше навчитися робити?

<v-click>
- Детально пояснювати що саме нам потрібно.
</v-click>
<v-click>
<br>
- На кожному кроці
</v-click>

---

# Spec Driven Development 2004 року

<div class="w-full flex justify-between items-center mt-2">
  <div class="w-3/5 pr-6">
    <ul class="list-disc pl-5">
      <li>Оригінально термін "Specification-Driven Development" було введено у 2004 році у статті <a href="https://www.eecs.yorku.ca/~jonathan/publications/2004/xp2004.pdf">"Agile Specification-Driven Development"</a>.</li>
      <li>Специфікація — це будь-який виконуваний конструкт, який перетворює вимоги на компільований код, причому цей конструкт є основним рушієм розробки.</li>
      <li>Специфікаціями можуть бути дві взаємодоповнюючі речі: юніт-тести (Test Driven Development, TDD) - специфікації спільної поведінки; та контракти (Design-by-Contract, DbC) виражені у вигляді передумов та післяумов.</li>
    </ul>
  </div>
  <div class="w-2/5 flex justify-end">
    <img src="/sdd-2004.png" class="w-full"/>
  </div>
</div>

---

# Spec Driven Development 2025 року

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

# GitHub Spec Kit

<div class="w-full flex justify-center">
  <img src="/github-spec-kit.png" class="w-4/5"/>
</div>

---

## Як стартувати зі Spec Kit

```bash
# 1) Інсталюємо CLI, ініціалізуємо проект і перевіряємо його стан
uv tool install specify-cli --from git+https://github.com/github/spec-kit.git

specify init <PROJECT_NAME>
specify check

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

| Фаза                  | Фокус                 | Що робимо                                    |
| --------------------- | --------------------- | -------------------------------------------- |
| Greenfield            | Створення з нуля      | Вимоги → специфікація → план → імплементація |
| Brownfield            | Робота з існуючим     | Додавання фіч, рефакторинг, адаптація        |
| Креативні дослідження | Паралельні реалізації | Порівняння стеків, UX‑підходів               |

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

# А що у нас з brownfield?

<div class="w-full flex justify-center">
  <img src="/meme-old-new.jpg" class="w-2/5"/>
</div>

---

# OpenSpec

<div class="w-full flex justify-center">
  <img src="/openspec.png" class="w-3/6"/>
</div>

<div class="w-full flex justify-center">
  <a href="https://github.com/Fission-AI/OpenSpec">https://github.com/Fission-AI/OpenSpec</a>
</div>

---

# OpenSpec lifecycle

<div class="w-full flex justify-center bg-white">
  <img src="/openspec-lifecycle.png" class="w-3/5"/>
</div>

---

# Порівняння OpenSpec з GitHub Spec Kit / Kiro

<div class="comparison-table">

| Критерій                | OpenSpec (1→n)                                                                                                                        | Spec Kit / Kiro (0→1)                                                                           |
| ----------------------- | ------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------- |
| **Ключовий Фокус**      | Brownfield-first (модифікація наявної поведінки: 1→n).                                                                                | Greenfield-first (створення нових функцій з нуля: 0→1).                                         |
| **Архітектура Сховища** | Двохпапочна модель: openspec/specs/ (поточна істина) окремо від openspec/changes/ (пропоновані оновлення).                            | Використання однієї папки для спеки або гілок (branches) для кожної специфікації.               |
| **Управління Змінами**  | Явне відстеження змін: Усі пропозиції, завдання та дельти спеки групуються в одній папці змін (openspec/changes/feature-name/).       | Зміни (оновлення) можуть бути розпорошені між кількома файлами спеки, що ускладнює відстеження. |
| **Робочий Процес**      | Зосереджений на життєвому циклі змін (Draft Proposal → Implement → Archive), де архівування явно зливає зміни назад у джерело істини. | Зосереджений на послідовній генерації (Specify → Plan → Tasks).                                 |

</div>

<style>
.comparison-table {
  font-size: 0.85em;
}

.comparison-table table {
  table-layout: fixed;
  width: 100%;
}

.comparison-table table th:nth-child(1),
.comparison-table table td:nth-child(1) {
  width: 25%;
}

.comparison-table table th:nth-child(2),
.comparison-table table td:nth-child(2),
.comparison-table table th:nth-child(3),
.comparison-table table td:nth-child(3) {
  width: 37.5%;
}
</style>

---

# Рівні імплементації SDD

| Рівень SDD                            | Опис                                                                                                                               |
| ------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- |
| **Spec-first** (Спершу спека)         | Продумана спека пишеться першою, а потім використовується в робочому процесі за допомогою ШІ.                                      |
| **Spec-anchored** (Закріплена спека)  | Спека зберігається навіть після завершення завдання та використовується для еволюції та підтримки функції протягом тривалого часу. |
| **Spec-as-source** (Спека як джерело) | Редагується лише спека; людина ніколи не торкається коду, який повністю генерується з неї.                                         |

https://martinfowler.com/articles/exploring-gen-ai/sdd-3-tools.html

---

# Specs vs rules

<div class="w-full flex justify-center">
  <img src="/specs-vs-rules.png" class="w-4/5"/>
</div>

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

<div class="w-full flex flex-col items-center mt-20">
  <img src="/slides-qr.png" alt="QR код для презентації" class="w-32 h-32 mb-4" />
  <a href="https://programmingmentor.github.io/2025-frontend-ai/">https://programmingmentor.github.io/2025-frontend-ai/</a>
</div>
