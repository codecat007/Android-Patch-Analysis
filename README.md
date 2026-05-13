# Android Patch Analysis

The tool identifies the list of CVEs that will affect the given AOSP version using the data available on google security bulletin website.

## 中文描述

这是一个用于分析 Android 安全补丁的 Python 工具。  
它会从 Google Android 安全公告页面抓取漏洞信息，并根据输入的 Android 版本筛选可能受影响的 CVE，最后导出 Excel 报告，便于排查和跟踪补丁风险。


## Installation

Sync the repo and run

```bash
python android_patch.py
```

## Usage

```python
> python.exe .\android_patch.py
Enter the android version
>>11
[+] Scanned CVEs form Patch : 2022-04-01
[+] Scanned CVEs form Patch : 2022-03-01
[+] Scanned CVEs form Patch : 2022-02-01
[+] Scanned CVEs form Patch : 2022-01-01
[+] Scanned CVEs form Patch : 2021-12-01
.
.
.
.
.
.
.
[+] Scanned CVEs form Patch : 2015-09-01
[+] Scanned CVEs form Patch : 2015-08-01
[+] New Excel File Created
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.