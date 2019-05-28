---
layout: single
title: Here is your sexy .bashrc file
---

## Section 1: Corporate Proxy

### If you are in the native Ubuntu universe
```bash
export http_proxy=http://[your-corporate-proxy]:[port]
export https_proxy=https://[your-corporate-proxy]:[port]
export HTTP_PROXY=http://[your-corporate-proxy]:[port]
export HTTPS_PROXY=http://[your-corporate-proxy]:[port]
```

### Just in case you are in the C shell universe
```bash
setenv http_proxy http://[your-corporate-proxy]:[port]
setenv https_proxy https://[your-corporate-proxy]:[port]
setenv HTTP_PROXY http://[your-corporate-proxy]:[port]
setenv HTTPS_PROXY http://[your-corporate-proxy]:[port]
```

## Section 2: Git

```bash
alias clone_[your most used project]="git clone https://github.com/[your username]/[repository name]"

alias quick_git_push="git add -A && git commit -m \"quick update\" && git push"

alias save_git_password="git config credential.helper store"
```

<br/>

<iframe data-aa="1180220" src="//acceptable.a-ads.com/1180220" scrolling="no" style="border:0px; padding:0; overflow:hidden" allowtransparency="true"></iframe>
