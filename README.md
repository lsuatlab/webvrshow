##Site for immersive expressions.

Helpful to use git-ftp to push.

`brew install git-ftp`

Add the following to .git/config

```
[git-ftp]
	url = ftp.siggraphdigitalarts.hosting.acm.org
	user = immersiveexpressions@siggraphdigitalarts.hosting.acm.org
	syncroot = _site/
```

`git ftp push`
