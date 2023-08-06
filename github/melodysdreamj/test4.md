# Description & How to use
A brief Description of the script. and how to use this script.

## Quick Run Link
- [OneClickAll Link](http://oneclickall.com/your-script)

## Script
```yaml
Config: 
  project_folder: Test # only application type use this, if plugin type, leave this blank

Shell Script Code:
  MacOS: | # if not use this OS, leave this blank
    Code to run this script on MacOS
  Windows: | # if not use this OS, leave this blank
    Code to run this script on Windows
  Linux: | # if not use this OS, leave this blank
    Code to run this script on Linux
    
User Input Format:
  Description: |
    (Description line 1)
    (Description line 2)
    (Description line 3)
    Test4
  Parameters:
    parameter1: 
      Type: "Text"
      Description: "Describe yourself:"
      Default: |
        (default value of parameter1)
    parameter2: 
      Type: "Text"
      Description: "Describe yourself:"
      Default: |
        (default value of parameter2)
  AutoInput:
    - triggerString: "specific string pattern1"  # String pattern to trigger the input
      inputStrings:                              # Array of automatic responses for the specified pattern
        - "automatic response1"
        - "automatic response2"
      targetTerminalID: "project2_terminal"  # Terminal instance ID to receive the automatic input. If left blank, it targets the current instance.

Script Imports:

Document Version: v1 # do not edit this. this is for document parser

```

## Authors
[AuthName](http://oneclickall.com/your-script), ...