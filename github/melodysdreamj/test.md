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
    Test1
  Parameters:
    parameter1: |
        (default value of parameter1)
    parameter2: |
        (default value of parameter2)

Script Imports:
- Link: https://github.com/onelink-is-all-you-need/onelink-is-all-you-need/blob/main/github/melodysdreamj/test2.md
  ActivationCondition: 
    type: "onStart"
  TerminalID: "project1_own" # this is the instance where the script runs
  Parameters:
    parameter1: |
        value1
        value1 continued
    parameter2: |
        value2
        value2 continued

- Link: https://github.com/onelink-is-all-you-need/onelink-is-all-you-need/blob/main/github/melodysdreamj/test3.md
  ActivationCondition: 
    type: "onStart"
  TerminalID:
  Parameters:
    parameter1: |
        value3
        value3 continued
    parameter2: |
        value4
        value4 continued

- Link: https://github.com/onelink-is-all-you-need/onelink-is-all-you-need/blob/main/github/melodysdreamj/test4.md
  ActivationCondition: 
    type: "onPatternMatch"
    value: "specific string pattern"
    targetTerminalID: "project2" # this instance is monitored for the pattern condition
  TerminalID: "project3_own"
  Parameters:
    parameter1: |
        value1
        value1 continued
    parameter2: |
        value2
        value2 continued

- Link: https://github.com/onelink-is-all-you-need/onelink-is-all-you-need/blob/main/github/melodysdreamj/test5.md
  ActivationCondition: 
    type: "onPatternMatch"
    value: "another specific string pattern"
    targetTerminalID: 
  TerminalID: "project4_own"
  Parameters:
    parameter1: |
        value3
        value3 continued
    parameter2: |
        value4
        value4 continued
      
- Link: https://github.com/onelink-is-all-you-need/onelink-is-all-you-need/blob/main/github/melodysdreamj/test5.md
  ActivationCondition: 
    type: "onPatternMatch"
    value: "another specific string pattern"
    targetTerminalID: 
  TerminalID: "project4_own"
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