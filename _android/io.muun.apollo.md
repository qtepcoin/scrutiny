---
wsId: muun
title: Muun - Bitcoin and Lightning Wallet
altTitle: 
authors:
- leo
users: 50000
appId: io.muun.apollo
appCountry: 
released: 2017-04-25
updated: 2022-03-22
version: '49.2'
stars: 4.5
ratings: 650
reviews: 69
size: 65M
website: https://muun.com
repository: https://github.com/muun/apollo
issue: https://github.com/muun/apollo/issues/54
icon: io.muun.apollo.png
bugbounty: 
meta: ok
verdict: nonverifiable
date: 2022-03-24
signer: 
reviewArchive:
- date: 2021-10-09
  version: '46.10'
  appHash: e7504467c314b576f5f0c45eeb135396f4d771f976e886bc9b0e1111f1172ff8
  gitRevision: 0ad5c7d69a32e48712b94cb7d7572b122ad0e49c
  verdict: nonverifiable
- date: 2021-04-06
  version: '45.2'
  appHash: 292776e270739d37b9307465cbddfc11068813078d9633035d74ae67f322a3b2
  gitRevision: 707ff239df150e0b2d6810e2444e495e2ca4c174
  verdict: nonverifiable
- date: 2019-12-29
  version: beta-36.2
  appHash: 
  gitRevision: e5bd20b29118aaefc8abe66f03c728a834be9984
  verdict: nonverifiable
twitter: MuunWallet
social: 
redirect_from:
- /io.muun.apollo/
- /posts/io.muun.apollo/

---

With
[our own verification script](https://gitlab.com/walletscrutiny/walletScrutinyCom/-/blob/master/scripts/test/android/io.muun.apollo.sh)
we get these results:

```
===== Begin Results =====
appId:          io.muun.apollo
signer:         026ae0ac859cc32adf2d4e7aa909daf902f40db0b4fe6138358026fd62836ad1
apkVersionName: 49.1
apkVersionCode: 901
verdict:        
appHash:        c2121cdb8f6a4a3e11470ce7787cda2eb6c1d1df28b987d50a4ab39b82d3c3ae
commit:         82575d702e57940f184656a8efd83e5f5a336831

Diff:
Files /tmp/fromPlay_io.muun.apollo_901/classes2.dex and /tmp/fromBuild_io.muun.apollo_901/classes2.dex differ
Files /tmp/fromPlay_io.muun.apollo_901/classes.dex and /tmp/fromBuild_io.muun.apollo_901/classes.dex differ
Only in /tmp/fromPlay_io.muun.apollo_901/META-INF: APOLLORE.RSA
Only in /tmp/fromPlay_io.muun.apollo_901/META-INF: APOLLORE.SF
Only in /tmp/fromPlay_io.muun.apollo_901/META-INF: MANIFEST.MF
Files /tmp/fromPlay_io.muun.apollo_901/resources.arsc and /tmp/fromBuild_io.muun.apollo_901/resources.arsc differ

Revision, tag (and its signature):
object 82575d702e57940f184656a8efd83e5f5a336831
type commit
tag v49.1
tagger acrespo <alvaro.andres.crespo@gmail.com> 1647637865 -0300

v49.1
===== End Results =====
```

Sadly that is worse than last time. In fact here, their own verification script
should come to the same conclusion: **not verifiable**.
