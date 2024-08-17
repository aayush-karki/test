# SFML Boilerplate

This is a SFML boiler plate for visual studio.

## Download the SFML

-   Download the SFML files from this [link](https://www.sfml-dev.org/download.php) if you do not have it downloaded
-   extract the files and copy it into a stable folder.
-   open the folder and it should have the following folder structure:
    ![SFML folder structure](/sfml_boilerplate_vs/assets/sfml_folder_structure.png "SFML folder structure")
    -   bin has debug files that you need to add to your debug folder
    -   include is the folder that needs to be pointed at your project's C++ properties
    -   lib is the folder that needs to be pointed at your project's linker properties

## Things to do after creating the repo from the template:

-   your active solution platform must be x86 ![active_solution_platform](/sfml_boilerplate_vs/assets/active_solution_platform.png "active_solution_platform")
-   repoint the include and lib folder in project properties.
    -   to repoint to include folder:
        -   right click your project
        -   click on project
        -   click on c/c++
        -   click on general
        -   click on the text field of the "Additional Include Directories"
        -   click on the dropdown arrow
        -   click on edit
        -   paste the absolute path to your inlcude folder
    -   to repoint to lib folder:
        -   right click your project
        -   click on project
        -   click on linker
        -   click on general
        -   click on the text field of the "Additional Libraries Directories"
        -   click on the dropdown arrow
        -   click on edit
        -   paste the absolute path to your lib folder
-   copy the files found in the bin folder of the sfml download into the debug folder.
    -   to get the debug folder, build the solution and run it in debug mode once.
