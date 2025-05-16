DevOps Task 4 
 Version-Controlled Project

 Objective
Build and manage a DevOps project using Git and GitHub best practices including branching, commits, tags, and documentation.

Tools Used
•	Git
•	GitHub

 Branch Strategy
•	Main : Production-ready code
•	dev : Development integration
•	feature : Individual features 

Features Implemented
•	Feature branches created for each task
•	Pull Requests used to merge into dev
•	Merges from dev to main after final review

 Versioning
-v1.0 : First stable version tagged

 Files
•	.gitignore added to ignore unnecessary files
•	This `README.md` to document the project

 How to Use
1. Clone the repository:  
   git clone https://github.com/Hiba1311/devops-task4  
   cd Devops-task4  

2. Create a new feature branch:  
   git checkout -b feature/my-feature  

3. Add your changes and commit:  
   git add .  
   git commit -m "Add: <describe your feature>"  

4. Push your branch:  
   git push origin feature/my-feature  

5. Create a Pull Request on GitHub to merge into dev  

6. After testing, merge dev into main  

Versioning

Git tags are used to track project releases:  
•	git tag -v1.0 
•	git push origin v1.0 
