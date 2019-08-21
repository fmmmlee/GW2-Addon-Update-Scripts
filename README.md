# GW2-Addon-Update-Scripts
the scripts portion of my gw2 add-on updater, which evolved into a C# application to which these files were no longer relevant

Copied from GW2-UOAOM:

- Powershell Scripts (requires Powershell 3.0, does not require .NET)
  - Configurable: The scripts in this folder can be run individually or all at once, and each relies on the `dll_config.ini` file to get various settings used within the scripts. Using `update_all.bat` to perform all updates at once is recommended, though it requires Arc, GW2Radial, and d912pxy to all be installed.
  - Standalone: You should be able to download and run a single powershell script from this folder and have it work properly (assuming your script execution policy is set to allow them to run). To set naming preferences, game path, etc, you need to edit each individual script itself. These are meant more for testing or for those who don't care about an interface, or those who want to play with and edit the scripts without messing with a configuration file.
