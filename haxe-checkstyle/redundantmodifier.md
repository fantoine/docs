---
title: Redundant Modifier
keywords: modifier, redundant
toc: false
---

Checks for redundant modifiers.

Omitting the visibility modifier usually defaults the visibility to `private` in normal classes and `pulbic` in interfaces and externs.

### Configuration

```json
{
    "type": "RedundantModifier",
    "props": {
        "enforcePublicPrivate": false,
        "severity": "INFO"
    }
}
```

### Reference

[http://haxe.org/manual/class-field-visibility.html](http://haxe.org/manual/class-field-visibility.html)