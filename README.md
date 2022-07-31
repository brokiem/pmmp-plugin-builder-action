# PMMP Plugin Builder (PHAR)

With this github action script, you can make phar of your plugin and injecting virions with GitHub Actions easily. <br>
This script aims for users who want to create phar on their private plugin because they can't use poggit to generate
phar plugin.

## How to use

1. Create directory ``.github/workflows`` in your root repository
2. Copy ``phar-build.yml`` from this repo into your ``.github/workflows`` directory
3. Create file ``.libraries.yml`` if you're using virion(s) and then look at the example how to use it in this repo in
   the [.libraries.yml](https://github.com/brokiem/pm-plugin-builder-actions/blob/master/.libraries.yml)
   file
4. Activate ``Actions`` on your plugin repo if its disabled
5. Trigger the actions to execute the script
6. Done. You should have the generated phar now 👍🏻 🌟

## Information

- If you don't want to create release for the phar, you can delete ``prepare-release`` job.
- You can download the generated phar from actions artifact or repo release section
- This phar-builder support any pocketmine plugin version
- You are free to modify anything from ``phar-build.yml`` file

## Examples

- https://github.com/brokiem-pm-pl/PvPToggle/tree/pm4

## Question?

You can open issue to ask your question.