---
date: 2018-02-26T14:10:03Z
title: "jx delete jenkins user"
slug: jx_delete_jenkins_user
url: /commands/jx_delete_jenkins_user/
---
## jx delete jenkins user

Deletes one or more jenkins user api tokens

### Synopsis

Deletes one or more jenkins user tokens from your local settings

```
jx delete jenkins user [flags]
```

### Examples

```
  # Deletes a git provider
  jx delete git server MyProvider
```

### Options

```
  -h, --help          help for user
  -n, --name string   The name of the git server to add a user
  -u, --url string    The URL of the git server to add a user
```

### SEE ALSO

* [jx delete jenkins](/commands/jx_delete_jenkins/)	 - Deletes one or many jenkins resources

###### Auto generated by spf13/cobra on 26-Feb-2018