Requirements:
- pip install mkdocs
- pip install markdown-include

Building the docs:
```
mkdocs build --clean
```

Build and serve the docs local (http://0.0.0.0:8000):
```
mkdocs serve
```

Build and deploy to GitHub (via gh-pages):
```
mkdocs gh-deploy --clean
```