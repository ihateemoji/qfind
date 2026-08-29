# qfind XBPS Package

This repository contains files for packaging qfind for Void Linux using the XBPS package manager.

### Installation

1. Clone this repository:
   ```sh
   git clone https://github.com/ihateemoji/qfind.git
   ```
2. Copy the directory to the `srcpkgs` directory in your Void Packages repository:
   ```sh
   cp -r qfind /path/to/void-packages/srcpkgs/
   ```
3. Build the package:
   ```sh
   ./xbps-src pkg qfind
   ```
4. Install the package:
   ```sh
   sudo xbps-install --repository=hostdir/binpkgs qfind
   ```
