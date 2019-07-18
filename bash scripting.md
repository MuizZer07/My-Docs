### - Change directory to home and create bin folder
```
$ cd ~
$ pwd
$ mkdir bin
```

### - Export bin directory to the environment
```
$ export PATH=$PATH:/home/thinkbricks/bin
```

### - create a new script with nano type instructions
```
$ nano hello-world
```

##### inside nano
```
echo Hello, World!
```

### - change permission for the script
```
$ chmod u+x hello-world
```

### - run the script from anywhere
```
$ hello-world
// output: Hello, World!
```
