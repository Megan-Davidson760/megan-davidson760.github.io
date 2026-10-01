# _config.yml — fields to change

Don't replace your whole _config.yml with this — just find these specific
keys in the file the template gives you and change their values to the
ones below. Everything else in that file (theme settings, analytics,
comments, etc.) can stay as the template set it.

```yaml
title: "Megan Davidson"
name: "Megan Davidson"
description: "PhD researcher in Criminology, University of Manchester"

url: "https://<your-github-username>.github.io"   # must match the repo name exactly
# baseurl: ""                                       # leave empty unless your repo is NOT named <username>.github.io
repository: "<your-github-username>/<your-github-username>.github.io"

author:
  name: "Megan Davidson"
  avatar: "profile.jpg"   # drop a square photo into /images/ and reference it here
  bio: "PhD researcher in Criminology at the University of Manchester, studying the spatial and architectural dimensions of incarceration."
  location: "Manchester, UK"
  email: "megan.davidson@manchester.ac.uk"
  links:
    - label: "Email"
      icon: "fas fa-fw fa-envelope-square"
      url: "mailto:megan.davidson@manchester.ac.uk"
    - label: "LinkedIn"
      icon: "fab fa-fw fa-linkedin"
      url: "https://www.linkedin.com/in/megan-d-01986218b/"
    - label: "ORCID"
      icon: "ai ai-orcid"
      url: "https://orcid.org/0009-0005-0237-1272"
```

Notes:
- The `ai ai-orcid` icon needs Academicons, which the template already
  ships with — you don't need to install anything extra for it to show up.
- If you'd rather use your Gmail as the public contact instead of your
  Manchester address, just swap the two `email` values above.
- `url` and `repository` are the two fields people most often get wrong —
  both need to match your actual repo name exactly, or GitHub Pages will
  build the site at the wrong address and links/assets will break.
