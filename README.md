
![banner](banner.png)

# Hackerman Text, the AI-native code editor 

Hackerman Text is built on a simple principle: make typing feel instant, then stay out of your way.

Non-essential features are on-demand by default. There are no distracting squiggles.

Most things behave as you'd expect, no learning curve. Focus on a single file, or open multiple files into a single view. Every view stays in sync and always shows the latest version of your files.

Your configuration lives in plain text, so it can be version-controlled, shared across machines, or stored in the cloud.

## Simple and fast

Hackerman Text ships with built-in, native-level lexers tuned for speed. There are currently no plans to add heavier, language-aware tooling.

## Inline AI chat

Edit or delete context as plain text, or use Markdown for extra structure. Chats can be saved to disk, version controlled, and resumed later in any editor.

Powered by [Ollama](https://ollama.com/download)

## Custom bindable functions

Write your own editor commands in a small, well-defined subset of Python.

Functions hot-reload from your scripts file, show up in the function explorer, and can be bound to any key, so your custom workflows feel like built-in features.

## Intuitive key bindings

Hackerman Text uses platform-default shortcuts. No learning curve.

```
line_start          Command + Left, Control + A
line_end            Command + Right, Control + E
```

# Editor roadmap

| Done | Almost ready | TODO |
| :--- | :---         | :--- |
| Core editor features (multi-cursor, multiple selections)  | Bring your own lexer                                  | Remote development (SSH) |
| Everything as text files                                  | Support for mix-and-match LLMs (local and hosted)     | Virtual buffers for very large files (10M+ lines) |
| Multiple views, single document                           | Inline shell, eval, and AI chat                       | Sublime-like performance (on very large files) |
| Create your own themes                                    | Sublime-like performance                              |  |
| Local LLMs                                                |  |  |
| Copilot-like code completion                              |  |  |
| Project-wide search                                       |  |  |
| Keybind custom functions                                  |  |  |
| Emacs-like org mode for notes                             |  |  |
| Zero-latency typing (<10ms)                               |  |  |
| Context-aware autocomplete                                |  |  |
| Code scroller (minimap)                                   |  |  |

