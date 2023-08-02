# Description & How to use
A brief description of the script. and how to use this script.

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
  description: |
    (description line 1)
    (description line 2)
    (description line 3)
  parameters:
    parameter1: |
        (default value of parameter1)
    parameter2: |
        (default value of parameter2)

Script Imports:
- Link: https://www.link.com
  Trigger: 
    type: "initial"
    terminal_instance: "project1" # if current instance, leave this blank
  Parameters:
    parameter1: |
        value1
        value1 continued
    parameter2: |
        value2
        value2 continued

- Link: https://www.link.com
  Trigger: 
    type: "initial"
    terminal_instance: 
  Parameters:
    parameter1: |
        value3
        value3 continued
    parameter2: |
        value4
        value4 continued

- Link: https://www.link.com
  Trigger: 
    type: "pattern"
    value: "specific string pattern"
    terminal_instance: "project2"
  Parameters:
    parameter1: |
        value1
        value1 continued
    parameter2: |
        value2
        value2 continued

- Link: https://www.link.com
  Trigger: 
    type: "pattern"
    value: "another specific string pattern"
    terminal_instance: 
  Parameters:
    parameter1: |
        value3
        value3 continued
    parameter2: |
        value4
        value4 continued

Document Version: v1 # do not edit this. this is for document parser

```

## Authors
[AuthName](http://oneclickall.com/your-script), ...