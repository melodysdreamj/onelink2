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
  ActivationCondition: 
    type: "onStart"
  ownInstance: "project1_own" # this is the instance where the script runs
  Parameters:
    parameter1: |
        value1
        value1 continued
    parameter2: |
        value2
        value2 continued

- Link: https://www.link.com
  ActivationCondition: 
    type: "onStart"
  ownInstance: "project2_own"
  Parameters:
    parameter1: |
        value3`
        value3 continued
    parameter2: |
        value4
        value4 continued

- Link: https://www.link.com
  ActivationCondition: 
    type: "onPatternMatch"
    value: "specific string pattern"
    targetInstance: "project2" # this instance is monitored for the pattern condition
  ownInstance: "project3_own"
  Parameters:
    parameter1: |
        value1
        value1 continued
    parameter2: |
        value2
        value2 continued

- Link: https://www.link.com
  ActivationCondition: 
    type: "onPatternMatch"
    value: "another specific string pattern"
    targetInstance: 
  ownInstance: "project4_own"
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