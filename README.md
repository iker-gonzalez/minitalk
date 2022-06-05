<h1 align="center">
	 🙊 Minitalk
</h1>

<p align="center">
	<b><i>Development repo for 42cursus' minitalk project</i></b><br>
	For further information about 42cursus and its projects, please refer to <a href="https://github.com/iker-gonzalez/42_cursus"><b>42cursus repo</b></a>.
</p>

<p align="center">
	<img alt="GitHub code size in bytes" src="https://img.shields.io/github/languages/code-size/iker-gonzalez/minitalk?color=blueviolet" />
	<img alt="Number of lines of code" src="https://img.shields.io/tokei/lines/github/iker-gonzalez/minitalk?color=blueviolet" />
	<img alt="Code language count" src="https://img.shields.io/github/languages/count/iker-gonzalez/minitalk?color=blue" />
	<img alt="GitHub top language" src="https://img.shields.io/github/languages/top/iker-gonzalez/minitalk?color=blue" />
	<img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/iker-gonzalez/minitalk?color=brightgreen" />
</p>

<h3 align="center">
	<a href="#%EF%B8%8F-about">About</a>
	<span> · </span>
	<a href="#%EF%B8%8F-usage">Usage</a>
  <span> · </span>
</h3>

---

## 🗣️ About

> The goal of this project is to create two executables: a server and a client. The client will send information (a string) to the server using UNIX signals. The server must correctly receive and interpret this information, then display it.

For detailed information, refer to the [**subject of this project**](https://github.com/iker-gonzalez/42_cursus/blob/main/_PDFs/en.subject_minitalk.pdf)

 ## 🛠️ Usage
 
 Clone the repository and run the command `make` root directory.
 
 This will create two executables: `client` and `server`.

1) By running the server executable we start up the server and it displays its process id.

2) By running the client with the process id from the server we can send strings to the server.

3) Server receives bits containing the information, translates them to characters and prints the result as a string.

#### Bonus:
1) The client can also send Unicode format characters

2) The server interprets and displays them correctly <br />
