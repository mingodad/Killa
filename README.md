# Killa

Killa is a programming language based in Lua and Javascript. It uses the Lua virtual machine and the Lua external C API with almost no changes but it has a different syntax similar to Javascript without the prototype mechanism and the ugly parts. 

Killa is a work in progress but it is already functional and has been tested inside popular game engines like the Love engine: https://bitbucket.org/ex/love and the cocos2d-x engine: https://github.com/ex/cocos2d-x


### Build on Windows

For Windows use the provided Visual Studio 2008 solution.

### Build on Mac OSX

Open the terminal and go to the directory where the Makefile is and type: 
<pre>
make macosx
make test
</pre>
tested in Mac OSX 10.6.8

### Build on Linux

From the terminal type:
<pre>
make linux
make test
</pre>

tested in Ubuntu 11
In case of error due to a readline.h header, install the library:
<pre>
sudo apt-get install libreadline-dev
</pre>

### Try it

For Windows users there are provided binaries and some example scripts to run.
Go to the directory [bin/windows] and type in the console window: 
<pre>
killa test.kia
killac -l test.kia
</pre>


