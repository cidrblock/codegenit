### Getting started

```
python3 -m venv venv
source venv/bin/activate
pip install codegenit
https://raw.githubusercontent.com/OAI/OpenAPI-Specification/master/examples/v2.0/yaml/petstore.yaml
mv petstore.yaml api.yml
codegenit
```


### Usage
```
$ codegenit --help
usage: codegenit [-h] [-c CODEGEN_DIR] [-p PROJECT_DIR] [-s SWAGGER_FILE]

Generate a python project from a swagger file.

optional arguments:
  -h, --help            show this help message and exit
  -c CODEGEN_DIR, --codegen_dir CODEGEN_DIR
                        A folder in which to place the codegend project. (default: ./swagger_codegen/)
  -p PROJECT_DIR, --project_dir PROJECT_DIR
                        A folder in which to place the codegend project. (default: ./)
  -s SWAGGER_FILE, --swagger_file SWAGGER_FILE
                        A folder in which to place the codegend project. (default ./api.yml)
```
