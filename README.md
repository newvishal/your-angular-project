check link https://newvishal.github.io/your-angular-project/

steps:
 # 1: npm install -g @angular/cli
 # 2: ng new your-angular-project --defaults
 # 3: cd your-angular-project
 # 4: Create a new empty GitHub repository first.
 # 5: Please enter the URL https://github.com/<username>/<repositoryname>.git into your browser – you should see your existing         repository on GitHub.
  cmd: git remote add origin https://github.com/<username>/<repositoryname>.git
 # 6: Add angular-cli-ghpages to your project.
    cmd: ng add angular-cli-ghpages
 # 7: ng deploy --base-href=/the-repositoryname/
 # 8: https://<username>.github.io/<repositoryname>
  
