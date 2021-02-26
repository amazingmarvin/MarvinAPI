---
name: Bug report
about: Report a Marvin API bug
title: "[BUG]"
labels: bug
assignees: amazingmarvin

---

**Statement of purpose**

I do solemnly swear (or affirm) that this is an API bug, and not a Marvin bug. For Marvin bugs I would use the in-app "?→Contact Support" feature

<!-- Feel free to delete any sections below that don't apply to your situation. -->

**Describe the bug**
A clear and concise description of what the bug is.

**Endpoint(s) in question**
e.g. `/api/track`

**To Reproduce**

e.g.
```
curl \
  -XPOST \
  -H'X-API-Token: redacted' \
  --data '{"taskId":"xyz","action":"STOP"}' \
  https://serv.amazingmarvin.com/api/track
```

or sample code, or ?

**Expected behavior**
A clear and concise description of what you expected to happen.

**Screenshots**
If applicable, add screenshots to help explain your problem.

**HTTP client:**
* curl? browser (w/ CORS details)? language library? 

**Additional context**
Add any other context about the problem here.
