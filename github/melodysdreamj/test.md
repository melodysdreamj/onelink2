# Description & How to use
A brief Description of the script. and how to use this script.

## Quick Run Link
- [OneClickAll Link](http://oneclickall.com/your-script)

## Script
```yaml


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
    parameter3:
      Type: "Select"
      Description: "Select your country:"
      Options: 
        - "United States"
        - "Canada"
        - "South Korea"
      Default: "United States"
    parameter5:
      Type: "CheckBox"
      Description: "Agree to the terms and conditions:"
      Default: false
    parameter12:
      Type: "RangeSlider"
      Description: "Select your satisfaction level:"
      Min: 1
      Max: 10
      Default: 5
    parameter13:
      Type: "Text"
      Description: "Describe yourself:"
      Default: |
          (default value of parameter1)
  AutoInput:
    - triggerString: "specific string pattern1"  # String pattern to trigger the input
      inputStrings:                              # Array of automatic responses for the specified pattern
        - "automatic response1"
        - "automatic response2"
      targetTerminalID: "project2_terminal"  # Terminal instance ID to receive the automatic input. If left blank, it targets the current instance.
    - triggerString: "specific string pattern2"  # String pattern to trigger the input
      inputStrings:                              # Array of automatic responses for the specified pattern
        - "automatic response3"
        - "automatic response4"
      targetTerminalID:  # Terminal instance ID to receive the automatic input. If left blank, it targets the current instance.

  

Script Imports:
- Link: https://github.com/onelink-is-all-you-need/onelink-is-all-you-need/blob/main/github/melodysdreamj/test2.md
  ActivationCondition: 
    type: "onStart"
  TerminalID: "project1_own" # this is the instance where the script runs
  Parameters:
    parameter1: 
      Type: "Text"
      Description: "Describe yourself:"
      Default: |
        value1
        value1 continued
    parameter2: 
      Type: "Text"
      Description: "Describe yourself:"
      Default: |
        value2
        value2 continued
  AutoInput:
    - triggerString: "specific string pattern1"  # String pattern to trigger the input
      inputStrings:                              # Array of automatic responses for the specified pattern
        - "automatic response1"
        - "automatic response2"
      targetTerminalID: "project2_terminal"  # Terminal instance ID to receive the automatic input. If left blank, it targets the current instance.

- Link: https://github.com/onelink-is-all-you-need/onelink-is-all-you-need/blob/main/github/melodysdreamj/test3.md
  ActivationCondition: 
    type: "onStart"
  TerminalID:
  Parameters:
    parameter1: 
      Type: "Text"
      Description: "Describe yourself:"
      Default: |
        value3
        value3 continued
    parameter2: 
      Type: "Text"
      Description: "Describe yourself:"
      Default: |
        value4
        value4 continued

- Link: https://github.com/onelink-is-all-you-need/onelink-is-all-you-need/blob/main/github/melodysdreamj/test4.md
  ActivationCondition: 
    type: "onPatternMatch"
    triggerString: "specific string pattern"
    targetTerminalID: "project2" # this instance is monitored for the pattern condition
  TerminalID: "project3_own"
  Parameters:
    parameter3:
      Type: "Select"
      Description: "Select your country:"
      Options: 
        - "United States"
        - "Canada"
        - "South Korea"
      Default: "United States"
    parameter5:
      Type: "CheckBox"
      Description: "Agree to the terms and conditions:"
      Default: false
    parameter12:
      Type: "RangeSlider"
      Description: "Select your satisfaction level:"
      Min: 1
      Max: 10
      Default: 5
    parameter13:
      Type: "Text"
      Description: "Describe yourself:"
      Default: |
          (default value of parameter1)

- Link: https://github.com/onelink-is-all-you-need/onelink-is-all-you-need/blob/main/github/melodysdreamj/test5.md
  ActivationCondition: 
    type: "onPatternMatch"
    triggerString: "another specific string pattern"
    targetTerminalID: 
  TerminalID: "project4_own"
  Parameters:
    parameter1: 
      Type: "Text"
      Description: "Describe yourself:"
      Default: |
        value3
        value3 continued
    parameter2: 
      Type: "Text"
      Description: "Describe yourself:"
      Default: |
        value4
        value4 continued
      
- Link: https://github.com/onelink-is-all-you-need/onelink-is-all-you-need/blob/main/github/melodysdreamj/test5.md
  ActivationCondition: 
    type: "onPatternMatch"
    triggerString: "another specific string pattern"
    targetTerminalID: 
  TerminalID: "project4_own"
  Parameters:
    parameter1: 
      Type: "Text"
      Description: "Describe yourself:"
      Default: |
        value3
        value3 continued
    parameter2: 
      Type: "Text"
      Description: "Describe yourself:"
      Default: |
        value4
        value4 continued


Document Version: v1 # do not edit this. this is for document parser



```

## Authors
[AuthName](http://oneclickall.com/your-script), ...