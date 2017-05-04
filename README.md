# API Docs

To update the docs, edit `apiary.apib`, then run:

```bash
sudo npm install -g aglio

aglio --theme-variables slate -i apiary.apib -o html/index.html
```

That will compile the API Blueprint file into HTML. You can view the file at localurl.dev/deploynaut/docs/en/api/html/index.html.

Eventually this will be properly integrated with Apiary and such maybe.
