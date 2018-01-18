# Geilo Winter School 2018: Pratical Artificial Intelligence

## Install AMIST Toolbox

First, check whether you have installed Java 8:
```bash
$ java -version
```
If Java 8 is not installed download it from [here](http://www.oracle.com/technetwork/java/javase/downloads/index.html).

For compiling and runing the toolbox you have two options:

1. **Intellij IDEA**: You can download it from [here](https://www.jetbrains.com/idea/). 

2. **Maven**: Follow the [official web page](https://maven.apache.org/install.html) for instructions about how to install it. 


## Download the code repository

First, download the project code:

```bash
$ git clone https://github.com/andresmasegosa/GeiloWinterSchool2018.git
```

Enter in the downloaded folder:

```bash
$ cd example-project/
```

If you have installed maven, you can compile and build the package:

```bash
$ mvn clean package
```

For runing a piece of code you should type:

```bash
$ java -cp target/example-project-full.jar BasicExample

```
