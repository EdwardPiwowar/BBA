# Bridge Bot Analyzer (BBA)

<p align="center">
  <img src="BBALogo.jpg" alt="Bridge Bot Analyzer Logo" width="300">
</p>

<p align="center">
  <strong>Bridge Bot Analyzer</strong> is a bridge analysis application powered by <strong>EPBot</strong>, designed for evaluating bidding, play decisions, and bridge bot performance.
</p>

---

## Features

- Contract bridge deal analysis
- Integration with the EPBot engine
- Support for multiple architectures:
  - x86
  - x64
  - ARM64
- Native Windows executable
- DLL and COM library support
- Easy deployment and standalone usage

---

## Repository Contents

The repository contains:

- Native Windows application binaries
- EPBot engine libraries for multiple platforms and CPU architectures
- Runtime libraries for:
  - Windows
  - Linux
  - macOS
  - WebAssembly (WASM)
- COM type libraries (`.tlb`)
- Distribution archives
- Configuration and support files
- Project resources including the application logo

The main BBA application is distributed as a native Windows executable, while the included EPBot libraries support cross-platform integration and experimentation.

---|---|
| `BBA.exe` | Main application executable |
| `BBA.zip` | Compressed distribution package |
| `EPBot64.dll` | EPBot library for 64-bit systems |
| `EPBot86.dll` | EPBot library for 32-bit systems |
| `EPBotARM64.dll` | EPBot library for ARM64 systems |
| `EPBot64.tlb` | COM type library for 64-bit EPBot |
| `EPBot86.tlb` | COM type library for 32-bit EPBot |
| `EPBotARM64.tlb` | COM type library for ARM64 EPBot |
| `BBALogo.jpg` | Project logo |

---

## System Requirements

- Windows 10 or Windows 11
- Supported architectures:
  - x86
  - x64
  - ARM64
- Microsoft Visual C++ Redistributable (if required)

---

## Installation

1. Download the latest release package.
2. Extract `BBA.zip`.
3. Make sure all required DLL files are located in the same directory as `BBA.exe`.
4. Launch the application.

---

## Running the Application

```bash
BBA.exe
```

---

## Project Website

Official website:

- https://sites.google.com/view/bbaenglish

---

## Bug Reports & Suggestions

If you find a bug or want to suggest an improvement:

1. Open the **Issues** tab
2. Create a new issue
3. Describe the problem and steps to reproduce it

---

## Releases

All published versions are available in the repository **Releases** section.

---

## License

No explicit license is currently provided in this repository.

If you intend to use this software commercially or redistribute it, please contact the repository owner.

---

## Author

Developed and maintained by Edward Piwowar.

GitHub Repository:

- https://github.com/EdwardPiwowar/BBA

---

Bridge Bot Analyzer is a tool created for contract bridge enthusiasts, allowing advanced bridge analysis and experimentation with bridge-playing algorithms.

