# Multiprocessing
Для распараллеливания CPU-bound задач в Python используется модуль multiprocessing.
Использование данного модуля позволяет создать несколько процессов. 
Каждый процесс получает свой личный интерпетатор (у каждого процесса будет свой GIL) 
и  пространство в памяти. Таким образом, процессы будут выполняться параллельно друг другу. 
Очевидно, что создание процессов более ресурсоемкий процесс, чем создание потоков.

Для решения I/O bound задач, требующий ввода/вывода лучше использовать потоки!

