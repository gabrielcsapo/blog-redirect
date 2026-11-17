# blog-redirect

Sends old `blog.gabrielcsapo.com` links to the same path on `www.gabrielcsapo.com`.

GitHub Pages serves `404.html` for every path that isn't a file here, and that page
forwards the visitor, keeping the path, query, and hash. `index.html` is the same page
for the root address.

Needs one DNS record: CNAME, host `blog`, value `gabrielcsapo.github.io.`
