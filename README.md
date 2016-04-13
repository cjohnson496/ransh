
####SHORTCUTS
remove every specific word in a file - `sed -i 's/WORD//g' filename`   

remove lines with specific word - `sed -i '/pattern to match/d' filename ` 

replace one word with another - `sed -i s/OLD/NEW/g file`  
add a backup extension to sed - `-i.bak`    

execute a command on every file in current directory - `find . -type f -exec COMMAND {} \;`    
  
find a file from `~` - `find ~ -name filename`  

ROLLBACK GIT REPO - 
`git reset --hard old-commit-id; git push origin HEAD --force`



 
