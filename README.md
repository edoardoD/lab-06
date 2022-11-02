# How to use this repository

Recommended strategy:
* Create your own copy of this repository on your profile
* Clone this repository locally
* Remove the `origin` remote
* Create a new `origin` remote pointing to your copy
* Push the exercises branch on your copy, setting the branch upstream contextually (use `git push -u origin exercises`)
* Commit progressively when resolving the exercise and push changes on your repo


# Solutions

* generate the public ssh key on your pc.
I using windows based pc and this is only for that operating system: 
 - open git bash and execute `ssh-keygen` press `enter` untill the process will finish 
 - `cat ~/.ssh/id_rsa.pub` cpy and paste the output in the ssh section on your github account
 - now cpy the ssh link of the teacher account and do: `git clone [ssh-link-techer]`
 - remove the remote `origin` of the teacher' s repo:
 - - `git remote show origin` check if the origin is whorst
 - - `git remote rm origin`
 - - `$ git add . $ git commit -m "First commit" $ git remote add origin Copied_origin_url $ git remote show origin $ git push origin master`
