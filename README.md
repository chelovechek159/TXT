# TXT
___
### 1. Create an external repository called TXT
    click create New Repository
    entered Repository name - TXT
    choose Public repo, add a Readmy file, create repo
### 2. Clone TXT repository to local machine
    git clone https://......
### 3. Inside local TXT create file `new.txt`
    cd XML
    touch new.txt
or    

    cat > new.txt
    "control + c"
### 4. Add file uder git
    git add new.txt
### 5. Commit a file
    git commit -m "new"
### 6. Push file to external GitHub repository 
    git push
or U can join 4-6 in one line

    git commit -am "newFile" && git push

### 7. Edit the contents of the `new.txt` file - write information about yourself (name, age, number of pets, future desired salary). Everything is written in TXT format
    cat >> new.txt
or

    add information in TXT format
### 8. Push changes to an external repository
    git add new.xml
    git commit -m "text"
    git push
result
>https://github.com/chelovechek159/TXT/blob/main/new.txt
### 9. Create file preferences.txt
    cat >preferences.txt
### 10. Add information about your preferences (Favorite movie, favorite series, favorite food, favorite season, country you would like to visit) to the `preferences.txt` file in TXT format
    vim preferences.txt
    add information in TXT format
result
>https://github.com/chelovechek159/TXT/blob/main/preferences.txt

### 11. Create a file `skills.txt` add information about the skills that will be studied in the course in TXT format
    cat > skills.txt
    add information in TXT format
result
>https://github.com/chelovechek159/TXT/blob/main/skills.txt

### 12. Make commit in one line
    git commit -am "text"
### 13.Send 2 files at once to an external repository
    git push

### 14. On the web interface, create a file `bug_report.txt`
    add file
    create new file
### 15. Make Commit changes (save) changes on the web interface
    add changes
    click on [Commit changes]
### 16. Modify the `bug_report.txt` file on the web interface to add a bug report in TXT format
    edit file
    write bug report in TXT format
### 17. Make Commit changes (save) changes on the web interface
    click on [Commit changes]
result
>https://github.com/chelovechek159/TXT/blob/main/bug_report.txt
### 18. Синхронизировать внешний и локальный репозиторий XML
    git pull