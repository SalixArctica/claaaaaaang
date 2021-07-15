# Configuring VS Code for C Development

1. Install Clang for windows. (if you're on windows) [get it here](https://llvm.org/builds/)
2. Install clang-format VS Code extension: [here](https://marketplace.visualstudio.com/items?itemName=xaver.clang-format)
3. Copy .clang-format to root of you project directory
4. add the following to your VS Code's settings.json

```
  "editor.formatOnSave": true,
  "files.eol": "\n"
```

5. Done!
