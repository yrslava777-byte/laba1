# ЛР 1. Процесс изнутри

Программа на C. PID 26813 совпал в Терминале и Мониторинге системы. Физическая память составила 544 КБ, время ЦП 0,01 с. При ожидании ввода getchar блокируется. Дескрипторы 0, 1 и 2 ведут в /dev/ttys000. В карте памяти 44 файла .dylib, включая libSystem.B.dylib. После завершения из Мониторинга системы код выхода 143 (SIGTERM).

Программа на Python. PID 27127 совпал в обоих окнах. Физическая память составила 1,2 МБ, примерно в 2,2 раза больше. Общая библиотека libSystem.B.dylib. После Enter код выхода 0.

[Открыть PDF](Лабораторная%20работа%201.pdf)

## Снимки

![01](screenshots/01_program_started.png)

![02](screenshots/02_process_found.png)

![03](screenshots/03_process_properties.png)

![04](screenshots/04_process_files.png)

![05](screenshots/05_process_libraries.png)

![06](screenshots/06_killed.png)

![07](screenshots/07_python_memory.png)

![07](screenshots/07_python_monitor.png)

![07](screenshots/07_python_process.png)

![08](screenshots/08_python_exit.png)
