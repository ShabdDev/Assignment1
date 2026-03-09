Assignment 1 
Tasks To Be Performed: 
1. Based on what you have learnt in the class, do the following steps: 
    a. Create a new folder 
    b. Put the following files in the folder ● Code.txt ● Log.txt ● Output.txt 
    c. Stage the Code.txt and Output.txt files 
    d. Commit them 
    e. And finally push them to GitHub 
2. Please share the commands for the above point

solution: 
1. cd /E
2. cd Devops/Devops_Labs/Git_Labs
3. mkdir Assignment1
4. cd Assignment1
5. git init
6. git config --global user.email "shabdali.tribhuwan97@gmail.com"
7. git config --global user.name "Shabdali Tribhuwan"
8. touch Code.txt Log.txt Output.txt
9. git add Code.txt Log.txt
10. git commit -m "Code.txt and Log.txt these files are added"
11. git remote add origin https://github.com/ShabdDev/Assignment1.git
12. git branch -M main
13. git push -u origin main
14. history
