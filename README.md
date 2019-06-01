# Portfolio Optimzation
The project aims to select proportions of various stocks in order to minimize the volatility of the portfolio. Our project will not assume ideal conditions. We will take into account the associated costs with trading as well as the non-stationary nature of the financial market. 

## Usage
If done correctly, our project will maximize returns while minimizing risk. In simple terms, this project will help you make money. 

## Team
Demi Dang 

Elia Xu

Sergio Zambrano 

Tommy Siegle

## Dataset
Data sets were obtained from yahoo finance 
https://finance.yahoo.com/

## Project Progress
Get familiar with Github

Create a master notebook with main functions

## General Git instructions

### Clone project to Jupyter

Open Jupyter notebook

Click new -> Terminal 

Run the command: git clone https://github.com/demidang12/PSTAT134FinalGroupProject


### Get the latest changes from Github

Click new -> Terminal

run: ls

run: cd PSTAT134FinalGroupProject

Until I find a better way to download and upload to github, make sure to pull before uploading

run: git pull origin master

run: git pull origin collab

### To upload to github (Temp)

click new -> terminal 

run :ls

run: cd PSTAT134FinalGroupProject

run: git checkout collab

run: git add .

run: git commit -m 'Write something relevant to code'

run: git push

The code should then be uploaded to a branch in github. From there click the buttom 'New Pull Request'. Follow the directions and write what changes you are making and what is it for. When it is all done, merge to main branch. 

### Reset branch and pull from others

open Terminal

run the following commands

git fetch --all

git reset --hard origin/master

git reset --hard HEAD

git clean -f -d

git pull origin NameofBrance

If a prompt window pops up press

ctrl-x ctrl-c
