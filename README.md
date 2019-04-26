- [the-rust-programming-language](#the-rust-programming-language)
  - [Notes](#notes)

# the-rust-programming-language

"The Rust Programming Language" exercises.

## Notes

Useful save and run plugin for visual studio code:

```json
"saveAndRun": {
    "commands": [
        {
            "match": "\\.rs$",
            "cmd": "echo 'Formatting ${fileBasename}... ' && rustfmt ${fileBasename}",
            "useShortcut": false,
            "silent": true
        }
    ]
}
```