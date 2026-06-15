bundle 3 exercise1
`````
<!-- START: Bundle 3 Exercise 1 -->
# Question 1
cd "git exrcise"

# Question 2
git checkout ft/team-page

# Question 3
git branch main
git checkout main

git branch ft/contact-page

# Question 4
git switch ft/team-page

# Question 5
git log
git log --oneline -1

# Question 6
git checkout ft/contact-page
git log --oneline ft/team-page -1

git cherry-pick 0353690

# Question 7
git checkout ft/contact-page
git add contact.html
git commit -m "update on contact page"
git push origin ft/contact-page

# Question 8
git checkout ft/contact-page
git branch ft/faq-page
git checkout ft/faq-page
git add faq.html
git commit -m "the faq page"
git push origin ft/faq-page

# Question 9
git checkout ft/team-page
git revert 0353690
git push origin ft/team-page
<!-- END: Bundle 3 Exercise 1 -->
`````
exercise2
`````
<!-- START: Bundle 3 Exercise 2 -->
# Question 1
git branch ft/home-page-redesign

# Question 2
git checkout main

# Question 3
git add team.html
git commit -m "updated team.html"
git push origin main

# Question 4
git checkout ft/home-page-redesign

# Question 5
git rebase main

# Question 6
git add home.html
git commit -m "home page"
git push origin ft/home-page-redesign
<!-- END: Bundle 3 Exercise 2 -->
`````
Bundle 4 exercise 1
```````
<!-- START: Bundle 4 Exercise 1 -->
# Question 1
git checkout main

# Question 2
git remote add git-copy <repo-url>

# Question 3
git add home.html
git commit -m "update home page"

# Question 4
git push origin main
git push git-copy main
<!-- END: Bundle 4 Exercise 1 -->
```````
 exercise2
```````
<!-- START: Bundle 4 Exercise 2 -->
# Question 1
git checkout ft/footer

# Question 2
git add foot.html
git commit -m "foot page"

git add foot.html
git commit -m "new changes"

# Question 3
git push origin ft/footer

# Question 4
git checkout main
git branch ft/squashing
git checkout ft/squashing

# Question 5
git merge --squash ft/footer

# Question 6
git add foot.html
git commit -m "footer changes squashing"

# Question 7
git push origin ft/squashing
<!-- END: Bundle 4 Exercise 2 -->
``````` 
bundle 5 exercise 1
```````
<!-- START: Bundle 5 Exercise 1 -->
# Question 1
Enable GitHub Pages in repository settings

# Question 2
Check public link:
https://ora-nova.github.io/git-exercises/
<!-- END: Bundle 5 Exercise  -->
```````
exercise 2
```````
<!-- START: Bundle 5 Exercise 2 -->
# Question 1
git clone https://github.com/your-username/git-cafe-exercise

# Question 2
cd git-cafe-exercise

# Question 3
git add index.html

# Question 4
git commit -m "Change welcome message to restaurant"

# Question 5
git push origin main

# Question 6
Create PR to original repo
<!-- END: Bundle 5 Exercise 2 -->
```````
bundle 6 exercise 1
``````
<!-- START: Bundle 6 Exercise 1 -->
# Question 1
git checkout main
git checkout -b ft/menu

# Question 2
touch menu.html
git add menu.html

# Question 3
git commit -m "Add Menu page"
git push origin ft/menu

# Question 4
Create PR + request review
<!-- END: Bundle 6 Exercise 1 -->
``````
exercise 2
``````
<!-- START: Bundle 6 Exercise 2 -->
# Question 1
git checkout main
git checkout -b bugfix-contact-title

# Question 2
git add index-4.html
git commit -m "Fix contact page title"
git push origin bugfix-contact-title

# Question 3
Create PR + request review
<!-- END: Bundle 6 Exercise 2 -->
``````
exercise 3
````
<!-- START: Bundle 6 Exercise 3 -->
# Question 1
git checkout main
git checkout -b hotfix-contact-phone

# Question 2
Edit index-4.html:
Change phone number:
+1 800 603 6035 → +1 800 659 6035

# Question 3
git add index-4.html
git commit -m "Fix contact phone number"
git push origin hotfix-contact-phone

# Question 4
Create PR
<!-- END: Bundle 6 Exercise 3 -->
````
exercise 4
````
<!-- START: Bundle 6 Exercise 4 -->
# Question 1
Open peers PR

# Question 2
Go to Files changed tab

# Question 3
Click Review changes

# Question 4
Request changes with comments

# Question 5
After fixes → Approve PR

# Question 6
Merge PR
<!-- END: Bundle 6 Exercise 4 -->
````
