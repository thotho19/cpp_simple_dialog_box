# cpp_simple_dialog_box

1. Create **resource.H** file containing
    - Macro definition of the all used objects
2. Create **resource.RC** file containing
    - Include the resource.H file
    - Define Window Menus
    - Define Window ACCELERATORS
    - Define window Dialog
3. Create **main.cpp** file
    - Call the required libraries 
    - Call **WinMain()** function with the required configuration
    - Call **WindowFunc()** for message handling
    - Call **DialogFunc()** with specific message listening
