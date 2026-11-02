# products-mysql


Настройка базы данных MySQL в Docker, создание таблиц, вставка данных и выполнение базовых запросов.

## 1. Запуск контейнера MySQL
Контейнер базы данных успешно запущен. Использовался образ `mysql:latest`, настроен пароль для root и смонтирован том для хранения данных.

**<img width="660" height="260" alt="изображение" src="https://github.com/user-attachments/assets/d5782f11-213a-4945-ad3b-3e6976480859" />
**

## 2. Создание базы данных и таблиц
Внутри контейнера создана база данных `shop` с поддержкой кодировки `utf8mb4`. В ней созданы две таблицы `products1` и `products2` для хранения списка товаров.

**<img width="1294" height="600" alt="изображение" src="https://github.com/user-attachments/assets/b22bff64-237c-4df0-93d7-702cb450f03b" />
**


## 3. Вставка данных и результаты
В таблицы добавлены тестовые данные (фрукты и их цены). Выполнены SQL-запросы `SELECT` для вывода содержимого таблиц.
<img width="1119" height="702" alt="изображение" src="https://github.com/user-attachments/assets/ff6f67ae-79a7-492a-9629-a9c2bd5995b5" />


**Содержимое таблицы `products1`:**
**<img width="336" height="214" alt="изображение" src="https://github.com/user-attachments/assets/c24bc20e-944c-4373-be46-3899f087473d" />
**

**Содержимое таблицы `products2`:**
**<img width="321" height="174" alt="изображение" src="https://github.com/user-attachments/assets/ec35a125-b534-48f9-affe-960edcbfe605" />
**

## Вывод
В ходе работы была развернута база данных MySQL в Docker-контейнере. Освоены команды создания баз данных, таблиц, настройки кодировки (utf8mb4), а также добавления и извлечения данных с помощью SQL-запросов.
