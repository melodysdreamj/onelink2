## Description & How to use
A brief description of the script. and how to use this script.

## Sample Link
OneClickAll Link

## Config
```yaml
type: library # plugin, application
project_folder_name: Test # only application type use this
document_version: v1 # do not edit this. this is for document parser
```
## Imports

Initial Loading
Import 1
Import 2
Conditional Import
For each conditional import, specify the conditions, and any required variables.

Import 3

Link: Import 3
Description: A brief description of import 3 and when it's needed.
Conditions:
```yaml
pattern: "specific string pattern" # The specific pattern to trigger the import.
terminal_instance: "new" # 'current' or 'new'. Specifies whether to continue on the current terminal instance or create a new one.
```
Variables:
```yaml
variable1: "value1"
variable2: "value2"
```
Import 4

Link: Import 4
Description: A brief description of import 4 and when it's needed.
Conditions:
```yaml
pattern: "another specific string pattern"
terminal_instance: "current"
```
Variables:
```yaml
variable1: "value3"
variable2: "value4"
```
## Shell Script Code

MacOS
```bash

Code to run this script on MacOS
```

Windows
```powershell

Code to run this script on Windows
```

Linux
```bash

Code to run this script on Linux
```

## User Input Format
```
(description)

--- parameter ---
(define parameter)
```

## Authors
[AuthName](github link), ...