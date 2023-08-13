# Script Name

A brief Description of the script. and how to use this script.

## Quick Run Link

- [OneClickAll Link](http://oneclickall.com/your-script)

## Script

```yaml
Config: 
  ProjectID: "Test" # only application type use this, if plugin type, leave this blank
  DocumentVersion: "v1" # do not edit this. this is for document parser

ScriptCodes:
  MacOS: | # if not use this OS, leave this blank
    Code to run this script on MacOS
    Code Line 2
  Windows: | # if not use this OS, leave this blank
    Code to run this script on Windows
    Code Line 2
  Linux: | # if not use this OS, leave this blank
    Code to run this script on Linux

UserInputForm:
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
        (default value of parameter2)

TriggerInput:
  - TriggerPatternString: "specific string pattern1"  # String pattern to trigger the input
    TargetTerminalID: # Terminal instance ID to receive the automatic input. If left blank, it targets the current instance.
    AutoInput:
      MacOS: | # if not use this OS, leave this blank
        Code to run this script on MacOS
      Windows: | # if not use this OS, leave this blank
        Code to run this script on Windows
      Linux: | # if not use this OS, leave this blank
        Code to run this script on Linux

  - TriggerPatternString: "specific string pattern2"  # String pattern to trigger the input 
    TargetTerminalID: # Terminal instance ID to receive the automatic input. If left blank, it targets the current instance.
    AutoInput:
      MacOS: | # if not use this OS, leave this blank
        Code to run this script on MacOS
      Windows: | # if not use this OS, leave this blank
        Code to run this script on Windows
      Linux: | # if not use this OS, leave this blank
        Code to run this script on Linux

ImportScript:
  - Link: "https://raw.githubusercontent.com/melodysdreamj/OneClickAll/master/Scripts/ScriptName.py"
    TriggerPatternString: "specific string pattern1"  # String pattern to trigger the input
    TerminalID: # Terminal instance ID to receive the automatic input. If left blank, it targets the current instance.
    UserInputFormParameters:
      parameter3: "Select your country:"
      parameter5: true
      parameter12: 5
      parameter13: |
        (default value of parameter1)
        
    PrepareBeforeRun:
      MacOS: | # if not use this OS, leave this blank
        Code to run this script on MacOS
      Windows: | # if not use this OS, leave this blank
        Code to run this script on Windows
      Linux: | # if not use this OS, leave this blank
        Code to run this script on Linux
        
    TriggerInput:
      - TriggerPatternString: "specific string pattern1"  # String pattern to trigger the input
        TargetTerminalID: # Terminal instance ID to receive the automatic input. If left blank, it targets the current instance.
        AutoInput:
          MacOS: | # if not use this OS, leave this blank
            Code to run this script on MacOS
          Windows: | # if not use this OS, leave this blank
            Code to run this script on Windows
          Linux: | # if not use this OS, leave this blank
            Code to run this script on Linux
    
      - TriggerPatternString: "specific string pattern2"  # String pattern to trigger the input 
        TargetTerminalID: # Terminal instance ID to receive the automatic input. If left blank, it targets the current instance.
        AutoInput:
          MacOS: | # if not use this OS, leave this blank
            Code to run this script on MacOS
          Windows: | # if not use this OS, leave this blank
            Code to run this script on Windows
          Linux: | # if not use this OS, leave this blank
            Code to run this script on Linux
            
  
  - Link: "https://raw.githubusercontent.com/melodysdreamj/OneClickAll/master/Scripts/ScriptName2.py"
    TriggerPatternString: "specific string pattern1"  # String pattern to trigger the input
    TerminalID: # Terminal instance ID to receive the automatic input. If left blank, it targets the current instance.
    UserInputFormParameters:
      parameter3: "Select your country:"
      parameter5: true
      parameter12: 5
      parameter13: |
        (default value of parameter1)
        
    PrepareBeforeRun:
      MacOS: | # if not use this OS, leave this blank
        Code to run this script on MacOS
      Windows: | # if not use this OS, leave this blank
        Code to run this script on Windows
      Linux: | # if not use this OS, leave this blank
        Code to run this script on Linux
        
    TriggerInput:
      - TriggerPatternString: "specific string pattern1"  # String pattern to trigger the input
        TargetTerminalID: # Terminal instance ID to receive the automatic input. If left blank, it targets the current instance.
        AutoInput:
          MacOS: | # if not use this OS, leave this blank
            Code to run this script on MacOS
          Windows: | # if not use this OS, leave this blank
            Code to run this script on Windows
          Linux: | # if not use this OS, leave this blank
            Code to run this script on Linux
    
      - TriggerPatternString: "specific string pattern2"  # String pattern to trigger the input 
        TargetTerminalID: # Terminal instance ID to receive the automatic input. If left blank, it targets the current instance.
        AutoInput:
          MacOS: | # if not use this OS, leave this blank
            Code to run this script on MacOS
          Windows: | # if not use this OS, leave this blank
            Code to run this script on Windows
          Linux: | # if not use this OS, leave this blank
            Code to run this script on Linux
          

```
























































