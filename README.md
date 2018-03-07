# git-cloneas
add git sub-command `git cloneas`.

# What's 'cloneas'?
Some time, do you want to set local user?
But,only at those times, forgot to set it..:sob:

Don't worry!!:smile:

**This 'cloneas' command resolve it!!**

# How to use ?

## setup sub-command
copy `git-cloneas` file and place it in the directory where the path passes

## setup any user profile
Open your **global** `.gitconfig` file.
And set any User Profiles,like this.

```
[SomeUser1]
  name = some-user1
  email = some.user1@some.com
[SomeUser2]
  name = some-user2
  email = some.user2@some.com
...
```

## Let's clone as ..
Use the `cloneas` command as follows.

```
git cloneas <User> <git-repo>
```

### Example
If you want clone this repository as *SomeUser1*, you will execute following command.

```
$ git cloneas SomeUser1 git@github.com:kiuchikeisuke/git-cloneas.git
Cloning into 'git-cloneas'...
remote: Counting objects: 4, done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (4/4), 4.52 KiB | 0 bytes/s, done.
set local user.name some-user1
set local some.user1@some.com
```

**Then git clone done , and set local user automatically!!**:smile::smile:
