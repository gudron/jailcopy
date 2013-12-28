# JAILCOPY HELPER

## About Jailcopy
Little and simple helper for copy binary file and their ".so" or ".dlib"(on MacOS X) libraries into jail root path. 
// TODO write anything about that bash script


## Required

Linux-like or bsd-like or MacOS operation system

## Installation & Documentation

### Installation

On Linux and BSD OS:
```bash
sudo sh -c 'wget https://raw.github.com/gudron/jailcopy/master/jailcopy -P /usr/local/bin && chmod +x /usr/local/bin/jailcopy'
```

### Documentation



<pre>
USAGE: ./jailcopy -n <BINARY_NAME> -j <JAIL_ROOT>
Options:
	-n <BINARY_NAME>	Binary application name.	 Example: bash, sh, rsync
	-j <JAIL_ROOT>		Jailroot path.				 Example: /home/virtualhosts/example.dev	
</pre>