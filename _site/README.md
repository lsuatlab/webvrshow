##Site for immersive expressions show

Helpful to setup git-ftp to push:

1. `brew install git-ftp`
2. Add the following to .git/config

```
[git-ftp]
	url = ftp.siggraphdigitalarts.hosting.acm.org
	user = immersiveexpressions@siggraphdigitalarts.hosting.acm.org
	syncroot = _site/
```
To update the site:

1. `jekyll build`
2. `git commit -m "updated"`
3. `git ftp push`

To automatically upload on a git push you could even put the following inside of .git/hooks/pre-push:

```
#!/bin/sh
git ftp push
```
Then to update the site you only need to: `git push`