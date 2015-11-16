# Sudoku

Ce défi consiste à résoudre des grilles de sudoku.

Comme ça:

```console
$ cat ./path/to/map.txt
2         4   6 9
1         6   4
  4         7
        3   8 5
8 1     2
9
    7 1         2
          2 3   4
5   2
$ ./sudoku ./path/to/map.txt
2 5 8 3 7 4 1 6 9
1 7 9 5 8 6 2 4 3
3 4 6 2 9 1 7 8 5
7 2 4 6 3 9 8 5 1
8 1 5 4 2 7 9 3 6
9 6 3 8 1 5 4 2 7
4 3 7 1 6 8 5 9 2
6 8 1 9 5 2 3 7 4
5 9 2 7 4 3 6 1 8
```