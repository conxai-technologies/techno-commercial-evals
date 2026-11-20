# Technical & commercial evaluation

DAMAC bid levelling dashboard, served at https://conxai-technologies.github.io/techno-commercial-evals/.

`index.html` is password protected with [StatiCrypt](https://github.com/robinmoisson/staticrypt): the page, its code and its data are AES-encrypted and only decrypt in the browser with the password. Ask the CONXAI team for access.

It is a static snapshot of the results in DocNostic. It is rebuilt from the docs-ui `bidLevelling` module (`scripts/build-bid-levelling-static.mjs`) and encrypted before it is committed. Never commit an unencrypted build or the data snapshot to this public repo.
