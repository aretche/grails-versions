![Grails Versions](https://github.com/aretche/grails-versions/workflows/Grails%20Versions/badge.svg?branch=master)

Grails Versions (rest-api profile)
---
Adapted from Søren Berg Glasius project (https://github.com/sbglasius/grails-versions).

Handy repo/script to compare fresh `create-app --profile=rest-api` versions of Grails 3 and up so you can see what changed.

Just compare across tags:
* <https://github.com/aretche/grails-versions/compare/3.1.0...3.2.0>
* <https://github.com/sbglasius/grails-versions/compare/4.0.0...4.0.13>
* <https://github.com/sbglasius/grails-versions/compare/4.0.13...5.2.4>

From the git cli:

```bash
git diff 4.0.13..5.2.4
```

To add versions make pull-requests with new versions in versions.txt

A GitHub Action will rebuild the tags with all versions in versions.txt
