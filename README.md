# StickyNotes Releases

This repository hosts the public **binary releases** of **StickyNotes** — a lightweight
sticky notes app for the Windows desktop, built with C# / WPF on .NET 10.

It does **not** contain the application source code. Only release artifacts are published here.

## Downloads

See the [Releases](../../releases) page for:

- `StickyNotes-1.3.3-win-x64.exe` — self-contained portable build (no runtime required)
- `StickyNotes-Setup-1.3.3.exe` — installer
- `SHA256SUMS.txt` — SHA-256 checksums for both executables

## Verify a download

```powershell
Get-FileHash .\StickyNotes-1.3.3-win-x64.exe -Algorithm SHA256
```

Compare the printed hash with the matching line in `SHA256SUMS.txt`.

## Requirements

Windows 10 or Windows 11, x64. The portable executable needs nothing else — no .NET install,
no administrator rights, and no network access.
