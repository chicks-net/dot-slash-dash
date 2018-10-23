# dot-slash-dash
ascii-art dashboard

## layout

The `dash_lay.txt` is like a mini-spreadsheet.  If you have a layout like this:

| `A1` |  `B1` |  `C1` |
|  |  `B2` |  `C2` |
|  |   |  `C3` |

You have

* 3 columns `A` through `C`
* 3 rows `1` through `3`
* one column has one row, another has two, and the last has all three

You can

* have 1-n rows in each column
* up to 26 columns `A` through `Z`

Here is an example `dash_lay.txt` for the above layout:

```
A1: users
B1: weather work
B2: weather home
C1: todo.todo
C2: todo.done
C3: todo.touched_today
```
