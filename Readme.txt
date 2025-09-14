Who Am I@DESKTOP-UCRK8PB MINGW64 ~/desktop/Egot_IT120_Act01
$ git init
Initialized empty Git repository in C:/Users/Who Am I/Desktop/Egot_IT120_Act01/.
git/

Who Am I@DESKTOP-UCRK8PB MINGW64 ~/desktop/Egot_IT120_Act01 (master)
$ echo "First Name: Bonifacio, Jr
Middle Name: Magalona
Last Name: Egot
Gender: Male
Age: 24
Birthday: March, 11 , 2001
Contacts: 09709221667" > Profile.txt

Who Am I@DESKTOP-UCRK8PB MINGW64 ~/desktop/Egot_IT120_Act01 (master)
$ echo "Elementary School: Tagbongabong Elementary School
Year Graduated: SY 2013-2014
High School: Balang balang National High School
Year Graduated: SY 2017-2018
Senior High School: Agay National High School
Year Graduated: SY 2018-2020
" > Education.txt

Who Am I@DESKTOP-UCRK8PB MINGW64 ~/desktop/Egot_IT120_Act01 (master)
$ echo "Language: Bisaya, Tagalog, English
" background.txt
Language: Bisaya, Tagalog, English
 background.txt

Who Am I@DESKTOP-UCRK8PB MINGW64 ~/desktop/Egot_IT120_Act01 (master)
$ echo "" > Readme.txt

Who Am I@DESKTOP-UCRK8PB MINGW64 ~/desktop/Egot_IT120_Act01 (master)
$  echo "" > Test.py

Who Am I@DESKTOP-UCRK8PB MINGW64 ~/desktop/Egot_IT120_Act01 (master)
$ ls
Background.txt  Education.txt  Profile.txt  Readme.txt  Test.py

Who Am I@DESKTOP-UCRK8PB MINGW64 ~/desktop/Egot_IT120_Act01 (master)
$ git add .
warning: in the working copy of 'Education.txt', LF will be replaced by CRLF the
 next time Git touches it
warning: in the working copy of 'Profile.txt', LF will be replaced by CRLF the n
ext time Git touches it
warning: in the working copy of 'Readme.txt', LF will be replaced by CRLF the ne
xt time Git touches it
warning: in the working copy of 'Test.py', LF will be replaced by CRLF the next
time Git touches it

Who Am I@DESKTOP-UCRK8PB MINGW64 ~/desktop/Egot_IT120_Act01 (master)
$ git commit -m "Files Created and data on the Profile.txt, Education.txt and Backround.txt is inserted "
[master (root-commit) 5147058] Files Created and data on the Profile.txt, Educat
ion.txt and Backround.txt is inserted
 5 files changed, 17 insertions(+)
 create mode 100644 Background.txt
 create mode 100644 Education.txt
 create mode 100644 Profile.txt
 create mode 100644 Readme.txt
 create mode 100644 Test.py

Who Am I@DESKTOP-UCRK8PB MINGW64 ~/desktop/Egot_IT120_Act01 (master)
$ git user --global user.email "rezzhas@gmail.com"
git: 'user' is not a git command. See 'git --help'.

The most similar command is
        subtree

Who Am I@DESKTOP-UCRK8PB MINGW64 ~/desktop/Egot_IT120_Act01 (master)
$ git config --global  user.email "rezzhas@gmail.com"

Who Am I@DESKTOP-UCRK8PB MINGW64 ~/desktop/Egot_IT120_Act01 (master)
$ git config --global  user.name sungjinwoo100"
>
> ^C

Who Am I@DESKTOP-UCRK8PB MINGW64 ~/desktop/Egot_IT120_Act01 (master)
$ git checkout master
Already on 'master'

