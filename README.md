delete branches
    local:
        git branch -d dev 
        git branch -d test
    remote :
        git push origin --delete dev 
        git push origin --delete test
checkout branches :
    git checkout master 
    . --git checkout 
list tags :
    git tag 
delete tags :
    local :
        git tag -d v1.7
    remote :
        git push origin --delete v1.7   
adding image :
![alternate text for image](https://github.com/Basma516/basma/blob/master/basma.jpeg)    
