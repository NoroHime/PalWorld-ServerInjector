# Project is archived

This launcher should no longer be necessary, as UE4SS now uses dwmapi.dll to inject.
If a mod you use still wants you to copy a xinput dll, its probably outdated.

# PalWorld UE4SS Server Injector

Launcher for PalWorld Server that injects UE4SS.dll into the server process.
Also bundles required signatures.

## Installation

### Premade zip
- Extract the [latest release](https://github.com/N00byKing/PalWorld-ServerInjector/releases) to `<wherever your server is>/Pal/Binaries/Win64`

### Manual
- Extract the `UE4SS` standard package into `<wherever your server is>/Pal/Binaries/Win64`.
- Put `PalServerInject.exe`, and the `UE4SS_Signatures` folder in the same directory
- (Optional) To verify if its working it might be best to set `GuiConsoleVisible` in `UE4SS-settings.ini` to `1`

## Usage

Just run `PalServerInject.exe`.

## Credits

Injection logic by @crwn1337, [here](https://github.com/crwn1337/wine_injector)
