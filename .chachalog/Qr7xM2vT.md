---
# Allowed version bumps: patch, minor, major
profile: patch
---

Fixed user profiles so the details shown always belong to the person whose profile was opened.

On a page displaying user details, opening one person's profile and then another's could show the first person's details again for the second, until the cached page expired.
