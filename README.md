>*"An idiot admires complexity, a genius admires simplicity."*
>Terry A. Davis (1969 - 2018)

## About the Project
This project is an homage to the electrical engineer, computer programmer and outsider artist Terrence Andrew Davis. My goal is to modernize HolyC, while respecting his philosophy, simple and fast. I do not intend to gain money or fame from this. This is a study in Computer Science that wishes to honor his legacy.

Terry's trajectory is a painful reminder of the importance of mental health awareness and support, especially regarding severe disorders such as schizophrenia. 

## Roadmap 

### Phase 1: Core Foundation
- [ ] Lexer and AST Parser for HolyC syntax.
- [ ] Basic primitive types support (`I8`, `I16`, `I32`, `I64`, `U8`, `U16`, `U32`, `U64`, `F64`, `Bool`).
- [ ] Direct string printing (`"Hello World\n";`).
- [ ] Function declarations and syntax relaxed calls (functions without parenthesis).

### Phase 2: System Integration & Modernization
- [ ] Cross-platform support (Linux, Windows, macOS).
- [ ] C-ABI compatibility (importing and calling external C/C++ functions).
- [ ] Basic memory management (`MAlloc` / `Free` semantics).
- [ ] Modules and Namespace system (preventing global scope pollution).

### Phase 3: Advanced Features & Low-Level Control
- [ ] Inline Assembly support (`asm {}`).
- [ ] JIT (Just-In-Time) compilation backend (or LLVM integration).
- [ ] Basic graphics/terminal buffer manipulation (inspired by DolDoc / TempleOS graphics).

### Phase 4: Tooling & Documentation
- [ ] Command Line Interface (CLI) driver (`holyc++ run main.hc`).
- [ ] Language documentation and syntax specification guide.
- [ ] Code examples and standard library snippets.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
