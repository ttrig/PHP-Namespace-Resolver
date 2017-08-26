# PHP Namespace Resolver

PHP Namespace Resolver can import, expand and sort your namespaces.

## Commands

Search these commands by the title on command palette.

```json
[
    {
        "title": "Import Namespace",
        "command": "namespaceResolver.import"
    },
    {
        "title": "Expand Namespace",
        "command": "namespaceResolver.expand"
    },
    {
        "title": "Sort Namespaces",
        "command": "namespaceResolver.sort"
    }
]
```

## Keybindings

You can override these default keybindings on your `keybindings.json`.

```json
[
    {
        "command": "namespaceResolver.import",
        "key": "f1"
    },
    {
        "command": "namespaceResolver.expand",
        "key": "f2"
    },
    {
        "command": "namespaceResolver.sort",
        "key": "f3"
    }
]
```

## Settings

```json
[
    "namespaceResolver.autoSort": {
        "type": "boolean",
        "default": true,
        "description": "Auto sort use statements by line length after imports."
    },
    "namespaceResolver.leadingSeparator": {
        "type": "boolean",
        "default": true,
        "description": "Expand with leading namespace separator."
    },
    "namespaceResolver.messagesOnStatusBar": {
        "type": "boolean",
        "default": false,
        "description": "Show messages on status bar."
    }
]
```

## Context Menu

```json
[
    {
        "command": "namespaceResolver.import",
        "group": "navigation",
        "when": "!editorHasSelection"
    },
    {
        "command": "namespaceResolver.expand",
        "group": "navigation"
    },
    {
        "command": "namespaceResolver.sort",
        "group": "navigation"
    }
]
```

## Author

- [Mehedi Hassan](https://www.facebook.com/MehediDracula)
- [@MehediDracula](https://twitter.com/MehediDracula)

## License

[MIT](LICENSE) License.

Copyright (c) 2017 Mehedi Hassan