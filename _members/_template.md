---
# Template for new members: copy to _members/<first-name>-<last-name>.md
# (lowercase ASCII with hyphens, e.g. asa-oberg.md), which becomes your profile
# URL. Files starting with "_" are not published.
#
# This file is public on GitHub; everything but comments is also published on
# the website, as is your GitHub avatar if you provide a GitHub handle but no
# photo. By submitting it, you consent to this publication of your personal data
# under the GDPR. To withdraw consent, remove your file (pull request) or ask a
# repository owner.

# --- Required -----------------------------------------------------------------

first_name: "Åsa"
last_name: "Öberg"

# Swedish organizations you work for or within, ordered from most specific to
# most general: research groups, (infrastructure) units and (core) facilities,
# platforms, and larger organizations such as research infrastructures. List
# site-bound organizations (e.g. your university or company) last. Do not list
# departments, divisions, or (international) networks and communities; mention
# those in the free text after the closing "---".
#
# Use keys from _organizations/ (file name without .md); add missing ones based
# on _organizations/_template.md.
affiliations:
  - biif # unit
  - nbis # platform
  - scilifelab # research infrastructure
  - uu # site-bound organization (university)

city: "Uppsala" # where you work

# --- Optional (leave empty to not publish) ------------------------------------

# Photo of yourself that you have the right to publish: square (1:1), 400x400 to
# 800x800 pixels, JPEG, PNG, or WebP, at most 200 kB. Add it to
# assets/images/members/, named like this file (e.g. asa-oberg.jpg). Without a
# photo, your GitHub avatar is shown if you provide a GitHub handle, otherwise
# your initials.
photo: # file name only, e.g. asa-oberg.jpg

email: # e.g. asa.oberg@example.org
website: # full URL, e.g. https://example.org
orcid: # iD only, e.g. 0000-0002-1825-0097
github: # handle only, e.g. octocat

# Free text after the closing "---" appears on your profile page. Don't repeat
# the fields above. Markdown and Liquid are processed, so avoid "{{" and "{%".
---
