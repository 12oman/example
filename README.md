# example
basic example of making commits

##  step 1. make some changes to the codebase to address an issue

an issue is typically a bug or a feature request. in this case, we are going to address a bug.

##  step 2. commit the changes

commit the changes to the codebase. this is done by running the following command:

    git commit -m "commit message"

the commit message should be a short description of the changes made. it should be in the present tense and should not be more than 50 characters long. it should also be capitalized. typically it doesn't include "how" the changes were made. it is also a good idea to include the issue number in the commit message. for example:

    git commit -m "fixes #1234"

it should also include a test case that demonstrates the bug has been fixed or the feature has been implemented. the test case should be in the same commit as the code changes.