# (Реализовать получение числа силами argparse и логирование хода выполнения)
```
$ ./prime_num.py -1
2023-12-13 20:19:39,342: __main__ - DEBUG - Got number = -1
2023-12-13 20:19:39,342: __main__ - INFO - Число должно быть больше 1 и меньше 100000
$ ./prime_num.py 5
2023-12-13 20:19:53,766: __main__ - DEBUG - Got number = 5
2023-12-13 20:19:53,766: __main__ - DEBUG - Number 5 validated in 2 steps
2023-12-13 20:19:53,766: __main__ - INFO - 5 является простым числом
$ ./prime_num.py 100
2023-12-13 20:19:55,410: __main__ - DEBUG - Got number = 100
2023-12-13 20:19:55,410: __main__ - DEBUG - Number 100 validated in 2 steps
2023-12-13 20:19:55,410: __main__ - INFO - 100 является составным числом
$ ./prime_num.py 11
2023-12-13 20:20:12,272: __main__ - DEBUG - Got number = 11
2023-12-13 20:20:12,272: __main__ - DEBUG - Number 11 validated in 5 steps
2023-12-13 20:20:12,272: __main__ - INFO - 11 является простым числом
```