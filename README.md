# ATL Server

## Origin 

This code was pulled down [CodePlex](http://atlserver.codeplex.com/) before it was [shut down](https://blogs.msdn.microsoft.com/bharry/2017/03/31/shutting-down-codeplex/). Every effort was made to preserve history of the original authors using widely [accepted methods](https://john.albin.net/git/convert-subversion-to-git) available at the time, but it would just hang forever when cloning using git-svn. 

## Wacky SVN

I'm not sure if the CodePlex server/bridge is jacked, but there were a few things that didn't look right that are worth pointing out.

### Authors

Here is an example `authors-transform.txt`:

```
RNO\V-BCHRIS = RNO\V-BCHRIS <RNO\V-BCHRIS>
RNO\_TFSSERVICE = RNO\_TFSSERVICE <RNO\_TFSSERVICE>
SND\atlsadmin_cp = SND\atlsadmin_cp <SND\atlsadmin_cp>
vstfs:///Framework/IdentityDomain/2327b42d-5241-43d6-9e2a-de5ac946f064\Project Collection Service Accounts = vstfs:///Framework/IdentityDomain/2327b42d-5241-43d6-9e2a-de5ac946f064\Project Collection Service Accounts <vstfs:///Framework/IdentityDomain/2327b42d-5241-43d6-9e2a-de5ac946f064\Project Collection Service Accounts>
```

### Revisions

Also, the revisions shown with `svn log -q` gave inconsistent results and let me to belove that they couldn't be trusted.

### Proper Migrations

Hopefully this code will get migrated by the owners using the tools built in collaboration with GitHub and this repo will no longer be needed.

### Conclusion 

I did all I could to properly move this code. Please let me know should take it down because a proper migration exists somewhere else.

Read more about the [project](https://en.wikipedia.org/wiki/ATL_Server) and find [reference](https://msdn.microsoft.com/en-us/magazine/t9adwcde.aspx).
