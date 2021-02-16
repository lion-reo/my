# pip install
次のような警告が出た。
```
WARNING: You are using pip version 20.2.3; however, version 21.0.1 is available.
You should consider upgrading via the 'c:\users\kages\appdata\local\programs\python\python39\python.exe -m pip install --upgrade pip' command.
```
pipをupgradeする。
```
$pip install --upgrade pip
Collecting pip
  Downloading pip-21.0.1-py3-none-any.whl (1.5 MB)
     |████████████████████████████████| 1.5 MB 6.4 MB/s
Installing collected packages: pip
  Attempting uninstall: pip
    Found existing installation: pip 20.2.3
    Uninstalling pip-20.2.3:
      Successfully uninstalled pip-20.2.3
ERROR: Could not install packages due to an EnvironmentError: [WinError 5] アクセスが拒否されました。: 'C:\\Users\\kages\\AppData\\Local\\Temp\\pip-uninstall-wazud02y\\pip.exe'
Consider using the `--user` option or check the permissions.
```



# python
ライブラリのインストール
```
$pip install numpy
Collecting numpy
  Downloading numpy-1.20.1-cp39-cp39-win_amd64.whl (13.7 MB)
     |████████████████████████████████| 13.7 MB 3.3 MB/s
Installing collected packages: numpy
Successfully installed numpy-1.20.1
```
```
$pip intall matplotlib
Collecting matplotlib
  Downloading matplotlib-3.3.4-cp39-cp39-win_amd64.whl (8.5 MB)
     |████████████████████████████████| 8.5 MB 6.4 MB/s
Requirement already satisfied: numpy>=1.15 in c:\users\kages\appdata\local\programs\python\python39\lib\site-packages (from matplotlib) (1.20.1)
Collecting cycler>=0.10
  Downloading cycler-0.10.0-py2.py3-none-any.whl (6.5 kB)
Collecting pyparsing!=2.0.4,!=2.1.2,!=2.1.6,>=2.0.3
  Downloading pyparsing-2.4.7-py2.py3-none-any.whl (67 kB)
     |████████████████████████████████| 67 kB 4.5 MB/s
Collecting pillow>=6.2.0
  Downloading Pillow-8.1.0-cp39-cp39-win_amd64.whl (2.2 MB)
     |████████████████████████████████| 2.2 MB 6.4 MB/s
Collecting kiwisolver>=1.0.1
  Downloading kiwisolver-1.3.1-cp39-cp39-win_amd64.whl (51 kB)
     |████████████████████████████████| 51 kB ...
Collecting python-dateutil>=2.1
  Downloading python_dateutil-2.8.1-py2.py3-none-any.whl (227 kB)
     |████████████████████████████████| 227 kB ...
Collecting six
  Downloading six-1.15.0-py2.py3-none-any.whl (10 kB)
Installing collected packages: six, python-dateutil, pyparsing, pillow, kiwisolver, cycler, matplotlib
Successfully installed cycler-0.10.0 kiwisolver-1.3.1 matplotlib-3.3.4 pillow-8.1.0 pyparsing-2.4.7 python-dateutil-2.8.1 six-1.15.0
```
