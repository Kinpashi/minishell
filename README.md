Unix Shell (minishell)
**Goal:** Demonstrate your understanding of OS processes, signals, and system calls.

```markdown
# minishell
A custom Unix shell implementation written in C, mirroring core bash functionality.

## Features
* **Process Management:** Supports forking, executing external binaries, and wait/waitpid handling[cite: 1].
* **Redirections:** Implemented support for `<`, `>`, `>>` and pipe `|` operators[cite: 1].
* **Parsing:** Robust command-line parsing to handle arguments, quotes, and environment variables[cite: 1].
* **Signals:** Proper handling of `Ctrl+C`, `Ctrl+D`, and `Ctrl+\` to ensure a stable user experience[cite: 1].

## Build
```bash
git clone <repository-url>
cd minishell
make
./minishell
