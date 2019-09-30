# datastax-examples-template
This a sample template repo for contributions to the DataStax Examples platform.  This provides the minimum set of items needed to create a new example for submission to the DataStax Examples platform.

## Cloning this Repo to a New Repo
Open Terminal.

1) Create a bare clone of the repository.

`$ git clone --bare https://github.com/bechbd/datastax-examples-template.git`

2) Mirror-push to the new repository.`

`$ cd old-repository.git
$ git push --mirror https://github.com/bechbd/<new repo name>.git`

3) Remove the temporary local repository you created in step 1.

`$ cd ..
$ rm -rf datastax-examples-template.git`
 
