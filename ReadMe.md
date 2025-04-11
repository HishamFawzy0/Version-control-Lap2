- How to delete a branch (Locally)

    git branch -D branch_name 

    EX: git branch -D dev


- How to delete a branch (Remotly)

    git push origin --delete branch_name

    EX: git push origin --delete dev



    -- comapare bettween Annotated Tag and lightweight Tag

    # Annotated Tag
    -Includes a message about the commit
    -Includes author & date information
    -Stored as Git object

  
    # Lightweight Tag
    -Does not include a commit message
    -Does not include author & date information
    -Does not store as Git object - Just a reference to the commit
    
    **Annotated Tag:**
```bash
git tag -a v1.0.0 -m "First stable release"
```




**Lightweight Tag:**
```bash
git tag v1.0.0
```
