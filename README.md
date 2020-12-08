# workos-events
WorkOS events 

Users:
```
dsync.user.created
dsync.user.deleted
```
Groups:
```
dsync.group.created
dsync.group.user_removed
dsync.group.user_added
```

Omitted:
```
dsync.user.updated
```
Info to update user name?
***
```
dsync.group.updated
```
Property to update group name.
***
``` 
dsync.group.group_deleted
```
It doesn't provide the list of deleted users and we're not storing directories id's
```
{
  "event": "dsync.group.group_deleted",
  "data": {
    "directory_id": "directory_edp_01E1X194NTJ3PYMAY79DYV0F0P",
    "id": "directory_grp_01E1X5GPMMXF4T1DCERMVEEPVW",
    "name": "Developers"
  }
}
```