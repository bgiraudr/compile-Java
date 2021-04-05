# compile-Java

Just a little bash script to compile and run java file with this specific organization :

```.
├── class
│   └── *.class
├── javaDoc
├── src
│   └── *.java
└── ws
    └── compile
   ```

It has multiple option :

- `./compile` if there is only one file, will compile and run it. Else it will let you choose
- `./compile all` will compile every file (package too)
- `./compile javadoc` will generate the javadoc
- `./compile compress` will create a .zip file with the javadoc and all files. It's name is `$name-$directory`. You can change the name in the script
- `./compile <FILENAME>` will compile and run the file
- `./compile <FILENAME> a` will compile all files before run the program
