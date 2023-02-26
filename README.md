# How-use-7zip
How use 7zip

Install
```
sudo apt update
sudo apt-get install p7zip-full
```


To compress a file or folder
```
7z a [output file name] [input file or folder name]
7z a archive.7z file1
```

To compress a file or folder with password
```
7z a -p archive.7z file1
```

To extract an archive file to a specific directory:
```
7z x [archive file name] -o[output directory name]
```
