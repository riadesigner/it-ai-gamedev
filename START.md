# Старт: «ИИ в игровой разработке»

Выжимка контекста и согласованных решений. Читать в начале любой сессии по курсу.

## Аудитория

- Колледж, Россия. Студенты **17–19 лет**, обучение **3 года**.
- Предмет ведётся для **2 курса** (программирование уже начато: JS, Python, C# — всё ещё базово).
- Есть также 1 курс; фокус материалов — на 2-й.
- Уровень JS **разный** (Java, C#, начальный JS) — на практиках с кодом **архитектуру и реализацию отдаём ИИ**, человек формулирует поведение и проверяет результат.

## Преподаватель (я)

- Web-fullstack: vanilla JS, Node.js, React, Postgres, nginx, Linux.
- Немного Python (скрипты).
- Blender, web-design.
- Cursor: агенты и skills.



## Ограничения по инструментам (РФ)

Доступны (бесплатно / относительно доступно):

- DeepSeek, Qwen, GigaChat
- Возможно DeepSeek → Visual Studio через Cline (уточнить при сетапе)



## Нагрузка семестра

- **9 встреч** (дней) с преподавателем
- На встречу: **2 пары** по **1,5 часа**
- Итого: **18 пар** ≈ **27 ч** контакта
- Календарно: ~4 пары в неделю (2 встречи в неделю по 2 пары)



## Философия курса (главное решение)

**Цель:** показать **полезность разных видов ИИ** в играх на живых примерах; движки (web, threejs, godot) — только полигон.

Итог для студента: видел несколько видов ИИ, сделал 3–4 мини-демо, понимает куда копать дальше.

## Полигон (чем делаем демо)


| Роль             | Выбор                                                        |
| ---------------- | ------------------------------------------------------------ |
| Основной полигон | **Web**: canvas → three.js, glTF/спрайты, ProcGen в браузере |
| Игровой движок   | **Godot 2D** (GDScript ближе к Python/JS)                    |


## Связанные файлы

- [syllabus-sketch.md](./syllabus-sketch.md) — грубый план модулей и встреч  
- [day-01/day-01.md](./day-01/day-01.md) — подробно: день 1 (2 пары)  
- [day-02/day-02.md](./day-02/day-02.md) — подробно: день 2 (2 пары)  
- [day-02/tasks/task-02.md](./day-02/tasks/task-02.md) — задание дня 2 для студентов (GitHub)  
- [day-02/examples/starter/index.html](./day-02/examples/starter/index.html) — стартер canvas для практики  
- [day-02/examples/demo-canvas-minimal/index.html](./day-02/examples/demo-canvas-minimal/index.html) — эталон ч.1: игрок + стены  
- [day-02/examples/demo-canvas-enemy/index.html](./day-02/examples/demo-canvas-enemy/index.html) — эталон ч.2: враг patrol/chase/attack (не раздавать до конца практики)  
- [day-01/lecture/lect-01.html](./day-01/lecture/lect-01.html) — слайды дня 1  
- [day-01/tasks/task-01.md](./day-01/tasks/task-01.md) — задание дня 1 для студентов (GitHub)  
- [day-01/examples/demo-gdd-01-guard.md](./day-01/examples/demo-gdd-01-guard.md) — эталон GDD №1 («Страж арены»)  
- [day-01/examples/demo-gdd-02-sigil.md](./day-01/examples/demo-gdd-02-sigil.md) — эталон GDD №2 (SIGIL SNATCHER; FSM без «фонового» состояния)  
- [day-01/lecture/lect-01-faq.md](./day-01/lecture/lect-01-faq.md) — ответы на вопросы по теме дня 1 (дописывать)  
- [decisions.md](./decisions.md) — журнал решений и идей (дополнять по ходу)

