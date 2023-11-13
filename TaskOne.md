# Task 1: Create a function to run fastQC from terminal
### [1] Install fastQC dependencies
Firstly, I need to install Java on my Windows system. To do so, I followed the instructions given here: https://phoenixnap.com/kb/install-java-windows. To test, in Git Bash terminal 
```nano JavaTest.sh``` was created where the following was written: 
```
class HelloWorld{
	public static void main(String args[]){
		System.out.println("Hello world!");
		}
}

# saved in Nano as .java file
```
and tested 
```
javac JavaTest.java
java JavaTest.java

# output: 
Hello world!
```
### [2] Install fastQC 
Downloaded fastQC and unzipped file. To test, travelled to the directory where it was saved ``` ~/Training/FastQC/fastqc_v0.12.1/FastQC ``` and ran 
```
fastqc - version 
# output : 
FastQC v0.12.1
```
Once installation was confirmed, tested it with scRNA-seq files 
```
fastqc 
