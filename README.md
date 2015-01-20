snake
=====

A simple terminal based snake game written in c with ncurses. Uses vim style 'hjkl' to move around (or the arrow keys if you please).

### Screenshot

![screenshot](https://raw.githubusercontent.com/mnisjk/snake/master/screenshot.png)

### How to compile & run

```
gcc -I/usr/include/ -osnake snake.c -lncurses
./snake
```

### Dependencies

snake.c relies on ncurses to draw to the terminal. To install on Ubuntu/Debian, use:

```
sudo apt-get install lib32ncurses5-dev
```


### License

Use, copy and/or distribute in any way you want.
