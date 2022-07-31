## PMMP Plugin Builder (PHAR)
You can make phar of your plugin with GitHub Actions

### How to use
1. Create folder/directory ``.github/workflows``
2. Copy ``phar-build.yml`` from this repo to ``.github/workflows`` directory
3. Activate ``Actions`` on  your plugin repo
4. Trigger the actions

### Examples
- https://github.com/brokiem-pm-pl/PvPToggle/tree/pm4

### Info
- If you don't want to make release the phar, you can delete ``prepare-release`` job.
- Download the generated phar from actions artifact
- This plugin support both pm3 and pm4 version
- You are free to modify anything from ``phar-build.yml``

### Question?
You can open issue to ask your question