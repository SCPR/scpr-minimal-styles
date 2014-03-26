## SCPR Minimal Stylesheet

Static assets which make up our "minimal" template. This was extracted from the scpr.org asset pipeline so we didn't have to reference those unreliable asset paths anymore.

This is hosted at http://media.scpr.org/static/styles/scpr-minimal/

### Deployment
This repository is cloned on media. To deploy, you need your public key added to kpcc@media's public keys.

Deploy with the deploy script:

```
./deploy
```

Note that this pulls from github, so you'll need to push to github first.
