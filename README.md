Unix Shell (minishell)
**Goal:** Demonstrate your understanding of OS processes, signals, and system calls.

```markdown
# minishell
A custom Unix shell implementation written in C, mirroring core bash functionality.

## Features
* **Process Management:** Supports forking, executing external binaries, and wait/waitpid handling.
* **Redirections:** Implemented support for `<`, `>`, `>>` and pipe `|` operators.
* **Parsing:** Robust command-line parsing to handle arguments, quotes, and environment variables.
* **Signals:** Proper handling of `Ctrl+C`, `Ctrl+D`, and `Ctrl+\` to ensure a stable user experience.

## Build
```bash
git clone <repository-url>
cd minishell
make
./minishell
