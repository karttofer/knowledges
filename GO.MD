# ***Go*** - By A Frontend Perspective
Currently, I'm crafting this kind of documentation without any prior knowledge of ***Go***. This is a personal project I embarked upon to assist my future self, enabling me to review it should I ever have any uncertainties.

In other words, this document is being created based on my understanding and perception of what ***Go*** is and how I interpret it. I prefer to avoid overly lengthy explanations, so I will strive to keep each explanation brief and concise.

Another of the reasons why I created this documentation is due to the ever-changing dynamics of the job market concerning Frontend developers. I feel that we should explore different horizons beyond the mere creation of user interfaces. (And as a Frontend developer, I don't intend to imply that designing user interfaces is easy, but rather that the market is undergoing a transformation; that's my perspective.) We must begin to acquaint ourselves not only with the functioning of the backend, but also with other languages beyond just Java, C++, or C#.

Without further ado, let's get started!"
## Installation
The installation of ***Go*** is relatively straightforward, a bit different if you come from the Frontend and have never dealt with another language apart from JavaScript.

We can even compare its installation with Python. Furthermore, I assume you are aware of what an IDE is and that you already have one installed. In my personal case, I use Visual Studio Code, which is well-suited for ***Go***.
And also, if you're coming from another operating system like MacOS, you'll need to do a separate installation, and for that, I'll provide you with some tutorials down below.

For MacOS, the installation process is the same; you just need to click "next, next," and you'll have ***Go*** up and running on your computer. However, I want to emphasize that this entire document was created on Windows.

Follow the basic steps and you won't be able to get lost <br>
<br>
<center>
<img width="395" alt="1" src="https://github.com/karttofer/knowledges/assets/34972636/7633ff5a-7a62-4922-a001-44bc950f20e6">
</center>

Then, run this command, and you should be able to see the installed version on your computer. If you can't see it, it means you encountered an issue with the installation (obviously).
```node
go version
go version go1.21.0 windows/amd6
```
## Commands
The commands I'll provide below are the ones I usually use, although please keep in mind that I'm still learning, so these would be the commands that someone with little experience would only know how to use.

This may change gradually as I progress through the document.

```
go <command> [arguments]

get         add dependencies to current module and install them
install     compile and install packages and dependencies
mod         module maintenance
list        list packages or modules
test        test packages
run         compile and run Go program
build       compile packages and dependencies
clean       remove object files and cached files
fmt         gofmt (reformat) package sources
generate    generate Go files by processing source
version     print Go version
```

So, these ***commands*** are I usually use but each of them has its own [arguments]. So, I will leave you the documentation to read it <a href="https://pkg.go.dev/cmd/go">_I'm the doc baby!_</a>

# Let's kick some commands 
And when I say that it might change, I'm saying it right now. Let's try out some of the commands we have using a Go project I've created on my computer. We'll be discovering their purposes and understanding them in "depth".
