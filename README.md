# Templates for Efficient Coding
This repo includes template for Bash files, makefile, CMakeLists that I used frequently.

## Bash Template
### cleanGitignore.bash
```shell
chmod 700 cleanGiignore.bash
./cleanGiignore.bash < .gitignore
```
**Note**: In gitignore file, make sure to have new line at the end so the bash file can read the last line with filename

## makefile Template
### makefile
```shell
make 
```

## CMakeLists Template
### CMakeLists.txt
```shell
mkdir build
cd build
cmake ../
make
```





