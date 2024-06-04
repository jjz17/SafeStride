# SafeStride
Dashboard and analytics of city crime data to enable safe walking for pedestrians

## Data Source(s)
* [Boston Crime](https://data.boston.gov/dataset/crime-incident-reports-august-2015-to-date-source-new-system)

## Next Steps
1. [Project template](https://gist.github.com/ericmjl/27e50331f24db3e8f957d1fe7bbbe510) or [Cookie cutter template](https://cookiecutter-data-science.drivendata.org)

## Common Problems
* [psutil incompatible architecture](https://stackoverflow.com/questions/72619143/unable-to-import-psutil-on-m1-mac-with-miniforge-mach-o-file-but-is-an-incomp)
  * ```pip uninstall psutil```
  * ```pip install --no-binary :all: psutil```
* [Error importing numpy: you should not try to import numpy from its source directory;](https://stackoverflow.com/questions/72920577/mach-o-file-but-is-an-incompatible-architecture-have-arm64-need-x86-64)
  * pip3 install numpy==1.26.4  --compile --force-reinstall