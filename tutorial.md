# Neos Editor Commands

## Command Demo

### Spotlight Editor Element Test 1

<walkthrough-editor-spotlight spotlightId="fileMenu">
  File Menu
</walkthrough-editor-spotlight>

### Highlight Editor Element Test 2

<walkthrough-editor-spotlight spotlightId="navigator" spotlightItem="/test_directory/test_file.txt">
  spotlight test_file.txt
</walkthrough-editor-spotlight>

### Open File in Editor

<walkthrough-editor-open-file filePath="test_directory/test_file.txt">
  open test_file.txt
</walkthrough-editor-open-file>

### Select Line in Editor

<walkthrough-editor-select-line filePath="test_directory/test_file.txt"
                                startLine=1
                                startCharacterOffset=2
                                endLine=3
                                endCharacterOffset=4>
  Select Line
</walkthrough-editor-select-line>

### Select Regex in Editor

<walkthrough-editor-select-regex filePath="test_directory/test_file.txt"
                                regex="corned\sbeef">
  Select corned beef Regex
</walkthrough-editor-select-regex>

## Conclusion

We're done!
