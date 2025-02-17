
![Logo](https://media.licdn.com/dms/image/v2/D4D12AQEa_J0dinoDtA/article-cover_image-shrink_720_1280/article-cover_image-shrink_720_1280/0/1721187455024?e=2147483647&v=beta&t=OtHRrGsNAtI5sZkYV9Uu0D-Q8JAcbUYymXGepoRxwQs)

# Payload

A shellcode injector written in C# that implements several advanced evasion techniques to bypass security solutions. It uses a modular approach with a careful implementation of native Windows API calls via P/Invoke. The program can be used with a metasploit shellcode in C# format.

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


## More

- You can use ConfuserEx on the executable to make it more FUD 
- You can also study the possibility to use an XOR shellcode

![image](https://github.com/user-attachments/assets/52dcdd6f-ab22-4797-aaeb-338f99977d63)
