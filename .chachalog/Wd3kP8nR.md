---
# Allowed version bumps: patch, minor, major
profile: patch
---

Fixed the user profile component so a profile field is shown only when that exact field has been made public.

Previously a field could also be turned on by another published property whose name merely contained its name. No property shipped with Jahia has such a name, so profiles displayed today are unaffected.
