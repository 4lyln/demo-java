# Java Hello World Project

This is a simple Java Hello World program.

## How to Run

1. **Install Java (JDK) on macOS:**
   - Open Terminal and run:
     ```sh
     brew install openjdk
     ```
   - After installation, add the following to your shell profile (e.g., `~/.zshrc`):
     ```sh
     export PATH="/opt/homebrew/opt/openjdk/bin:$PATH"
     export CPPFLAGS="-I/opt/homebrew/opt/openjdk/include"
     ```
   - Restart your terminal or run `source ~/.zshrc`.

2. **Compile and Run:**
   - Navigate to the folder containing `Main.java`:
     ```sh
     cd /Users/allynflores/Downloads/Fall25/CS 2400
     javac Main.java
     java Main
     ```

You should see:
```
Hello, World!
```
