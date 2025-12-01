
python.exe -m pip list

python.exe -m pip install --upgrade pip
python.exe -m pip install --upgrade wheel
python.exe -m pip install --upgrade setuptools


uv python list
uv python install 3.13.7
uv python install 3.7.9


uv run main.py
uv run --python 3.7.9 main.py

uv run --with rich main.py
uv run --with rich --python 3.13 main.py

uv init --script main.py
uv init --script main.py --python 3.12
uv add --script main.py "rich"
uv add --script main.py "xyz"

uv init
uv add rich
uv add rich==14.1.0

uv remove rich

if u manually edit .python-version or pyproject.toml use
uv sysn
(no need to explicitly rint sysc as it gets executed with run command)
uv cache clean


uv add pyinstaller
uv add auto-py-to-exe
uv run .\.venv\Scripts\autopytoexe.exe


-------------------------------------------------------------------------------
uv add pyside6









