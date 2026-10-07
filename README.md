## Hi there 👋
<div align="center">

# Инженер-автоматизатор · Automation Engineer

**RU:** Автоматизирую рутину вокруг маркировки «Честный знак» и Национального каталога:
DataMatrix-коды, генерация импорт-файлов, парсинг, API-интеграции, Excel-отчёты.
Активно использую ИИ-агентов (Claude Code) как полноценный инструмент разработки.

**EN:** I build automation around product labeling («Chestny ZNAK» / GS1 DataMatrix),
catalog management, and parsing pipelines — with AI agents (Claude Code) as a core part of my workflow.

</div>

---

## 🛠 Технологии и инструменты · Tech stack

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/-React_18-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/-Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Pandas](https://img.shields.io/badge/-pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Playwright](https://img.shields.io/badge/-Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![Postman](https://img.shields.io/badge/-Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![Excel](https://img.shields.io/badge/-Excel_/_VBA-217346?style=flat-square&logo=microsoft-excel&logoColor=white)
![Claude](https://img.shields.io/badge/-Claude_Code-191919?style=flat-square&logo=anthropic&logoColor=white)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)
![Windows](https://img.shields.io/badge/-Windows-0078D6?style=flat-square&logo=windows&logoColor=white)

---

## 🚀 Проекты · Projects

### [dm-converter](https://github.com/ad620an/dm-converter) — генератор и декодер DataMatrix
Веб-сервис для работы с кодами маркировки «Честный знак»:
- **Генерация** GS1 DataMatrix ECC 200 — до 1000 кодов за раз из TXT/CSV/XLSX
- **Печать** PDF-наклеек точных физических размеров
- **Декодирование** DataMatrix из PDF/JPG/PNG (адаптивный рендер 200→400 DPI)
- Полностью локальная обработка данных — ничего не уходит наружу

`Python` `FastAPI` `React 18` `TypeScript` `pylibdmtx` `PyMuPDF` `pytest`

### [chz-nk](https://github.com/ad620an/chz-nk) — генератор импорт-файлов для Национального каталога
Автоматическое создание файлов загрузки товарных позиций (электронные компоненты:
светодиоды, реле, оптопары, разъёмы) по кодам ТНВЭД + .docx-отчёты о загрузке.
Включает предметную логику: например, маппинг артикулов светодиодов на ОКПД2 по длине волны из datasheet.

`Python` `openpyxl` `python-docx` `Excel`

### [nk_api](https://github.com/ad620an/nk_api) — клиент API Национального каталога
Скрипты для работы в контуре «Честного знака»: генерация черновых GTIN,
создание карточек товаров через feed-загрузку, контроль статусов фида.
Развёрнутый справочник маппингов ТНВЭД → cat_id → ОКПД2 под пресеты каталога.

`Python` `requests` `loguru` `API «Честного знака»`

### [nk](https://github.com/ad620an/nk) — парсер Национального каталога
Парсинг карточек товаров (национальный-каталог.рф) по брендам ABB, Schneider Electric, CHINT:
дисковый кэш HTML-страниц, ретраи с экспоненциальными паузами,
сборка оформленных сводных xlsx с воспроизведением структуры каталога.

`Python` `requests` `BeautifulSoup` `openpyxl`

### [sub-agents](https://github.com/ad620an/sub-agents) — специализированные ИИ-агенты
Песочница для проектирования субагентов Claude Code с собственными инструментами и
инструкциями: агент `datamatrix-decoder` декодирует DataMatrix из изображений и PDF,
учитывая граничные случаи (DLL на Windows, отсутствие Poppler, fallback-конвертации).

`Claude Code` `Custom Agents` `pylibdmtx` `OpenCV`

### [landing](https://github.com/ad620an/landing) — лендинг Winsen
Одностраничный сайт поставщика газовых и пироэлектрических датчиков
(электрохимические, каталитические, полупроводниковые, NDIR).
Чистый HTML/CSS без фреймворков, SEO-метатеги, задел под англоязычную версию.

`HTML` `CSS` `SEO`

### [seo_plt](https://github.com/ad620an/seo_plt) — SEO-аудит platan.ru
Полный SEO-аудит интернет-магазина электронных компонентов: мета-теги, JSON-LD,
canonical, скорость, мобильность — 11 страниц через headless Chromium.
С честным разделом о границах методологии (что требует Ahrefs/Serpstat).

`Claude Code` `MCP Playwright` `Headless Chromium`

---

## 🎯 Чем занимаюсь · What I do

- **Автоматизация «Честного знака»** — от генерации GTIN и DataMatrix до загрузки карточек в каталог
- **Парсинг и ETL** — сбор данных с сайтов и API, чистка, сводная отчётность в Excel
- **ИИ-агенты как инструмент** — проектирование рабочих процессов для Claude Code, кастомные субагенты, MCP
- **Веб-разработка** — FastAPI-бэкенды, React/TypeScript-фронты, статические лендинги
- **Аналитика** — SEO-аудиты, исследование рынка, структурированные отчёты

---

## 📈 Статистика · Stats

<div align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=ad620an&show_icons=true&locale=ru&hide_border=true&card_width=460" alt="GitHub stats" />
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ad620an&layout=compact&locale=ru&hide_border=true&card_width=320" alt="Top languages" />
</div>

---

<div align="center">
  <i>«Рутинная работа — это баг, а не фича» · "Manual work is a bug, not a feature"</i>
</div>
