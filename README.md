Export CP

Tool for exporting a file or directory from one terminal to another without having to copy paths.

Export file to buffer:
```
ecp file-to-copy
```

Import buffer to current working directory:
```
ecp
```

Details:
When exporting writes the full path to the file to "\~/.ecp/file".

When importing copies the file path stored in "\~/.ecp/file" to the current working directory.
