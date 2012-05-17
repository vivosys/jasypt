1. git svn remote (add to .git/config):

[svn-remote "svn"]
        url = https://jasypt.svn.sourceforge.net/svnroot/jasypt
        fetch = trunk:refs/remotes/trunk
        branches = branches/*:refs/remotes/*
