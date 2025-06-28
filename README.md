# Rafabduloff // rozeraf

<div align="center">

<svg width="800" height="200" viewBox="0 0 800 200" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="gradient1" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#667eea;stop-opacity:1">
        <animate attributeName="stop-color" values="#667eea;#764ba2;#f093fb;#667eea" dur="4s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" style="stop-color:#764ba2;stop-opacity:1">
        <animate attributeName="stop-color" values="#764ba2;#f093fb;#4facfe;#764ba2" dur="4s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>
    <linearGradient id="gradient2" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#4facfe;stop-opacity:1">
        <animate attributeName="stop-color" values="#4facfe;#00f2fe;#43e97b;#4facfe" dur="3s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" style="stop-color:#00f2fe;stop-opacity:1">
        <animate attributeName="stop-color" values="#00f2fe;#43e97b;#38f9d7;#00f2fe" dur="3s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>
  </defs>
  
  <!-- Background particles -->
  <circle cx="100" cy="50" r="2" fill="#667eea" opacity="0.6">
    <animate attributeName="cy" values="50;150;50" dur="3s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.6;0.2;0.6" dur="3s" repeatCount="indefinite"/>
  </circle>
  <circle cx="700" cy="150" r="1.5" fill="#764ba2" opacity="0.5">
    <animate attributeName="cy" values="150;50;150" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.5;0.8;0.5" dur="4s" repeatCount="indefinite"/>
  </circle>
  <circle cx="250" cy="30" r="1" fill="#4facfe" opacity="0.7">
    <animate attributeName="cx" values="250;550;250" dur="5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="550" cy="170" r="1.5" fill="#00f2fe" opacity="0.6">
    <animate attributeName="cx" values="550;250;550" dur="6s" repeatCount="indefinite"/>
  </circle>
  
  <!-- Main text -->
  <text x="400" y="80" font-family="'Segoe UI', Tahoma, Geneva, Verdana, sans-serif" font-size="36" font-weight="bold" text-anchor="middle" fill="url(#gradient1)">
    Full-Stack Developer
    <animate attributeName="opacity" values="0.8;1;0.8" dur="2s" repeatCount="indefinite"/>
  </text>
  
  <!-- Subtitle -->
  <text x="400" y="110" font-family="'Segoe UI', Tahoma, Geneva, Verdana, sans-serif" font-size="18" text-anchor="middle" fill="url(#gradient2)">
    JavaScript • TypeScript • C++ • Rust
  </text>
  
  <!-- Decorative lines -->
  <line x1="50" y1="130" x2="350" y2="130" stroke="url(#gradient1)" stroke-width="2" opacity="0.7">
    <animate attributeName="x2" values="350;380;350" dur="3s" repeatCount="indefinite"/>
  </line>
  <line x1="450" y1="130" x2="750" y2="130" stroke="url(#gradient2)" stroke-width="2" opacity="0.7">
    <animate attributeName="x1" values="450;420;450" dur="3s" repeatCount="indefinite"/>
  </line>
  
  <!-- Code brackets -->
  <text x="150" y="160" font-family="'Fira Code', Monaco, 'Cascadia Code', monospace" font-size="24" fill="#667eea" opacity="0.8">
    { }
    <animate attributeName="opacity" values="0.8;0.4;0.8" dur="2.5s" repeatCount="indefinite"/>
  </text>
  <text x="650" y="160" font-family="'Fira Code', Monaco, 'Cascadia Code', monospace" font-size="24" fill="#764ba2" opacity="0.8">
    &lt;/&gt;
    <animate attributeName="opacity" values="0.4;0.8;0.4" dur="2.5s" repeatCount="indefinite"/>
  </text>
</svg>

