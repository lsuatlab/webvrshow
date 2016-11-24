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

3. `jekyll build`
4. `git ftp push`

Repeat steps 3 and 4 after setting up git-ftp.
