
# Payload

A shellcode injector written in C# that implements several advanced evasion techniques to bypass security solutions. It uses a modular approach with a careful implementation of native Windows API calls via P/Invoke.


## Features

- Shellcode injection via suspended process creation
- Dynamic loading of DLLs and resolution of functions
- Multiple detection evasion techniques (VM evasion ...)
- Complete implementation of the necessary Windows structures

## Evasion Features (Main)

- Testing web connectivity to an invalid URL
- Checking file operations
- Testing access to system processes
- Checking system boot time
- CPU load test via intensive loop
- Controlling the size of working memory
- Checking the executable name
- Testing for large amount of memory allocation
- Mutex checking
- NUMA Allocation Test
## Usage

```
Payload.exe
```

