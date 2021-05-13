# compile-Java

Just a makefile to compile and run java file with this specific organization :

```.
├── class
│   └── *.class
├── data
├── javaDoc
├── src
│   └── *.java
└── ws
    └── Makefile
   ```

class, javaDoc and data folder can be change in the file

It has multiple option :

- `make` will compile every file in src/ including folder
- `make compress` same as make
- `make javadoc` compile all and generate the javadoc in another folder
- `make zip` compile and generate the javadoc and then place them in a .zip. If there is a data folder, add it to the zip
- `make run ARGS=FileYouWantToRun` compile every src and then run the specified file
