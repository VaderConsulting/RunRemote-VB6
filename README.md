# RunRemote

VB6 Run Remote tool (`RunRemote.exe`) that lists target servers and copies deployment/script packages from UNC sources onto each host (WMI `Win32_Process` helpers in `modExec` for remote execute/kill; Task Scheduler reference). Distinct from the later VB.NET Remoting.Common RunRemote repo. Open `RunRemote.vbp` in the VB6 IDE.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `RunRemote` (`RunRemote.vbp`) | VB6 | WinForms exe | Copy scripts/packages to remote servers and run remote processes. |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `RunRemote.vbp`

## Requirements

- Visual Basic 6.0 IDE

## Attribution and provenance

Working copy from Dave Robinson's OneDrive Historical Dev folder `VB/RunRemote`.
Company names in `.vbp` files: Freelance.

## License

MIT © 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
