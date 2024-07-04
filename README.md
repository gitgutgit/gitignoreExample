# gitignoreExample


(See gitignoreexample.png. The white items are listed as added in git, while the grey items are ignored.)
## How to Use .gitignore

There are four .gitignore files in this repository:

1. .gitignore in the main folder

    Unnecessaryfolder -> Ignore the Unnecessaryfolder.
    
    Tfolder/img -> Ignore the img folder inside Tfolder. (Note the difference from the below .gitignore files)



2. .gitignore in Pfolder

    img -> Ignore the img folder (Note that it is not Pfolder/img because this .gitignore is already inside the Pfolder).

3. .gitignore in Nfolder

    img -> Ignore the img folder (Same as above).


4. .gitignore in Jfolder

    img_name_strange -> Ignore the img_name_strange folder (Same as above but with a different name).
