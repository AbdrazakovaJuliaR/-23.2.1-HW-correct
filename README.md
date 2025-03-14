# Project-23.2.1-HW-correct

## 📌 Описание проекта

Данный скрипт парсит фильмы из дневника пользователя на платформе **Letterboxd**, собирает информацию о рейтинге и понравившихся фильмах и сохраняет результаты в файл Excel. 

**Функционал:**
- Извлекает **название фильма, год выхода, рейтинг**.
- Определяет, какие фильмы отмечены как **понравившиеся**.
- Сортирует понравившиеся фильмы по рейтингу.
- Сохраняет данные в **Excel** с двумя вкладками:
  - `All Movies` – все фильмы пользователя.
  - `Liked Movies` – понравившиеся фильмы.

---

## 🔧 Установка и запуск

Для работы скрипта требуется Python **3.8+** и библиотеки:

```bash
pip install requests bs4 pandas openpyxl
а также time и concurrent.futures
