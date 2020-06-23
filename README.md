### Setting up project on your system & basic GitHub guide

#### A. Setting up & running project on your system
1) First cloning the repo from github
```
$ git clone https://github.com/code-india-code/desi-cam-scanner.git
```
- To install all packages
``` 
$ npm install
```
```
$ npm install expo-cli --global
```
 
- running the app in our system  
```
$ npm start 
```
#### B. Basic github guide to contribute in this
2) Branch name should be short & should include the issue on which you are working or feature you are adding

```
eg: $ git branch imageToPDF
``` 
- Now , to create a new branch
```
$ git branch NEW_BRANCH_NAME  
```
3) Now, to enter this new branch
```
$ git checkout NEW_BRANCH_NAME
```
4) Now, add your code
- Do whatever changes you want to do / features you need to add 

5) Now first commiting these changes to our local repo
```
$ git add .
$ git commit -m " your message- 5 word summary of your changes"
```
6) Now your changes are in only you local repo (i.e only in your system).
- So we will update to our remote repo i.e in github server by pushing our local branch  
```
$ git push -u origin NEW_BRANCH_NAME
```
