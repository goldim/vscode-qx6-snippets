# qooxdoo v6 Snippets
This extension for Visual Studio Code adds snippets for qooxdoo framework.

## Usage
Type a part of the keywords in snippet e.g., "construct" and press enter.

```javascript
// Creates a for loop snippet
construct: function() {
    this.base(arguments);
}, 
```

Alternatively, one can also just press <kbd>Ctrl</kbd> + <kbd>Space</kbd> (works on Windows, Linux, or Mac) to access the available snippets in the editor.

## Snippets

| Snippet               | Purpose                                       |
| ----------------------| ----------------------------------------------|
| `qx.Interface.define` | interface declaration                         |
| `qx.Class.define`     | class declaration                             |
| `qx.Mixin.define`     | mixin declaration                             |
| `extend`              | extend word, default `qx.core.Object`         |
| `implement`           | implement interface                           |
| `include`             | include mixin                                 |
| `type`                | class type: `abstract`, `static`, `singleton` |
| `construct`           | class constructor                             |
| `destruct`            | class destructor                              |
| `events`              | event section                                 |

## Installation

1. Install Visual Studio Code 0.10.1 or higher
2. Launch VS Code
3. From the command palette `Ctrl`+`Shift`+`P` (Windows, Linux) or `Cmd`+`Shift`+`P` (OSX)
4. Type `ext install` or just simply select `Install Extension`
5. Choose the extension - Cpp Snippets
6. Relaunch VS Code


*Suggestions for improvement are welcome.*