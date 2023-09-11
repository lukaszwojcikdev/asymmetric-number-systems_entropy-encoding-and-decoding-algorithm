# asymmetric-number-systems_entropy-encoding-and-decoding-algorithm
**Asymmetric Number Systems (ANS): Entropy Encoding and Decoding Algorithm in GO**

This project implements an entropy encoding and decoding algorithm using Asymmetric Number Systems (ANS) in GO. 
ANS is a data compression technique that is used in various fields such as image, audio and video compression.

# Installation
1. Download and install the GO language (if you don't have it yet, and if you already have it, you can go to the next step).

We can use the traditional method and download the appropriate GO version for your system from: `https://golang.google.cn/dl/`
or use a tool `WGET` (for windows):

Run CMD as ADMIN and type:
`wget https://golang.google.cn/dl/go1.21.1.windows-amd64.msi`

For SCOOP download manager:
`scoop install golang`

For CHOCOLATEY download manager:
`choco install golang`

2. To install the project, execute the command below in the terminal:

# Run and Build
After installing the project, compile and run it in your development environment or from the command line:

`go build anseeda.go`
or
`go run anseeda.go`

# Usage
Windows: `anseeda.exe -e file.txt` [`-e` for encoding or `-d` for decoding]
Linux  : `./anseeda -e file.txt` 

# Documentation
Project documentation can be found in the DOCUMENTATION.md. It contains detailed implementation information, data structures, and usage examples.

# Examples
The examples folder contains several examples of using the ANS algorithm in various scenarios. You can run them by executing the command:

`go run examples/example1.go`

# Contribution
If you have any ideas, comments or found a bug, please feel free to contribute via pull request.

# License
This project is licensed under [[MIT](https://opensource.org/license/mit/)].

Details can be found in the file [[LICENSE](https://github.com/lukaszwojcikdev/ogonki/blob/main/LICENSE)].

# Author
The author of the program is Łukasz Wójcik [kontakt(at)lukaszwojcik.eu]
