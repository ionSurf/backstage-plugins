---
'@axis-backstage/plugin-jira-dashboard-backend': patch
---

Installed the auth-backend-module-guest-provider plugin to allow users to sign in as a specific user. This will prevent the Jira plugin from getting 401 response due to that httpAuth.credentials can't be found.
