# ℤrxiv /ˈziɹkaɪv/: work in progress
**zrxiv** is a Chrome / Firefox / Edge browser extension that logs and organizes your visited arxiv.org articles. **zrxiv** uses your personal Github repository as a database and Github Pages to generate a static pretty-looking article list. In order to use **zrxiv** you will need to fork a Github repository and provide Github credentials to the **zrxiv** browser extension (so that it can save information about your visited arxiv articles in form of commits).

### Install
1. Install the **zrxiv** browser extension from [Chrome Web Store](https://chrome.google.com/webstore/detail/oleagdnnlndgacibahnhoedjlcdlicoo/publish-accepted?authuser=0&hl=en-US) or [Mozilla Add-ons](https://addons.mozilla.org/)
2. [Fork](https://github.com/zrxiv/zrxiv/fork) this repo
3. Go to **zrxiv** extension options and enter the URL to your forked repo and a Github [personal access token](https://github.com/settings/tokens)
4. A zrxiv pane will appear on top of `https://arxiv.org/abs/*` pages, the saved papers are available at your repo's [Github Pages](../../settings/pages/status): `https://YOURGITHUBUSERNAME.github.io/zrxiv`

### Update
```shell
git clone https://github.com/YOURGITHUBUSERNAME/zrxiv
cd zrxiv
git fetch upstream
git merge upstream/gh-pages
git push
```
