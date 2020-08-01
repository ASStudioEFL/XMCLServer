# XMCL Update API

### 1. How to get XMCL

You can get XMCL from GitHub Repo: [XMCL](https://github.com/ASStudioEFL/XMCL)

For high-speed downloading, see [GitHub File Speed-Up](https://gh.efl.workers.dev) by [EFL](https://efl.pd2.ink) (me)

### 2. Change XMCL and Compile

Change the XMCL's code. Watch out, we use GPL v3 license.

Compile? Run gradlew.bat in Windows or gradlew in Linux. Very easily, right?

### 3. Setup your API!

**Fork the GitHub Repo from XMCLServer first!!!Don't forget!!!Change all the file in your GitHub Repo, not mine!!!!!**

See ./api/update_link, there's a explain:

|                        pack                         |               packsha1                |                       packxz                        |              packxzsha1               |            universal            |         version          |
| :-------------------------------------------------: | :-----------------------------------: | :-------------------------------------------------: | :-----------------------------------: | :-----------------------------: | :----------------------: |
| The link that can download .pack.gz-format launcher | Sha-1 of the .pack.gz-format launcher | The link that can download .pack.xz-format launcher | Sha-1 of the .pack.xz-format launcher | Where you publish your launcher | Version of your launcher |

After change the update_link, upload your launcher in ./XMCL directory. *./XMCL/excutable use to save the .exe or .jar XMCL. You can ignore it. ./sha1 use to save the sha-1 of files. You can ignore it too.*

### 4. Change the changelog

See ./changelog.html, write your changelog in it!

---

All finish!