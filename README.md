# dot-slash-dash

[![Open Source Love png2](https://badges.frapsoft.com/os/v2/open-source.png?v=103)](https://github.com/ellerbrock/open-source-badges/)
[![GPLv2 license](https://img.shields.io/badge/License-GPLv2-blue.svg)](https://github.com/chicks-net/dot-slash-dash/blob/master/LICENSE)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/chicks-net/dot-slash-dash/graphs/commit-activity)

ascii-art dashboard

## layout

The `dash_lay.txt` is like a mini-spreadsheet.  If you have a layout like this:

| A | B | C |
| :-- | :-- | :-- |
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
