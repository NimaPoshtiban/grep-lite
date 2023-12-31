# Grep-lite
A lite version of ```grep``` written in Rust

## Usage
```
USAGE:
    grep-lite <pattern> <input>

searching in a file:
    grep-lite -- pattern -- filename
    
searching from stdin:
    "input from stdin" | grep-lite -- pattern -- -
```