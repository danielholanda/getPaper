# GetPaper
Get paper is a software to download IEEE Xplore papers from a remote host.

## Installing dependencies

You might need to install pexpect.
```
pip install pexpect
```

## Configuring

Before running GetPaper, you have the option of hardcoding your username and host into the getPaper file using your preferred text editor. Hardcoding your password into the file is also possible, but not recommended. 

Moreover, you might need to make this file executable using the command:
```
chmod +x getPaper
```

## Running

Simply run getPaper followed by the full URL of the IEEE Xplore document you want to download.

Example:
```
./getPaper https://ieeexplore.ieee.org/abstract/document/8977853
```
