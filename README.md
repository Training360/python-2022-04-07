# Selenium példaprogram

Telepítendõ:

* 64-bit Git for Windows Setup: https://git-scm.com/download/win, https://github.com/git-for-windows/git/releases/download/v2.35.1.windows.2/Git-2.35.1.2-64-bit.exe
* Python Windows installer (64 bit): https://www.python.org/downloads/release/python-3104/, https://www.python.org/ftp/python/3.10.4/python-3.10.4-amd64.exe

Ha nem mûködik, esetleg lehet próbálkozni a [Portable Pythonnal](https://portablepython.com/), és a Git portable verziójával.

Ehhez az oldalhoz kell hozzáférés: https://pypi.org/

A projekt a `git clone https://github.com/Training360/python-2022-04-07` paranccsal clone-ozható. Vagy Code gomb és Download ZIP.

A könyvtárában parancssorban kiadandó parancsok:

```shell
python -m venv venv
venv\Scripts\activate.bat
pip install -r requirements.txt
python hello_selenium.py
```

Lásd [screenshot](screenshot.png)!

