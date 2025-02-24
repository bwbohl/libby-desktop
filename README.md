<div align=center>

![Libby Desktop](./libby-mascot.svg)
# Libby Desktop

<a href="https://discord.gg/yf4UDea">
<img src="https://img.shields.io/discord/735879930348306554?color=631A35&logo=discord&logoColor=white" alt="Chat on Discord" />
</a>
<a href="https://github.com/Spiffily/coronado-app/releases">
<img  alt="Release" src="https://img.shields.io/badge/release-1.0.0-A61C49" />
</a>
<a href="https://snapcraft.io/coronado-app">
<img src="https://img.shields.io/badge/snap-0.0.0-29CFC3?logo=snapcraft&logoColor=white" alt="Snap Store" />
</a>

A simple Electron app to come as close as possible to providing a Linux desktop app for [Libby](https://www.overdrive.com/apps/libby/).

This app is equipped with all the wonderful features of an electron app, including Dark theme (from Gtk light/dark), media playback, and Dev Tools (`Ctl+Shift+I`). Please enjoy.

## Development
1. Clone the repository. `git clone https://github.com/Spiffily/libby-desktop && cd libby-desktop`
2. Install npm. `sudo apt-get install -y npm` on Ubuntu based OSes
3. Install latest electron. `npm install --save-dev electron`
4. Run the app. `npm start`

## Credits
The Libby icon was taken from this page for use as the app icon: https://www.overdrive.com/apps/libby/

The `libby-mascot.ico` was created using ImageMagick, by running:

```bash
convert -background transparent "libby-mascot.png" -define icon:auto-resize=16,24,32,48,64,72,96,128,256 "libby-mascot.ico"
```

The `libby-mascot.icns` was created using from an  higher resolution PNG of the SVG and then converted to icns with:

```bash
sips -s format icns -z 1024 1024 libby-mascot.iconset/libby-mascot_512x512@2x.png -o libby-mascot.icns
```


**Disclaimer: Libby is in no way, shape, or form the work of Spiffily Software. This app is only a simple electron package to allow you to read in a sort of desktop app.**

</div>
