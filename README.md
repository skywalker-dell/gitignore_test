# gitignore_test
test rules about .gitignore
!/bin/run.sh: 不忽略 bin 目录下的 run.sh 文件
bin/: 忽略当前路径下的bin文件夹，该文件夹下的所有内容都会被忽略
bin_exist_file/: 不忽略 bin_exist_file 文件
/bin: 忽略根目录下的bin_ignore_file文件
/*.c: 忽略 cat.c，不忽略 build/cat.c
debug/*.obj: 忽略 debug/io.obj，不忽略 debug/common/io.obj 和 tools/debug/io.obj
**/foo: 忽略/foo, a/foo, a/b/foo等
a/**/b: 忽略a/b, a/x/b, a/x/y/b等
*.log: 忽略所有 .log 文件
config.php: 忽略当前路径的 config.php 文件
                                                                                                                                                               