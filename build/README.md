## Compiling The Theme

This was taken from https://github.com/jagannatharjun/qbt-theme/tree/master/Builds  

To build the theme from source, glone the repo, and use the [make-resource.py](./make-resource.py)

You're gonna need [python](https://www.python.org/downloads/) to run the script

Usage:
cd into the [src](../src/) directory and run the [make-resource.py](./make-resource.py) script.

```
python ../build/make-resource.py -style .\stylesheet.qss -base-dir . -icons-dir .\icons\ -config .\config.json -find-files -output please-6.qbtheme
```

Commands:
```
helper to create qbtthemes

positional arguments:
  files                 files to include in resources from baseDir, supports
                        glob patterns

optional arguments:
  -h, --help            show this help message and exit
  -output OUTPUT        output qbtheme file
  -style STYLE          stylesheet
  -base-dir BASEDIR
  -icons-dir ICONSDIR   directory which contains custom icons
  -dir-prefix DIRPREFIX
                        prefix added to all files
  -config CONFIG        file used as config.json
  -find-files           find files included in qss and only include those
```