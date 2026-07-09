# Cubyz Wiki Source Repository

This repository contains source markdown files of Cubyz Wiki.

To locally build Cubyz Wiki you need Python interpreter in version 3.8 or newer.
To install necessary requirements it is recommended to create isolated environment:

```
python -m venv .env
```

Mind that not every linux distro ships `venv` package alongside interpreter. You have to
check exact details for your distro.

After creating virtual environment, you have to activate it:

Linux:

```
source .env/bin/activate
```

Windows:

```
.\.env\Scripts\activate
```

Once virtual environment is activated, you can proceed to install Cubyz Wiki requirements:

```
pip install -r requirements.txt
```

Afterwards you should be able to build Cubyz Wiki files:

```
zensical build --clean
```

You can also serve the built documentation locally, so the changes are reflected in real time:

```
zensical serve
```
