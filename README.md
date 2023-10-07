# Perancangan dan Pemrograman Web (PPW)

M Ichsanul Amal

Sistem Informasi 2019

Fasilkom UI

## URL

https://laataiasu.herokuapp.com/

## Status

[![pipeline status](https://gitlab.com/ichsanul/archieve-web-ppw/badges/master/pipeline.svg)](https://gitlab.com/ichsanul/archieve-web-ppw/-/commits/master)
[![coverage report](https://gitlab.com/ichsanul/archieve-web-ppw/badges/master/coverage.svg)](https://gitlab.com/ichsanul/archieve-web-ppw/-/commits/master)

## Step

- Windows

```bash
python -m venv venv
venv\Scripts\activate.bat
pip install -r requirements.txt

python manage.py migrate --run-syncdb
python manage.py runserver
```