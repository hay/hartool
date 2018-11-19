# hartool
> HAR (HTTP Archive) utility, written for Python 3.6+

## Install
The only dependency for this utility is `haralyzer`, so either do

    pip install haralyzer

Or use the `Pipfile` together with `pipenv`.

## Usage

```bash
usage: hartool [-h] [-p PAGE] [-x] [-xi] [-ls] [-v] [path]

positional arguments:
  path                  path to HAR file

optional arguments:
  -h, --help            show this help message and exit
  -p PAGE, --page PAGE  specify page ID in archive
  -x, --extract         extract all files
  -xi, --extract-images
                        extract all images
  -ls, --list           list pages in file, add -v to list assets too
  -v, --verbose         print extra debug information
```

## License
MIT &copy; [Hay Kranen](http://www.haykranen.nl)