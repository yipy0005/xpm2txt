## xpm2txt
Updated xpm2txt.py to be compatible with Python 3.10

# Usage
```sh
usage: xpm2txt.py --f F --o O [--s S] [-h]

options:
  --f F       (Path, required) input xpm file
  --o O       (Path, required) output txt file
  --s S       (int, default=9999) Sorts the output by a given column
  -h, --help  show this help message and exit
  ```

## Running
Run

```sh
python xpm2txt.py --f <xpm_filename>.xpm --o <output_filename>.dat
```
