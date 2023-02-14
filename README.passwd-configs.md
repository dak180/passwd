Administrators can reconfigure @PREFIX@/etc/passwd-fink and @PREFIX@/etc/group-fink
to match their desired UID and GID settings for the various users.  The formats are
as follows.

passwd-fink:

```
<username>:*:<uid>:<gid>::0:0:<description>:<home directory>:<shell>
```

group-fink:

```
<groupname>:*:<gid>:<comma-separated-list-of-users>
```

`<field>` denotes a field which can be set by the administrator, and everything
else is mandatory.
