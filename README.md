##Site for immersive expressions show

Helpful to use git-ftp to push:

1. `brew install git-ftp`

2. Add the following to .git/config

```
[git-ftp]
	url = ftp.siggraphdigitalarts.hosting.acm.org
	user = immersiveexpressions@siggraphdigitalarts.hosting.acm.org
	syncroot = _site/
```

3. `git ftp push`
