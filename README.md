<p align="center">
  <img src="https://img.shields.io/badge/103_%2F_100-004d40?label=Final%20Grade&labelColor=151515&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIGhlaWdodD0iMjRweCIgdmlld0JveD0iMCAwIDI0IDI0IiB3aWR0aD0iMjRweCIgZmlsbD0iI0ZGRkZGRiI+PHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPjxwYXRoIGQ9Ik0xMiAxNy4yN0wxOC4xOCAyMWwtMS42NC03LjAzTDIyIDkuMjRsLTcuMTktLjYxTDEyIDIgOS4xOSA4LjYzIDIgOS4yNGw1LjQ2IDQuNzNMNS44MiAyMXoiLz48L3N2Zz4=" />
  <img src="https://img.shields.io/badge/C-fe428e?logo=C&label=Language&labelColor=151515" />
  <img src="https://img.shields.io/badge/Passing-brightgreen?logo=42&label=Norminette&labelColor=151515" />
  <img src="https://img.shields.io/badge/Custom%20libft-004d40?logo=GitHub&label=Library&labelColor=151515" />
</p>

# 🐚 minishell – Custom UNIX Shell

## 📖 Overview
	
**Minishell** is a group project developed at **42 Pari**s that consists of building a simplified UNIX shell in C, inspired by Bash.
The goal is to implement the core mechanisms of a command-line interpreter through rigorous parsing, while gaining a deeper understanding of processes, signals, redirections, and pipes.

This project strengthened our knowledge in **system programming, process management, and UNIX internals.**
	
### Features:
- 🔹 **Command execution**: Run shell commands with ease.
- 🔹 **Pipe management**: Link commands together for streamlined output processing.
- 🔹 **Signal handling**: Manage signals effectively within the shell environment.
- 🔹 **Process forking**: Create child processes to execute commands.
- 🔹 **Error handling**: Robust mechanisms to handle errors gracefully.

See subject [here](https://github.com/uninstall-lea/minishell/blob/master/subject/en.subject.pdf)
	
## 🛠️ Installation & Setup
	
To get started, follow these steps to set up and run the project:
	
1. **Clone the repository**:
   ```bash
   git clone https://github.com/uninstall-lea/minishell.git
   cd minishell
   make
   ```
	   
2. **Run the shell**:
   ```bash
   ./minishell
   ```
	
## 🔍 Technologies Used

- C : Core language.
- UNIX System Calls : fork, execve, pipe, dup2, waitpid, signal.
- Custom Libft : Reusable library with custom implementations of standard functions.	
	

Thank you for checking out minishell! 🌟
