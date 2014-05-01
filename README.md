# AMS (android-missing-strings)

**ams** (android-missing-strings) is a simple command line reporting tool to know what strings need to be translated on an android project.

The output of ams is a pdf file friendly to a non-coding person who can be in charge of managing the translators involved in the project.

## Requirements

[pyPDF](https://code.google.com/p/pyfpdf/)

## Installation
Make sure you have **ams** on your $PATH environment variable.

## Usage:
from within any android project, just execute

```bash
ams [-l xx[,yy,zz...]] -o <output_file>

    Options:
    -h --help            Print this help


    -l --lang <xx>       Specify a language or many with comma separated 2-char language codes.

                         e.g:  -l cn         (creates report for Chinese strings.xml)
                               -l cn,it,fr   (creates report for Chinese, Italian and French strings.xml files)

                         If this parameter is ommited, a report with every language file found will be created.


    -o --oFile           Specify the output file name for the PDF report
```

## License
Copyright (c) 2014 - The Mit License (MIT)

## Authors
 - Angel Leon <gubatron@gmail.com>
 - Katay Santos <kataysantos@gmail.com>
