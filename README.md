# Build Revanced

## Step 1: Version Check 
- [Poll repos](https://docs.github.com/en/actions/using-workflows/workflow-syntax-for-github-actions#onschedule):
  - https://github.com/revanced/revanced-patches
  - https://github.com/revanced/revanced-cli
  - https://github.com/revanced/revanced-integrations
- Write `.env` with latest versions
- [Tag new version](https://github.com/marketplace/actions/github-tag)

## Step 2: Build APK
- [On Tag](https://docs.github.com/en/actions/using-workflows/workflow-syntax-for-github-actions#onpushbranchestagsbranches-ignoretags-ignore)
- [Setup JRE](https://github.com/marketplace/actions/setup-java-jdk)
- [Load `.env`](https://github.com/aarcangeli/load-dotenv)
- Grab Revanced files
- Grab YouTube APK
- Build Revanced
- Upload Signed Revanced APK
