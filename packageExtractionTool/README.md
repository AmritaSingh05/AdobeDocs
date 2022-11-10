## Package Extraction Tool

The package extraction tool allows extraction of multiple packages via multi-selection in Adobe Campaign. It is accessible via an icon in the action menu of the package definition screen.   

The tool generates a zip file that can be extracted and can be used to install to a higher environment.
The tool performs the « separation » of packages in source files to make it easier to read. 

It generates 2 folders: 
1. Packages: As extracted from Adobe campaign (without modification) 
2. Sources: 
    a) One folder by package (= feature),
    b) One subfolder by object type,
    c) One object by file.
