#  Linux-Resource-Monitor

## About
Content here

## ncurses
[ncurses](https://www.gnu.org/software/ncurses/) is a library that facilitates text-based graphical output in the terminal. This project relies on ncurses for display output.

Install ncurses within your own Linux environment to run this project: `sudo apt install libncurses5-dev libncursesw5-dev`

## Make
This project uses [Make](https://www.gnu.org/software/make/). The Makefile has four targets:
* `build` compiles the source code and generates an executable
* `format` applies [ClangFormat](https://clang.llvm.org/docs/ClangFormat.html) to style the source code
* `debug` compiles the source code and generates an executable, including debugging symbols
* `clean` deletes the `build/` directory, including all of the build artifacts

## How to Use:
Step 1: \
Clone the repository by following the below given step:
```
git clone https://github.com/Pranavchiku/Linux-Resource-Monitor.git
```
Step 2: \
Open the project in an IDE and execute the following command in console to get the required dependencies:
```
make build
```
Step 3: \
Run the project by executing the below piece of code in console:
```
./build/monitor
```
## Collaborators:
| Name | Year | Branch|
| ------------- | ------------- | ------------- |
| Harshita Kalani (B20CS019)  | PreFinal  | CSE |
| Ramanpreet (B20CS052) | PreFinal | CSE |
| Shivi Mathur (B20CS067) | PreFinal | CSE |
| Pranav Goswami (B20CS016) | PreFinal  | CSE |
