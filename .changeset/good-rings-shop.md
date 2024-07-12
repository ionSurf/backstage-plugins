---
'@axis-backstage/plugin-vacation-calendar': patch
---

If the user is not found in the vacation calandar, an extra check now see if userId matches entity email. In addition, if no user is found, only the name is returned instead of the whole userId.
