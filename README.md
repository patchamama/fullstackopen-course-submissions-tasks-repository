# example-submission-repository


You may submit all the exercises of this course into the same repository, or use multiple repositories. If you submit exercises of different parts into the same repository, please use a sensible naming scheme for the directories.

One very functional file structure for the submission repository is as follows:

<pre>
part0
part1
  courseinfo
  unicafe
  anecdotes
part2
  phonebook
  countries
</pre>

Put the whole react repository of the project to each folder except the folder <i>node_modules</i>

# to delete the files in the main directory to submit all the content

```sh
rm -rf .git
rm -rf node_modules/ && npm i
```
