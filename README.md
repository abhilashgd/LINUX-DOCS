# LINUX-DOCS

# INSTALLING ZSH
          
          download and install homebrew, iterm2, zsh and oh myzsh
          FOR WINDOWS, use docker container image ubuntu ssh into the container and use
          
          
# ITERM2 SHORTCUTS

          % ctrl+l //clear terminal
          % ctrl+k //clear terminal
          % alt+command+c //spectacle
          % echo $SHELL
          % command+D //new shell inside same terminal vertically
          % command+w //close terminals
          % shift+command+D //new shell inside same terminal horizontally
          //profiles settings for customization
          % ctrl+a // to go to the beggining of the line
          % ctrl+e // to go to the end
          % alt+b //back one word at a time
          % alt+f //to go forward by one word
          % clear //clear terminal
          
          
# BASIC COMMANDS
          
          //BASIC UTILITIES
          % date //for todays date
          % cal //for this month calender
          % cal 2022
          % whoami //user logged in
          % man  //provides detailed info about the command
          % man cal
          % pwd
          
          % man ls  //listing 
          % ls
          % ls -a
          % ls -l
          % ls -la
          % ls testFolder
          
          % man cd //change directory
          % cd Desktop
          % cd ..
          % cd -
          
          % man df  //disk free space
          % df -h
          % man df
          
          % man mkdir  //make a directory
          % mkdir testFolder
          % mkdir testFolder1
          % rm -rf testFolder
          % mv testFolder1 testFolder
          % mkdir -p testFolder/hello/world //creates all directories  testFolder, hello, world
          
          % tree //to see folder structure
          % tree -l
          % touch query.sql
          % less query.sql
          % q
          % head query.sql //to see first 10 lines
          % tail query.sql //to see last 10 lines
          % cat query.sql
          
          % mv testFolder renamedFolder //to rename folders
          % mv query.sql testFolder2  //mv to move files and folders around
          % mv testFolder2/query.sql .
          % rm query.sql
          % touch query-1.sql
          % touch query-2.sql
          % rm query-*.sql
          % echo "select * from customer;"
          % echo "select * from customer;" >query.sql //to override
          % cat query.sql
          % echo "select * from order;" >>query.sql //to append
          
          % man cp  //copy command to duplicate files and folders
          % cp query.sql testFolder1/
          % cp query.sql query-copy.sql
          % cp *.sql /testFolder2/
          % cp -r testFolder1 testFolder-copy
          
          % man find  //to find files and folders 
          % find .
          % find . -name query.sql
          % find . -type f -name  query.sql
          % find . -type d -name  world
          % mv query.sql QUERY.sql
          % find . -type f -iname  query.sql
          % find . -type f -name  "*.sql"
          % find . -type f -empty
          % find . empty
          
          % man grep //used to search text inside a file and display content
          % grep -r "END" linuxDocs
          % grep -rni "customer" .
          % grep -rni -A 3 "customer" .
          % grep -rni -A 1 -B 4 "customer" .
          % grep -rni -A 1 -B 4 "customer" query.sql
          
          
# VIM
          % man curl //used for downloading files from server
          % curl -O https://github.com/abhilashgd/CUSTOMER-REGISTRATION-AND-FRAUD-CHECK-APP-MICROSERVICE-BACKEND/blob/main/customer/src/main/java/com/microservicetest/customer/CustomerController.java
          % less CustomerController.java
          % q
          % curl -O https://github.com/abhilashgd/CUSTOMER-REGISTRATION-AND-FRAUD-CHECK-APP-MICROSERVICE-BACKEND/blob/main/fraud/src/main/java/com/microservicetest/fraud/FraudController.java
          % less FraudController.java
          % q
          
          //command mode
          % vim CustomerController.java
          % :set number  //sets line numbering on 
          % :set nu
          % :syntax on  //sets syntax on according the the language specification similar to IDEs
          % :q! or :wq!
          % :wq
          h--> moves left 
          l-->moves right
          j-->moves down
          k-->moves up
          w-->moves word by word forward
          b-->moves word by word backward
          0-->to goto beggining of the line
          $--> to goto end of the line
          ^--> to goto beggining of the line after white spaces
          g -->two time -->to the beggining of the file
          G -->for end of the file
          { --> moves sentense by sentense upwards
          { --> moves sentense by sentense downwards
          8 gg --> goes to line number 8
          24 gg --> goes to line number 24
          i --> for insert mode
          esc --> for command mode
          % vim +20 CustomerController.java
          
          //insert mode
          % vim CustomerController.java
          % i //for insert mode
          % esc //for going back to command mode
          % u //to undo changes line by line inside command mode
          % ctrl + r //for redo
          % a --> for appending after the cursor 
          % shift+a --> to insert at the end of the line
          % o --> to insert after current line
          % shift+o --> to insert before current line
          % :q! to quit without changes
          % :w to save changes
          % :q! to quit
          % :wq to write/save and quit
          
          //deleting cut and paste
          % vim FraudController.java
          % set nu
          % set syntax on
          % dw --> to delete word
          % dd --> to delete entire line
          % 4dd --> to delete 4 lines
          % dG --> to delete complete file content
          % dd--> cuts line
          % p --> to paste the line
          % d0 --> to delete till the begginging of the line
          % d$ --> to delete till end of the line
          % u --> to undo changes line by line
          % /final //"final" is the string to search
          % n //to find next occurence of the word "find"
          % shift + n // to find previous occurence
          % :%s/public/private/gc  //public-string to replace, private - string which will replace, g- global, c-confirm before changing
          % vim fileName // to create a new file with fileName
          
#VIMRC CONFIGURING
          
          % vim .vimrc //under root directory
          % i
          //inside the file
          :set number
          :syntax on
          
          Ref-> The ultimate Vim configuration (vimrc):
          https://github.com/amix/vimrc
        
          
          
          
          
          
          
          
