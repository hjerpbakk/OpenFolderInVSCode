# OpenFolderInVSCode

A macOS Automator service, `Open in Visual Studio Code.workflow`, that opens a Finder folder in VS Code through the `code` shell command. There is no build, test or CI.

## Notes

- The logic lives in `Open in Visual Studio Code.workflow/Contents/document.wflow`. Edit the workflow in Automator, not the XML by hand. See the README for the edit instructions.
- The bundle is code signed (`_CodeSignature/`), so changes outside Automator can invalidate it.
