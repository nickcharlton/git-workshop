# Notes

## Overview and Why?

* Store everything you do – giving a history along the project.
* Which make it very easy to rollback to where you were before you broke
  everything *and* make it very easy to collaborate with others.
* If you've ever used anything else (like subversion), it's best to forget
  everything. Otherwise it makes life hard.

* Git is known as being 'distributed'. This means that you always have
  a complete version of the repository with you.
* Firstly, this means that everything is super fast.
* Secondly, you can continue working on the track back home.
* To aid it's speed, Git only stores snapshots of files. This means that it's
  very quick to commit to the repository. But also the overall repository size
  is kept as small as possible.
* You'll notice this if you try to create a directory in a repo. Git won't see
  it until you add a file to that directory.
* It's also worth adding here – Git usually just adds data. Regardless of the
  mess you get yourself in, it's unlikely that you've lost something. Be it
  a bad merge or a bad reset. If you've committed it, it'll still be there.

## Staging Files

* When you're using Git, you'll come across various states that files can be
  in.
* These are "unknown", "staged" and "committed".
* Unknown is when Git doesn't know about it yet.
* Staging adds files ready to be committed.
* Once it's committed, it's added to the repository.

## Committing

* Committing is one of the most fundamental actions you'll do. This adds
  a snapshot of of the file's changes to the repository.
* A commit contains: the snapshot, a timestamp, a hash and who committed it.
* You should do this often. You'll thank your past self.

## History

* Once a set of changes is committed to the repository you can view it in your
  history.
* From here, you can jump back to a previous repository state, or see who's
  done what.

## Setup

* *an explanation of how to use and find Git on the University machines*

**Activity: Create a repo. Add some files. Commit.**

## Remotes and GitHub

* Now you have a repository up and working, it's worth knowing about "remotes".
* A remote is a repository somewhere else. It can be on a service like GitHub
  or BitBucket or just hosted on another machine somewhere.
* Once configured, you can send all of your changes over to this remote
  repository.
* It's the key bit that allows you to collaborate with other people.

**Activity: Create a public repo on GitHub. Add it as a remote. Push it up.**

## Branching and Merging

* Say a requirement has changed. Or maybe you want to try something different
  without breaking what you already have.
* This is where branching and merging come in.
* You already have a "master" branch. By default, this is where all of your
  commits will go.
* Branching allows you to diverge from your current repository state, but still make
  it possible to go back to where you were.
* Merging allows you to take your new branch and combine it with another.
* I like to work on "feature branches". These are created first for one small
  requirement, merged back in and then disposed of. This way, you always have
  a working version on your "master" branch.

## Nick's Tips

* Use Feature Branches – branch, even for the little things.
* Commit often.
* Stick to one commit style.
* Use Git for everything – code, documentation, reports. Everything.
* Push to a remote often. Instant, cheap backup.

