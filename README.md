# LINUX-DOCS

# INSTALLING ZSH
          
          download and install homebrew, iterm2, zsh and oh myzsh
          FOR WINDOWS, use docker container image ubuntu ssh into the container and use
          
          
# ITERM2 SHORTCUTS

          % ctrl+l
          % ctrl+k
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
          % clear
          
          
# BASIC COMMANDS
          
          //BASIC UTILITIES
          % date //for todays date
          % cal //for this month calender
          % cal 2022
          % whoami
          % man
          % man cal
          % pwd
          
          % man ls
          % ls
          % ls -a
          % ls -l
          % ls -la
          % ls testFolder
          
          % man cd
          % cd Desktop
          % cd ..
          % cd -
          
          % man df
          % df -h
          % man df
          
          % man mkdir
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
          % mv query.sql testFolder2
          % mv testFolder2/query.sql .
          % rm query.sql
          % touch query-1.sql
          % touch query-2.sql
          % rm query-*.sql
          % echo "select * from customer;"
          % echo "select * from customer;" >query.sql //to override
          % cat query.sql
          % echo "select * from order;" >>query.sql //to append
          
          % man cp
          % cp query.sql testFolder1/
          % cp query.sql query-copy.sql
          % cp *.sql /testFolder2/
          % cp -r testFolder1 testFolder-copy
          
          % man find
          % find .
          % find . -name query.sql
          % find . -type f -name  query.sql
          % find . -type d -name  world
          % mv query.sql QUERY.sql
          % find . -type f -iname  query.sql
          % find . -type f -name  "*.sql"
          % find . -type f -empty
          % find . empty
          
          % man grep //used to search text inside a file
          % grep -r "END" linuxDocs
          % grep -rni "customer" .
          % grep -rni -A 3 "customer" .
          % grep -rni -A 1 -B 4 "customer" .
          % grep -rni -A 1 -B 4 "customer" query.sql
          
          
# VIM
          % man curl
          % curl -O https://github.com/abhilashgd/CUSTOMER-REGISTRATION-AND-FRAUD-CHECK-APP-MICROSERVICE-BACKEND/blob/main/customer/src/main/java/com/microservicetest/customer/CustomerController.java
          % less CustomerController.java
          % q
          % curl -O https://github.com/abhilashgd/CUSTOMER-REGISTRATION-AND-FRAUD-CHECK-APP-MICROSERVICE-BACKEND/blob/main/fraud/src/main/java/com/microservicetest/fraud/FraudController.java
          % less FraudController.java
          % q
          
          
          
          
          
          
          
          
          
          
          
          
