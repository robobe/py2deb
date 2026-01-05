# py2deb

Create python project using uv
- pack to wheel using build
- pack to debian using debuild

- create project

uv init py2deb --lib

- add build package to project under dev section
uv add --dev build

- Run build to create wheel
 uv run python -m build --wheel


### deb

```
sudo apt install dh-python
sudo apt install pybuild-plugin-pyproject
sudo apt install python3-all

```