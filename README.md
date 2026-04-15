# 🖱️ AutoClicker

[ 🇬🇧 English version below ]

**AutoClicker** — современный, настраиваемый и скрытный инструмент для автоматизации рутинных задач и гейминга.

Помимо классического закликивания, программа поддерживает запись макросов, очередь координат, умную хуманизацию движений для обхода античитов и кастомные темы оформления. Отличный выбор для требовательных игр.

-----

## ✨ Основной функционал

  * **Драйверы ввода:** Поддержка стандартного WinAPI, а также обход программных проверок (снятие флага `LLMHF_INJECTED`) через аппаратный виртуальный драйвер **Logitech G HUB** и **Interception**.
  * **Запись макросов:** Записывайте траекторию движения мыши и клики для точного повторения действий.
  * **Очередь координат (Multi-Point):** Укажите несколько точек на экране, и кликер будет нажимать на них по очереди.
  * **Привязка к окну:** Отправляйте клики в фоновое окно (через PostMessage), пока занимаетесь своими делами в другом.
  * **Режим скролла:** Эмуляция прокрутки колесика мыши (вверх/вниз) вместо обычных кликов.
  * **Анти-АФК:** Программа раз в заданный интервал эмулирует случайные движения мышью или нажатия клавиш (W, A, S, D, Space), предотвращая кик с сервера.
  * **Умные ограничения:** Настройте автоматическую остановку по таймеру (в секундах) или по лимиту количества кликов.
  * **Экранный прицел:** Поверх всех окон выводится прозрачный настраиваемый прицел (точка, крестик или круг) с выбором цвета и размера. Клики проходят сквозь него.
  * **Активация мышью:** Запускайте кликер не только кнопками клавиатуры, но и дополнительными кнопками мыши.

## 🛡️ Безопасность и "Хуманизация"

  * **Плавающий курсор:** Имитация легкого тремора руки — при каждом клике курсор случайно смещается на 1-2 пикселя.
  * **Случайная задержка:** Добавляет случайный разброс (в миллисекундах) к базовой скорости, делая интервалы между кликами неравномерными.

## 🎨 Кастомизация и Удобство

  * **Темы оформления (XAML):** Поддержка пользовательских тем. Закиньте `.xaml` файл с палитрой цветов в папку `Themes`, и тема появится в меню без перезагрузки программы.
  * **Умные профили:** Создавайте конфигурации под разные задачи и привязывайте их к конкретным процессам (например, `game.exe`). Кликер сам переключит настройки, когда вы развернете нужное окно.
  * **Виджет и Трей:** Сворачивайте программу в системный трей. Доступен компактный мини-виджет поверх всех окон, показывающий статус работы и текущий профиль. Правый клик по иконке в трее открывает кастомное меню.
  * **Гибкий интерфейс:** Настройка прозрачности, масштаба окна, закругления углов, точный ввод скорости текстом и запоминание позиции на экране.
  * **Многоязычность:** Русский, Английский, Французский, Украинский и Китайский языки.
  * **Полная очистка:** Кнопка "Очистить реестр" удаляет все следы настроек программы из системы в один клик.
  * **Статистика:** Отслеживание общего количества сделанных кликов на вкладке "О нас".

-----

## 🚀 Установка и запуск

Программа портативна и не требует установки.

1.  Перейдите в раздел [Releases](https://github.com/ZerioCommand/AutoClicker/releases) и скачайте последнюю версию `.exe` файла.
2.  Запустите `AutoClicker.exe`.
3.  *(Опционально)* Для установки пользовательских тем создайте папку `Themes` рядом с исполняемым файлом и поместите туда XAML-файлы (одна готовая тема уже включена в архив).

<br>

-----

-----

<br>

# 🇬🇧 English Version

**AutoClicker** is a modern, highly customizable, and stealthy tool designed for both routine automation and gaming.

Beyond standard rapid-clicking, it supports full macro recording, coordinate queuing, smart mouse humanization to bypass basic detections, and on-the-fly custom UI themes.

-----

## ✨ Core Features

  * **Input Drivers:** Choose between standard WinAPI, or bypass software detection (stripping the `LLMHF_INJECTED` flag) using the **Logitech G HUB** virtual driver or **Interception**.
  * **Macro Recording:** Record mouse paths and clicks to repeat exact sequences effortlessly.
  * **Coordinate Queue (Multi-Point):** Set multiple screen points, and the clicker will cycle through them automatically.
  * **Window Binding:** Send clicks to a background window via PostMessage while you work on something else.
  * **Scroll Mode:** Simulate mouse wheel scrolling (up or down) instead of standard clicks.
  * **Anti-AFK:** Prevents server kicks by making random mouse movements or pressing movement keys (W, A, S, D, Space) at set intervals.
  * **Smart Limits:** Stop the clicker automatically based on a countdown timer or a specific click limit.
  * **Screen Crosshair:** Overlay a click-through, customizable crosshair (dot, cross, or circle) over any application with adjustable size and colors.
  * **Mouse Activation:** Trigger the clicker using extra mouse buttons instead of keyboard hotkeys.

## 🛡️ Stealth & Humanization

  * **Floating Cursor:** Simulates natural hand movements by randomly shifting the cursor 1-2 pixels during clicks.
  * **Random Delay:** Adds a random millisecond spread to your clicking speed, making the pattern unpredictable and human-like.

## 🎨 Customization & Quality of Life

  * **XAML Themes:** Drop any valid `.xaml` color dictionary into the `Themes` folder to instantly change the app's look without restarting.
  * **Smart Profiles:** Save unique configurations and bind them to specific `.exe` processes. The app automatically swaps profiles when you alt-tab into the active game or program.
  * **Tray & Overlay Widget:** Minimize the app to the system tray and enable a sleek overlay widget that displays your active profile and clicking status. Right-clicking the tray icon opens a custom quick-menu.
  * **UI Controls:** Adjust window transparency, UI scale, corner rounding, toggle exact text-based speed input, and save the window position.
  * **Multilingual:** Built-in support for English, Russian, French, Ukrainian, and Chinese.
  * **Registry Cleaner:** A single button to completely wipe all saved configurations and profiles from your system registry.
  * **Statistics:** Tracks your lifetime total clicks in the "About" tab.

-----

## 🚀 Installation & Usage

The application is fully portable.

1.  Go to the [Releases](https://github.com/ZerioCommand/AutoClicker/releases) section and download the latest `.exe` file.
2.  Run `AutoClicker.exe`.
3.  *(Optional)* To install custom themes, create a `Themes` folder next to the executable and place your `.xaml` files inside (one theme is included by default).
