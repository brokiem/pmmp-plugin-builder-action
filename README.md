## PMMP Plugin Builder (PHAR)
You can make phar of your plugin with GitHub Actions

### How to use
1. Create folder/directory ``.github/workflows``
2. Copy ``phar-build.yml`` from this repo to ``.github/workflows`` directory
3. Activate ``Actions`` on  your plugin repo
4. Trigger the actions

### Info
- If you don't want to make release the phar, you can delete ``prepare-release`` job.
- Download the phar from actions artifact
- You are free to modify anything from ``phar-build.yml``

### Question?
You can open issue to ask your question