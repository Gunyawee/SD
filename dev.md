#I've learned

Git checkout test.txt >>  use it when you want ot recovery your file before you didn't commit it yet.

Git reset HEAD test.txt >>  ues it with the firt one if you want to recovery your file when you commited it.

Git pull >> to make your local as same as your remote origin

Git reset —soft “head^”

Gir rm Test.txt >> to delete your file which is commited 


Git add . >> to add your file (all the files that you want to change or add)
Git commit -m “update” >> to commit the files
Git push origin master >> to upload file to the remote origin branch name master

===  when you edit the files in the remote orgin and you should change in the local part too you can use
>> Git fetch 
>> Git merge   or  >> git pull

==when you want to hide your data youcan use
>> Git stash (to hide)
>> Git stash pop (to show it back)
 


Git brach -a  >> show all branshes

Git brach dev  >> make a branch

Git checkout dev >> move to dev branch

Git checkout -b new >> make and move to new branch

Git brach -d dev >> to delete branch


Get push -u origin new >> to upload file to the remote origin in branch name new


-----my little note :)-------------------------------------

Git checkout master
Git merge dev 
Git add .
Git commit -m “”
push origin  master 
Git checkout new 
Git add. 
Git commit -m “”
Git push origin  new

Git checkout master
Git merge —no-f 
Git add .
Git commit -m “”
push origin  master 

Switch  to branch master
Git merge —no-f new #merge from new to master

-------------------------------------------------------

