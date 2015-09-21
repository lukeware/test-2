This project will use the [Github Flow](https://guides.github.com/introduction/flow/), as defined by Github. That means we will make branches for each Task, and we will merge those branches using Pull Requests that we can code review and discuss.

If you are not familiar with [Github Flow](https://guides.github.com/introduction/flow/), please consult [this link](https://guides.github.com/introduction/flow/).

## Branch Management
As we work through this project, we will alter the names of the branches from what Github Flow specifies:

* `master` - This is the branch all work should be derived from. When creating a new Task branch, be sure to branch off of `master`.
* `gh-pages` - This is our production branch. Merging code to the `gh-pages` branch publishes the content to the publicly available static website.

Your work should be contained in branches that are named like this:

* `feature/task-name` - Feature branches contain new things that are in development. There will be lots of these.
* `fix/task-name` - Fix branches address any bugs or defects we find. There will (unfortunately) be lots of these.
* `misc/task-name` - If it's not a Feature and it's not a Fix, then we can just file it under Miscellaneous. Let's make sure there are very few of these.

## Code Reviews
Code reviews are essential. As you work on a feature, it's useful to create a [Pull Request](https://help.github.com/articles/using-pull-requests/) right away. Pull Requests will be used to conduct code reviews and assure that changes are compatible with the rest of the project before merging. 

Remember the following:
* Everyone should check for pending Pull Requests every day.
* If it is in-progress code, review the progress so far and leave inline comments if you see anything that gives you concern.
* Once the work is completed (as indicated by the author) review the code in the Pull Request and make inline comments if you see anything you have questions or comments about.
* Check out the branch for this Pull Request and test the changes to verify they work.
* If you don't have any specific comments, leave a comment on the Pull Request indicating your support for moving forward (+1).

**All changes must be reviewed by at least one other developer before they can be merged to `master`.**

If you have verified functionality and reviewed code, you may merge somebody else's Pull Request. **You should never merge your own Pull Request.**