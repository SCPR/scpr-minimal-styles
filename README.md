## SCPR Minimal Stylesheet

Static assets which make up our "minimal" template. This was extracted from the scpr.org asset pipeline so we didn't have to reference those unreliable asset paths anymore.

This is hosted at http://media.scpr.org/static/styles/scpr-minimal/

### Deployment
This repository is cloned on media. To deploy, you need your public key added to kpcc@media's public keys.

Then, add the repo as a remote:

```
git remote add live kpcc@media:/home/kpcc/media-www/static/styles/scpr-minimal
```

And deploy with:

```
git push live
```
