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

# Vibe Coding: Opus 4.5 

<div class="w-full flex justify-center mt-10">
  <img src="/jedi-vibe.png" alt="Jedi Vibe" class="w-4/5 rounded-lg shadow" />
</div>


---

# Що по інструментам?

- **Повністю автономні**: Cognition Devin, SWE-agent, OpenHands (ex-OpenDevin), Factory.ai **Droids**

- **Agentic IDE**: Cursor**, **Windsurf, GitHub Copilot, JetBrains Junie, AWS Kiro, Cline, Zed AI

- **CLI агенти**: Claude Code, OpenAI Codex CLI, Gemini CLI, GitHub Copilot CLI, Aider

- **Хмарні frontend-aware**: v0.dev, bolt.new, **Lovable.dev, Aura.build, Replit Agent, Builder.io, Figma Dev Mode / Make


---

# v0.dev

<div class="w-full flex justify-center">
  <img src="/v0-dev.png" class="w-4/5"/>
</div>

<div class="w-full flex justify-center">
  <a href="https://v0.dev/">https://v0.dev/</a>
</div>

---

# Figma Make

<div class="w-full flex justify-center">
  <img src="/figma-make.png" alt="Figma Make" class="w-4/5 rounded-lg shadow" />
</div>

<div class="w-full flex justify-center">
  <a href="https://www.figma.com/product/make/">https://www.figma.com/product/make/</a>
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

## Наскільки дорого може це коштувати?

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

# То яка альтернатива вайб-кодингу?

<div class="w-full flex justify-center mt-12">
  <img src="/kiro.png" alt="kiro" class="w-4/5 rounded-md shadow" />
</div>


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
  <img src="/kiro-requirements.png" class="w-4/5"/>
</div>

<div class="text-center">
  Вимоги
</div>

---

# GitHub Spec Kit

<div class="w-full flex justify-center">
  <img src="/github-spec-kit.png" class="w-4/5"/>
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
layout: section
---

# Практичний кейс: лендинг джедайського курсу

---

# Красивий лендинг

<div class="w-full flex justify-center mt-14">
  <img src="/vibe-landing.png" alt="Vibe landing page" class="w-4/5 rounded-lg shadow" />
</div>

---

# Vibe Coding: Gemini 3 Pro

<div class="w-full flex justify-center mt-10">
  <img src="/vibe-jedi-gemini.png" alt="Vibe Jedi Gemini" class="w-4/5 rounded-lg shadow" />
</div>

---

# Якщо розібрати фронтенд на складові

- концепт дизайну
- дизайн система
- темплейт
- assets (зображення, іконки, шрифти)
- фреймворк
- компоненти UI
- стилі
- бізнес-логіка
- стейт-менеджмент
- інтеграція з API
- тести
- документація
- ...


---
layout: fact
---

<p class="text-2xl font-semibold text-center">
  Ланцюжок: Концепт дизайну → Frontend-aware інструмент пропотитипування → Cursor
</p>

---

# Концепт дизайну

<div class="w-full flex justify-center mt-10">
  <img src="/prototype.png" alt="Prototype design" class="w-2/5 rounded-lg shadow" />
</div>


---

# Aura.build

<div class="w-full flex justify-center mt-10">
  <img src="/jedi-aura.build.png" alt="Jedi Aura.build" class="w-3/5 rounded-lg shadow" />
</div>

---

# Процес в Aura.build

- Використовуємо prompt builder
- Просимо адаптувати існуючий шаблон
- Даємо текстовий опис концепту дизайну
- Налаштовуємо дизайн-систему
- Обираємо готові ефекти з unicorn.studio
- Додаємо власні assets (у тому числі генеровані)
- Робимо точкові ручні правки чи через AI чат
- Експортуємо в html

---

# Cursor

<div class="w-full flex justify-center mt-10">
  <img src="/jedi-cursor.png" alt="Jedi Cursor" class="w-3/5 rounded-lg shadow" />
</div>

---

# Процесс в Cursor

- npx create-next-app@latest
- задаємо (генеруємо) правила
- імпортуємо з Aura, використовуємо режим планування
- імплементимо
- використовуємо SDD (OpenSpec)


---
## layout: end
---

# Дякую!

<div class="w-full flex flex-col items-center mt-20">
  <img src="/slides-qr.png" alt="QR код для презентації" class="w-32 h-32 mb-4" />
  <a href="https://programmingmentor.github.io/2025-frontend-ai/">https://programmingmentor.github.io/2025-frontend-ai/</a>
</div>
