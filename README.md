# VisMotive-BuiltBinary

<br/>
I provide built files of VisMotove essential componenets (Core APIs and certain essential module DLLs). Header and library files are provided for simple developement of VisMotive-based applications. Someday, I will open all source codes of these DLL files with build environments. The only problem for this is .. time (I am so busy for other projects and paper writings..). If anyone has experience this release work, please help me up!    

### Platforms:
- Windows PC Desktop (x64)

### Requirements:
- Windows 10
- GPU that supports DirectX 11 (feature level 3) or higher (for my rendering engine module https://github.com/korfriend/HybridRenderingEngine)

### Build Environments
Current build environment assumes the following structure of the developement folders. The DLL files are supposed to place X64_Debug/X64_Release. To be clear your folder structure should be something quite similar to:

    yourdevfolder/
     |
     ├──bin (build target folders)
     │   ├──X64_Debug (copy debug dlls here)
     │   └──X64_Release (copy release dlls here)
     └──External Projects
         ├──project1 (e.g., https://github.com/korfriend/LocalIsosurfaceModeler/)
         ├──project2
         ├──...
         └──...

### What Next?!
- Sample code projects for "get started" will be made here.
