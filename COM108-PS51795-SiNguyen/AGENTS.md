# AGENTS.md

## Project overview
This repository is a small C programming lab for COM108-PS51795-SiNguyen. The codebase is intentionally minimal, with most work concentrated in the `lab1` folder.

## Working conventions
- Keep programs small, clear, and compatible with standard GCC compilation.
- Prefer straightforward C code over extra abstractions or tooling.
- Match the assignment's required output and formatting exactly.
- Preserve Vietnamese text as needed when the exercise asks for it.

## Build and run workflow
From the repository root:

```bash
gcc lab1/Bai1_HelloC.c -o lab1/Bai1_HelloC
./lab1/Bai1_HelloC
```

From the `lab1` directory:

```bash
gcc Bai1_HelloC.c -o Bai1_HelloC
./Bai1_HelloC
```

## Common pitfalls
- `main` must be declared correctly, typically as `int main(void)` or `int main()`.
- Every function call needs a terminating semicolon.
- Watch for mismatched parentheses, braces, and quotes.
- The project is a teaching repo; avoid unnecessary framework setup or broad refactors.

## Key files
- [README.md](README.md): repository overview
- [lab1/Bai1_HelloC.c](lab1/Bai1_HelloC.c): current C lab exercise
