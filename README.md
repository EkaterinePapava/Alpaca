<p align="center"><img src="https://jeffser.com/images/alpaca/logo.svg">
<h1 align="center">Alpaca</h1>

<p align="center">Alpaca is an <a href="https://github.com/ollama/ollama">Ollama</a> client where you can manage and chat with multiple models, Alpaca provides an easy and beginner friendly way of interacting with local AI, everything is open source and powered by Ollama.</p>

<p align="center">You can also use third party AI providers such as Gemini, ChatGPT and more!</p>

<p align="center"><a href='https://flathub.org/apps/com.jeffser.Alpaca'><img width='190' alt='Download on Flathub' src='https://flathub.org/api/badge?locale=en'/></a></p>

---

> [!WARNING]
> This project is not affiliated at all with Ollama, I'm not responsible for any damages to your device or software caused by running code given by any AI models.

> [!IMPORTANT]
> Please be aware that [GNOME Code of Conduct](https://conduct.gnome.org) applies to Alpaca before interacting with this repository.

## Features!

- Talk to multiple models in the same conversation
- Pull and delete models from the app
- Image recognition
- Document recognition (plain text files)
- Code highlighting
- Multiple conversations
- Notifications
- Import / Export chats
- Delete / Edit messages
- Regenerate messages
- YouTube recognition (Ask questions about a YouTube video using the transcript)
- Website recognition (Ask questions about a certain website by parsing the url)

## Screenies

Normal conversation | Image recognition | Rich text formatting | Integrated script execution | YouTube transcription
:------------------:|:-----------------:|:--------------------:|:---------------------------:|:--------------------:
![screenie1](https://jeffser.com/images/alpaca/screenie1.png) | ![screenie2](https://jeffser.com/images/alpaca/screenie2.png) | ![screenie3](https://jeffser.com/images/alpaca/screenie3.png) | ![screenie4](https://jeffser.com/images/alpaca/screenie5.png) | ![screenie5](https://jeffser.com/images/alpaca/screenie6.png)

## Installation

### Flathub

You can find the latest stable version of the app on [Flathub](https://flathub.org/apps/com.jeffser.Alpaca)

### Flatpak Package

Everytime a new version is published they become available on the [releases page](https://github.com/Jeffser/Alpaca/releases) of the repository

### Snap Package

You can also find the Snap package on the [releases page](https://github.com/Jeffser/Alpaca/releases), to install it run this command:
```BASH
sudo snap install ./{package name} --dangerous
```
The `--dangerous` comes from the package being installed without any involvement of the SnapStore, I'm working on getting the app there, but for now you can test the app this way.

### MacOS

Please read the [wiki page](https://github.com/Jeffser/Alpaca/wiki/MacOS) for MacOS.

### Nix

Alpaca is also available in Nixpkgs. See [package info](https://search.nixos.org/packages?channel=unstable&show=alpaca&from=0&size=50&sort=relevance&type=packages&query=alpaca) for installation instructions.

Notes:

1. The package is not maintained by the author, but by [@Aleksanaa](https://github.com/Aleksanaa), thus any issues uncertain whether related to packaging or not, should be reported to [Nixpkgs issues](https://github.com/NixOS/nixpkgs/issues/new/choose).
2. Alpaca is automatically updated in Nixpkgs, but with a delay, and new updates will only be available after testing.
3. Alpaca in Nixpkgs does not come with sandboxing by default, which means if you want to directly execute the scripts generated by ollama (without even reviewing them first), we do not provide any isolation to prevent you from shooting yourself in the foot. You can still leverage [Nixpak](https://github.com/nixpak/nixpak) or [Firejail](https://wiki.nixos.org/wiki/Firejail) for a convenient sandboxing.

### Building Git Version

Note: This is not recommended since the prerelease versions of the app often present errors and general instability.

1. Clone the project
2. Open with Gnome Builder
3. Press the run button (or export if you want to build a Flatpak package)

## Translators

Language               | Contributors
:----------------------|:-----------
🇷🇺 Russian              | [Alex K](https://github.com/alexkdeveloper)
🇪🇸 Spanish              | [Jeffry Samuel](https://github.com/jeffser)
🇫🇷 French               | [Louis Chauvet-Villaret](https://github.com/loulou64490) , [Théo FORTIN](https://github.com/topiga)
🇧🇷 Brazilian Portuguese | [Daimar Stein](https://github.com/not-a-dev-stein) , [Bruno Antunes](https://github.com/antun3s)
🇳🇴 Norwegian            | [CounterFlow64](https://github.com/CounterFlow64)
🇮🇳 Bengali              | [Aritra Saha](https://github.com/olumolu)
🇨🇳 Simplified Chinese   | [Yuehao Sui](https://github.com/8ar10der) , [Aleksana](https://github.com/Aleksanaa)
🇮🇳 Hindi                | [Aritra Saha](https://github.com/olumolu)
🇹🇷 Turkish              | [YusaBecerikli](https://github.com/YusaBecerikli)
🇺🇦 Ukrainian            | [Simon](https://github.com/OriginalSimon)
🇩🇪 German               | [Marcel Margenberg](https://github.com/MehrzweckMandala)
🇮🇱 Hebrew               | [Yosef Or Boczko](https://github.com/yoseforb)
🇮🇳 Telugu               | [Aryan Karamtoth](https://github.com/SpaciousCoder78)
🇮🇹 Italian              | [Edoardo Brogiolo](https://github.com/edo0)
🇯🇵 Japanese             | [Shidore](https://github.com/sh1d0re)
🇳🇱 Dutch                | [Henk Leerssen](https://github.com/Henkster72)
🇮🇩 Indonesian           | [Nofal Briansah](https://github.com/nofalbriansah)

Want to add a language? Visit [this discussion](https://github.com/Jeffser/Alpaca/discussions/153) to get started!

---

## Thanks

- [not-a-dev-stein](https://github.com/not-a-dev-stein) for their help with requesting a new icon and bug reports
- [TylerLaBree](https://github.com/TylerLaBree) for their requests and ideas
- [Imbev](https://github.com/imbev) for their reports and suggestions
- [Nokse](https://github.com/Nokse22) for their contributions to the UI and table rendering
- [Louis Chauvet-Villaret](https://github.com/loulou64490) for their suggestions
- [Aleksana](https://github.com/Aleksanaa) for her help with better handling of directories
- [Gnome Builder Team](https://gitlab.gnome.org/GNOME/gnome-builder) for the awesome IDE I use to develop Alpaca
- Sponsors for giving me enough money to be able to take a ride to my campus every time I need to <3
- Everyone that has shared kind words of encouragement!

---

## Packaging Alpaca

If you want to package Alpaca in a different packaging method please read [this wiki page](https://github.com/Jeffser/Alpaca/wiki/Packaging-Alpaca).
