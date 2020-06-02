# How to Update this repo with origin?

* Add the remote (original repo that you forked) and call it “upstream” (You just need to to this
  once): `$ git remote add git@github.com:eugenp/tutorials.git`
* Fetch all branches of remote upstream: `$ git fetch upstream`
* Make a rebase: `$ git rebase upstream/master`
* Push the updates to your master: `$ git push origin master --force`
