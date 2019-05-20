# Choerodon Contributor Guide

Welcome to Choerodon! When you want to make a contribution to Choerodon, the document elaborates how you can do.

Contributions are welcome and appreciation! Every little bit helps and credit will always be given.

When you are ready to contribution
Please read [Choerodon coding specification](http://choerodon.io/zh/docs/development-guide/platform/)first.

You can contribute in many ways:

## Types of Contributions

### Report Bugs

Report bugs through [GitHub Issues](https://github.com/choerodon/choerodon/issues/new)

If you are reporting a bug, please include:

Your Browser and version.
Any details about your local setup that might be helpful in troubleshooting.
Detailed steps to reproduce the bug.

### Fix Bugs

Look through the GitHub issues for bugs. Anything tagged with "bug" is open to whoever wants to implement it.

### Implement Features

Look through the GitHub issues for features. Anything tagged with "feature" is open to whoever wants to implement it.

### Documentation

If you find any omissions or inaccuracies while browsing the documentation, leave feedback in Github Issues or modify it on the Fork website.

### Submit Feedback

The best way to send feedback is to file an issue on GitHub.

If you are proposing a feature:

Explain in detail how it would work.
Keep the scope as narrow as possible, to make it easier to implement.
Remember that this is a volunteer-driven project, and that contributions are welcome

If you put forward a suggestion:

Elaborate your ideas and requirements in detail.

If you put forward a bug:

Describe the problems you encountered, the operating environment and your own ideas in detail.

## Pull Request Guidelines

### Open a Pull Request

1. Fork Choerodon

 Go to [Choerodon](https://github.com/choerodon/choerodon), click fork button.
2. Clone fork to local storage

 ```git clone https://github.com/$user/choerodon.git```
 
3. Branch

 Update local branch of master and create new branch.
 
 ``` 
 git pull origin master
 git checkout -b myfeature
 ```
 Modify on the branch of myfeature.

4. Test

 Testing is the responsibility of all contributors.

 Please write the unit test case.
 
5. Keep your branch in sync

 Before submitting your code, please update the latest code and resolve conflict locally.
 
 ``` git fetch & git rebase ```

6. Commit

 Submit your locally modified code.
 
 ``` git commit -m "[IMP] summit"```
 
 - [IMP] Improve the function
 
 - [FIX] Fix the bug
 
 - [ADD] Add the funtion

 - [DEL] Delete the document

7. Push

 Push code to your remote repository.

8. Create a pull request

 Create a [merge request] on Github(https://help.github.com/articles/about-pull-requests/), wait to verify.

### Code Review

Completing the following points will help your submission to get better comments:

  - Follow the project's coding rules
  - Write a qualified description of submission     
  - Divide the large changes into smaller changes as much as possible, and add detailed descriptions for each minor change to help reviewers better understand your submissions.


Reviewers need to observe the following guidelines:

 - Prohibit public harassment or private harassment
 - Prohibit personal attacks
 - Prohibition of satirical and insulting/derogatory comments
 - Prohibit posting of private information of others, such as physical and electronic addresses, without explicit permission
 - Prohibit other unethical and unprofessional behavior
 
Project maintainers have the right and responsibility to delete, edit or reject comments, submissions, codes, questions, and other contributions that do not conform to the revised guidelines. The project maintainers promise to treat all adherence to the guidelines fairly and consistently.People who do not follow the code of conduct may be permanently removed from the project team.
