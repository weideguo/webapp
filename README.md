可以直接访问的web应用


```shell
# 查看目录信息
tree -f -P "*.html|*.svg" ./ | grep -vE "(/yi/icons)"
```

```
.
├── ./2048.html
├── ./alliance.html
├── ./blockoverit.html
├── ./chart_show.html
├── ./matrix.html
├── ./minesweeper.html
├── ./mycounter.html
├── ./random_string.html
├── ./snake.html
├── ./tetris.html
├── ./tetris.svg
└── ./yi
    └── ./yi/yi.html

```
