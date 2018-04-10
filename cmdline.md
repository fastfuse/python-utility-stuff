### '-m' command line option

#### Create virtual environment

```commandline
python -m venv venv_dir
```

#### HTTP server

Python2:

```commandline
python -m SimpleHTTPServer 8000
```

Python3:
```commandline
python -m http.server 8080
python -m http.server 8080 --bind 127.0.0.1
```

#### Pretty print JSON

```commandline
echo '{"foo": "bar", "spam": "ham"}' | python3 -m json.tool
```

#### Run doctest

```commandline
python -m doctest test_file.py
```

#### Create/extract *.tar files
See [docs](https://docs.python.org/3/library/tarfile.html#command-line-interface) for details

```commandline
python -m tarfile <options>
```
