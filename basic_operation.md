** Four essentials **
- repositories - 
- branches
- commits - saved changed are called commits.
- pull requests

1. Repositories
To organize **a single project**, and store everything associated with the project, such as folders and files, images, videos, spreesheets, data sets, ect, 

2. Branches
  - **master** branch   When you created a repository, the branch named "master" will be created by default.
  - **feature** branch    A copy or snapshot of **master** branch
  
3. commits and pull request

> On GitHub, saved changes are called *commits*. Each commit has an associated *commit message*, which is a description explaining why a particular change was made.

The process of making and committing a change:
  - Firstly, **crete a new branch**, named, for example "readme-edits".

  - Secondly, **make and commit changes** in the new branch

  - Then, **Open a Pull Request** , look over your changes in the diffs on the Compare page.
  base: master ... compare:readme-edits
Once you are satisfied with the changes, click the [Create Pull Request]
>Pull Requests are the heart of collaboration on GitHub. When you open a pull request, you’re proposing your changes and requesting that someone review and pull in your contribution and merge them into their branch. Pull requests show diffs, or differences, of the content from both branches. The changes, additions, and subtractions are shown in green and red.

  - Finally, **Merge your Pull Request** - merging your "readme-edits" branch into the branch, and delete this feature branch.

Notice:
README -- add some description and information about your project

References
[1]https://guides.github.com/activities/hello-world/
