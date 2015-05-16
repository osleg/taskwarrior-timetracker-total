# TaskWarrior Report

A supplement script to http://github.com/kostajh/taskwarrior-time-tracking-hook.
Getting total time for complete tasks on a project.

## Usage
```
python report.py -h
usage: report.py [-h] [-f YYYY-DD-MM] [-t YYYY-DD-MM] project

positional arguments:
  project

optional arguments:
  -h, --help            show this help message and exit
  -f YYYY-DD-MM, --from YYYY-DD-MM
                        From date, inclusive
  -t YYYY-DD-MM, --to YYYY-DD-MM
                        To date, exclusive
```

For ease of use it is possible to `chmod +x report.py` and put it
in PATH
