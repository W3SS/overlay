Overlay
=================

**Overlay** is a *Yu-Gi-Oh! Trading Card Game* engine made with **Haxe**

## Screenshots

This project is under development. Any screenshot displayed here has been taken during tests.

![screenshot 2017/12/19](screenshots/20171219.png)

## Usage

### Build

You'll need **Haxe**, the **random** and **thx.text** haxe libraries.
```bash
for lib in random thx.text; do haxelib install $lib; done # first run if you don't have them
haxe make.hxml # build
```

### Run

Run it with **Neko** (or other platform you can configure in `make.hxml`, as the project is currently platform independant)

```bash
neko bin/Overlay.n
```

## License

This project is distributed under the WTFPL v2.0
