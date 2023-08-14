# Node - JS

## REPL - Read-Evaluate-Print-Loop
A Read-Eval-Print Loop, or REPL, is a computer environment where user inputs are read and evaluated, and then the results are returned to the user. REPLs provide an interactive environment to explore tools available in specific environments or programming languages. Some examples include the Node.js console, IPython, the Bash shell, and the developer console found in most web browsers.

**Quick Words**
We can write javascript code in the terminal using REPL.

```
R - read user input
E - evaluate user input
P - Print or output result
L - Return and wait for new input
```
## File System Module
The Node.js file system allows us to both read and write any type of information that we store in extensive .txt files. Also, we can read other types of files in Node.js, but we would have to perform a different kind of magic, hahaha. So, we will focus on the basics of Node and then we will progress from there.

```
fs.readFile( filename, encoding, callback_function )
```
As evident, the **readFile** method only accepts three parameters. So, at the very beginning, we require a fileName – and yes, it's not just about the name; the path is necessary as well. After that, we'll need to specify the encoding, which refers to how the content of the file was written. Lastly, the callback comes into play. This callback provides us with two parameters: an error indicator and the content of the file.

However, something you might want to know is that we can also include flags, and these flags refer to certain behaviors. Take a look at the information below.

```
fs.writeFile('/Users/joe/test.txt', content, { flag: 'a+' }, err => {});
```

```
r+	This flag opens the file for reading and writing	❌
w+	This flag opens the file for reading and writing and it also positions the stream at the beginning of the file	✅
a	This flag opens the file for writing and it also positions the stream at the end of the file	✅
a+	This flag opens the file for reading and writing and it also positions the stream at the end of the file
```