[![Profile Views](https://komarev.com/ghpvc/?username=rafabduloff&style=flat-square&color=blue)](https://github.com/rafabduloff)

<div id="badges" align="center" style="margin: 20px 0;">
  <a href="https://t.me/rozeraf" target="_blank">
    <img src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram Badge"/>
  </a>
  <a href="https://github.com/rafabduloff" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Badge"/>
  </a>
  <a href="mailto:rafabduloff@gmail.com" target="_blank">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email Badge"/>
  </a>
</div>

</div>

---

## 👨‍💻 О себе

Фуллстек разработчик начального уровня с фокусом на создание качественных веб-приложений, CLI-утилит и десктопных интерфейсов. Работаю преимущественно с **JavaScript/TypeScript** и **C++**, активно изучаю **Rust**. 

Придерживаюсь принципов чистого кода, уделяю особое внимание качеству пользовательского интерфейса и автоматизации рутинных задач. Участвую в коммерческих и personal проектах, где совмещаю frontend и backend разработку.

---

## 🚀 Проекты

<table>
<tr>
<td width="50%">

### 🎵 [music-player](https://github.com/rafabduloff/music-player)
**Десктопный музыкальный плеер**
- **Stack:** Tauri + React + Tailwind CSS
- **Backend:** Rust (в процессе стабилизации)
- **Features:** 
  - Современный интерфейс с кастомными темами
  - Конфигурирование через TOML
  - Планируется интеграция с API (Yandex Music, Spotify)

</td>
<td width="50%">

### 🤖 [deepcode](https://github.com/rafabduloff/deepcode)
**CLI-инструмент с LLM интеграцией**
- **Stack:** Python + OpenRouter API
- **Features:**
  - Пошаговая генерация и дебаг кода
  - Unified-diff поддержка
  - Контроль опасных команд
  - Автоматическое управление зависимостями

</td>
</tr>
<tr>
<td width="50%">

### 🔐 [cpp-pswd-gen](https://github.com/rafabduloff/cpp-pswd-gen)
**Генератор паролей на C++**
- **Stack:** C++ (современный стандарт)
- **Features:**
  - Множественные режимы генерации
  - Оценка сложности паролей
  - Генерация с seed для воспроизводимости

</td>
<td width="50%">

### ⚙️ [qol](https://github.com/rafabduloff/qol)
**Скрипты для настройки Windows**
- **Stack:** PowerShell
- **Features:**
  - Автоматизированная очистка системы
  - Деактивация телеметрии
  - Пакетная установка ПО

</td>
</tr>
</table>

---

## 🛠️ Технологический стек

### 💪 Основные языки
<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

</div>

### 🌱 Изучаю
<div align="center">

![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)

</div>

### 🔧 Фреймворки и инструменты
<div align="center">

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![Tauri](https://img.shields.io/badge/Tauri-24C8D8?style=for-the-badge&logo=tauri&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)

![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)

</div>

### 🖥️ Среда разработки
<div align="center">

![Arch Linux](https://img.shields.io/badge/Arch_Linux-1793D1?style=for-the-badge&logo=arch-linux&logoColor=white)
![Windows 10](https://img.shields.io/badge/Windows_10-0078D6?style=for-the-badge&logo=windows&logoColor=white)
![GRUB](https://img.shields.io/badge/GRUB-8E8E8E?style=for-the-badge&logo=gnu&logoColor=white)

![Zsh](https://img.shields.io/badge/Zsh-89e051?style=for-the-badge&logo=gnu-bash&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)

![CLion](https://img.shields.io/badge/CLion-000000?style=for-the-badge&logo=clion&logoColor=white)
![PyCharm](https://img.shields.io/badge/PyCharm-000000?style=for-the-badge&logo=pycharm&logoColor=white)

</div>

---

## 💼 Ключевые навыки

- **Full-Stack разработка**: создание приложений с нуля (UI + backend логика)
- **API интеграция**: работа с REST API, HTTP-запросами и JSON
- **CLI разработка**: создание консольных утилит и скриптов автоматизации
- **Desktop приложения**: разработка на Tauri и нативных технологиях
- **Database**: проектирование схем БД, оптимизация запросов
- **DevOps**: настройка CI/CD, контейнеризация, деплой приложений
- **Code Quality**: рефакторинг, тестирование, code review

---

## 📊 GitHub статистика

<div align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=rafabduloff&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=rafabduloff&layout=compact&theme=tokyonight&hide_border=true"/>
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=rafabduloff&theme=tokyonight&hide_border=true" alt="GitHub Streak"/>
</div>

---

## 🎯 Текущие цели и интересы

- **🔄 DevOps & Automation**: улучшение dev-опыта и автоматизация рутинных процессов
- **🛠️ Tooling**: создание инструментов для повышения продуктивности разработчиков
- **📈 Architecture**: переход от "работающего кода" к масштабируемым решениям
- **⚡ Systems Programming**: углубленное изучение Rust и системного программирования
- **🌐 Web3 & Blockchain**: исследование децентрализованных технологий
- **🤖 AI/ML Integration**: внедрение ИИ в повседневные dev-задачи

---

## ☕ Powered by Coffee

<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=F7931E&center=true&vCenter=true&width=435&lines=console.log('Coding+with+%E2%98%95');while(coffee)+%7B+code()+%7D;System.out.println(%22Java+%2B+Coffee%22);" alt="Typing SVG" />
</div>

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=100&section=footer&animation=fadeIn"/>
</div>
