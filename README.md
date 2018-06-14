# Description

`stare` is a simple FILES WATCHER written in python.

It can monitor your script change and automatically re-execute it.

Inspiration from Petr Zemek -> [Restarting a Python Script Within Itself](https://blog.petrzemek.net/2014/03/23/restarting-a-python-script-within-itself/)

# Usage

by default, `stare` use `python` as the default interpreter.

```bash
  stare a.py
```

or you might specified your interpreter as below:

```bash
stare lessc main.less
```


finally, you can move `stare` to your `/bin` folder and use it easily.
