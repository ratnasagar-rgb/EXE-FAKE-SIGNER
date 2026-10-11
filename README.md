# fake Signature Simulator — Educational Project

An educational Windows utility for learning about executable file paths, digital signatures, and Authenticode verification.

> **Educational use only:** This project must not be used to impersonate Microsoft Corporation, mislead users about a publisher, or bypass Windows security protections. A simulated signature is not a genuine Microsoft digital signature.

## Features

- Windows executable path input
- Demonstration of signature-related concepts
- Educational testing with executable files
- Example usage with full Windows file paths

## Download

1. Open the repository's **Releases** page.
2. Download the latest available executable (`.exe`).
3. Save it to a folder of your choice.
4. Check the file's source before running it.

## How to Use

### Method 1: Enter the full file path

1. Download the tool.
2. Run it with the permissions required by your specific build. Administrator privileges should only be used when genuinely necessary.
3. Copy the full path of the executable you want to inspect.
4. Paste the path into the tool.
5. Follow the on-screen instructions to run the educational demonstration.

**Example path:**
```text
C:\Users\YourName\Desktop\TestApp.exe
```

Replace `YourName` and `TestApp.exe` with the actual Windows username and executable filename.<img width="997" height="598" alt="image" src="https://github.com/user-attachments/assets/038ad49c-7488-40ca-a130-a98f89bcce5e" />



### Method 2: Keep the files in the same folder

1. Create a folder, for example:
   ```text
   C:\SignatureLab\
   ```

2. Place the educational tool and your test executable inside it.

3. Copy the full path of the test executable.

4. Enter that path into the tool.

**Example:**
```text
C:\SignatureLab\SignatureTool.exe
C:\SignatureLab\TestApp.exe
```

Enter the path to `TestApp.exe`, not the path to the tool itself.

##
<img width="1036" height="627" alt="image" src="https://github.com/user-attachments/assets/517c469b-ea27-4693-8ed8-aa00f861a9ca" />
v<img width="927" height="650" alt="image" src="https://github.com/user-attachments/assets/d2890367-06b9-4be4-8e41-ff2241c09377" />



## Important Security Notice

- Never use this project to impersonate a software publisher.
- Never assume that a displayed Microsoft Corporation name proves authenticity.
- Do not disable antivirus or Windows security protections to run the program.
- Only test files that you own or have permission to examine.

## Disclaimer

This project is intended for educational purposes and authorized security testing. It is not affiliated with or endorsed by Microsoft Corporation.
Important Notice About Reverse Engineering

Please do not use IDA, IDA Pro, or similar reverse-engineering tools to inspect or analyze this executable.

The executable is distributed for educational purposes only.

If you need to understand how the project works, request the source code from the author.

If you encounter any issues or need clarification, contact the author.

Note: This notice expresses the author's request. It does not technically prevent reverse engineering or guarantee that the executable's code cannot be inspected.
