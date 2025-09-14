
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

Who Am I@DESKTOP-UCRK8PB MINGW64 ~/desktop/Egot_IT120_Act01 (master)
$ git checkout -b Egot_B1
Switched to a new branch 'Egot_B1'

Who Am I@DESKTOP-UCRK8PB MINGW64 ~/desktop/Egot_IT120_Act01 (Egot_B1)
$ echo "Birth of Place: P-4, Dalicanan Brgy; Tagbongabong R.T.R ADN
Religion: Roman Catholic
Father's Name: Bonifacio A. Egot Sr.
Occupation: Farmers
Mothers Name: Angelisa M. Egot
Occupation: House Wife" >> Profile.txt

Who Am I@DESKTOP-UCRK8PB MINGW64 ~/desktop/Egot_IT120_Act01 (Egot_B1)
$ git add Profile.txt
warning: in the working copy of 'Profile.txt', LF will be replaced by CRLF the n
ext time Git touches it

Who Am I@DESKTOP-UCRK8PB MINGW64 ~/desktop/Egot_IT120_Act01 (Egot_B1)
$ git commit -m "New Personal Information Added"
[Egot_B1 16ea7cb] New Personal Information Added
 1 file changed, 6 insertions(+)

Who Am I@DESKTOP-UCRK8PB MINGW64 ~/desktop/Egot_IT120_Act01 (Egot_B1)
$ ls
Background.txt  Education.txt  Profile.txt  Readme.txt  Test.py

Who Am I@DESKTOP-UCRK8PB MINGW64 ~/desktop/Egot_IT120_Act01 (Egot_B1)
$ notepad Profile.txt

Who Am I@DESKTOP-UCRK8PB MINGW64 ~/desktop/Egot_IT120_Act01 (Egot_B1)
$ notepad Readme.txt
Who Am I@DESKTOP-UCRK8PB MINGW64 ~/desktop/Egot_IT120_Act01 (Egot_B1)
$ git checkout master
M       Readme.txt
Switched to branch 'master'

Who Am I@DESKTOP-UCRK8PB MINGW64 ~/desktop/Egot_IT120_Act01 (master)
$ git checkout -b Egot_B2
Switched to a new branch 'Egot_B2'

Who Am I@DESKTOP-UCRK8PB MINGW64 ~/desktop/Egot_IT120_Act01 (Egot_B2)
$ ls
Background.txt  Education.txt  Profile.txt  Readme.txt  Test.py

Who Am I@DESKTOP-UCRK8PB MINGW64 ~/desktop/Egot_IT120_Act01 (Egot_B2)
$ echo "College: Caraga State University - Cabadbaran Campus
Program: BS Information Technology
Year Level: 3rd Year" >> Education.txt

Who Am I@DESKTOP-UCRK8PB MINGW64 ~/desktop/Egot_IT120_Act01 (Egot_B2)
$ git add education.txt

Who Am I@DESKTOP-UCRK8PB MINGW64 ~/desktop/Egot_IT120_Act01 (Egot_B2)
$ git add Education.txt
warning: in the working copy of 'Education.txt', LF will be replaced by CRLF the
 next time Git touches it

Who Am I@DESKTOP-UCRK8PB MINGW64 ~/desktop/Egot_IT120_Act01 (Egot_B2)
$ git commit -m "Added college info in Education.txt"
[Egot_B2 6125f96] Added college info in Education.txt
 1 file changed, 3 insertions(+)

Who Am I@DESKTOP-UCRK8PB MINGW64 ~/desktop/Egot_IT120_Act01 (Egot_B2)
$ git switch master
M       Readme.txt
Switched to branch 'master'
