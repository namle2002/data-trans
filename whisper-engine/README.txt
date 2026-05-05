Place Whisper engine runtime files in this folder for both dev and packaged builds.

Required:
- whisper-cli.exe
- all DLL files shipped with the same whisper.cpp release package

Runtime resolution order:
1) <resources>/whisper-engine/whisper-cli.exe (packaged app)
2) <app>/whisper-engine/whisper-cli.exe
3) <cwd>/whisper-engine/whisper-cli.exe
4) <project>/whisper-engine/whisper-cli.exe

Do not use main.exe (deprecated).
