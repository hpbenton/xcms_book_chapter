# XCMS Book Chapter

This is the code to go with the XCMS book chapter 2019

---------------------
There are two workflows in XCMS, the original workflow and the updated workflow. Both of the workflows have their own R notebooks with code explainations of each section.

To First clone the repository :
```{bash}
git clone https://github.com/hpbenton/xcms_book_chapter.git xcmsBook
cd xcmsBook
```

Data is contained inside zip files. Each file has been independantly zipped up. On linux based system users can run the following code after cloneing the repository.

```{bash}
find . -name "*.zip" | xargs -P 5 -I fileName sh -c 'unzip -o -d "$(dirname "fileName")/$(basename -s .zip "fileName")" "fileName"'
```
You can then run the R notebook in RStudio by clicking on the Rproj file.

--------------------
Scripps Research Institute

H. Paul Benton
