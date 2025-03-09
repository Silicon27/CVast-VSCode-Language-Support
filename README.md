# CVast Language Support 

![CVast Logo](images/logo.png) <!-- Add your logo here -->

VS Code extension for the CVast programming language with syntax highlighting, error checking, and language server support.

## Features

- **Syntax Highlighting**  
  Supports all CVast keywords, types, and operators.

- **Error Diagnostics** 🔴  
  Real-time red squiggles for type mismatches and syntax errors.

- **Code Navigation**  
  Go-to-definition and namespace resolution.

- **Language Server**  
  Auto-completion and parameter hints.

## Requirements

- C++ Build Tools:
  ```bash
  # Linux/macOS
  sudo apt install build-essential cmake
  
  # Windows
  choco install mingw cmake
  ```

## Extension Settings

```jsonc
{
  "cvast.enableLanguageServer": true,
  "cvast.parserPath": "./bin/cvast_parser"
}
```

## Known Issues

- Requires separate parser binaries per platform
- Namespace resolution limitations

## Release Notes

### 1.1.0
- Added Windows support
- Improved error recovery

### 1.0.0
- Initial release with core features

---

## Development

```bash
# Build from source
git clone https://github.com/Silicon27/ICVast.git
cd ICVast
mkdir build && cd build
cmake .. && make
```

**Happy Coding with CVast!** 🚀