uv sync - скачивает все зависимости и далее уже при помощи uv run можно запускать все команды из под venv
uv init py_project
cd py_project
echo "3.11" > .python-version
uv add numpy
uv lock
И все готово