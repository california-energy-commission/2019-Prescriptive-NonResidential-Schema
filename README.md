# 2019-Prescriptive-NonResidential-Schema

[![Remote Dispatch Action Dispatcher](https://github.com/RASENTSolutionsLLC-NORESCO/2019-Prescriptive-NonResidential-Schema/actions/workflows/dispatch.yml/badge.svg)](https://github.com/RASENTSolutionsLLC-NORESCO/2019-Prescriptive-NonResidential-Schema/actions/workflows/dispatch.yml)

## Deploy Schema

`deploy-schema.exe` is a command line application executable file that was
written in [Golang](https://golang.org/). This application deploys the schema (replaces embedded
square markup, formats, indents, removes whitespace, orders alphabetically)
to a `deployed` folder.  There is also a `deploy-schema` script that runs
on Linux and MacOS.

### Windows

```
deploy-schema.exe
Usage: deploy-schema.exe [options]
Options:
  -d, --destination string
        Path to deploy the schema:
  -s, --source string
        Path to schema:
  -v, --version string
        Enter new schema version:
```

#### Example run

```
cd 2019-Prescriptive-NonResidential-Development
deploy-schema.exe -d . -s schema -v 2019.0.000
```
