# python-library-template
A template repository for pure Python modules developed at the University of Saskatchewan
Atmospheric Research Group (usask-arg).


## Check list when creating a new repository
After using this template, there are a few files which need to be updated.

`pyproject.toml`
 - Read through and update all fields in the `[project]` section

`conda.recipe/meta.yaml`
 - Update the `package:` section with the package name
 - Update the `tests: imports:` section with the package name
 - Look through the `about:` section and update accordingly

`src/__init__.py`
 - Remove the example function

`tests/test_example.py`
 - Delete this file, or rename and use for your own tests

`docs/source/conf.py`
 - Update lines 9 through 12 accordingly

`README.md`
 - Delete all contents above `# usask-arg-example` and read through the remainder, updating accordingly

`LICENSE`
 - The default license is the MIT license, change this if you want a different license.  Also make sure to update the License section in the README

## Adding dependencies
If you need to add a dependency to the project, it must be added in the following places

- `env.yml`
- `pypoject.toml`, the "dependencies" section
- `conda.recipe/meta.yaml`, the "requirements/run" section

## Updating Python versions
The template is configured to test the code on the latest three available Python versions.  These are defined in

- `pyproject.toml`
- `.github/workflows/test.yml`

# usask-arg-example

Short description of project here

## License
This project is licensed under the MIT license
