# Description & How to use
A brief Description of the script. and how to use this script.

## Quick Run Link
- [OneClickAll Link](http://oneclickall.com/your-script)

## Script
```yaml
Config:
  project_folder: Test # only application type use this, if plugin type, leave this blank

Shell Script Code:
  Default:
    MacOS: | # if not use this OS, leave this blank
      Code to run this script on MacOS
    Windows: | # if not use this OS, leave this blank
      Code to run this script on Windows
    Linux: | # if not use this OS, leave this blank
      Code to run this script on Linux
  ReInstall:
    MacOS: | # if not use this OS, leave this blank
      Code to run this script on MacOS
    Windows: | # if not use this OS, leave this blank
      Code to run this script on Windows
    Linux: | # if not use this OS, leave this blank
      Code to run this script on Linux
  Launch:
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
    Test5
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

Script Imports:


Document Version: v1 # do not edit this. this is for document parser

```

## Authors
[AuthName](http://oneclickall.com/your-script), ...