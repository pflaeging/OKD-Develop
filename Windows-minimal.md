# Minimal setup for OKD & OpenShift

## Install

- create your `C:\Users\yourusername\Programs\`

- install VS Code as portable from: <https://code.visualstudio.com/#alt-downloads>
  - Select Windows `.zip` 64 bit
  - now you should have a `VScode-win32-x64-....zip` archive
  - extract it under `C:\Users\yourusername\Programs\VScode`
  - create `C:\Users\yourusername\programs\VScode\data` for your user settings
- install git for Windows porable from: <https://github.com/git-for-windows/git/releases/download/v2.31.1.windows.1/PortableGit-2.31.1-64-bit.7z.exe>
  - Run the exe
  - move the folder `PortableGit` to `C:\Users\yourusername\Programs\`
- install OKD Tools from your local install or from <https://github.com/openshift/okd/releases>
  - make a directory `C:\Users\yourusername\Programs\OKD``
  - and put the `oc.exe`binary in this dir


## Setting up Environment

- expand your path: `setx PATH "%PATH%;C:\Users\%USERNAME%\Programs\VSCode\;C:\Users\%USERNAME%\Programs\PortableGit\bin\;C:\Users\%USERNAME%\Programs\PortableGit\usr\bin;C:\Users\%USERNAME%\Programs\OKD"`
- ...

## Setting up VS Code

- Install the following Plugins:
  - OpenShift Extension Pack (by Red Hat)
  - Remote Development (by Microsoft)
  - Git Extension Pack
- Finish VS Code 

---

Congrats, your done!

Peter Pfläging <peter@pflaeging.net>