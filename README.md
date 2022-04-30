# NUSspli
Install content directly from the Nintendo Update Servers to your Wii U.

# Features
- Download titles from Nintendos servers (NUS).
- Install the downloaded titles to external or internal storage.
- Includes a keygen!
- Create fake tickets at will or if not found.
- Shows the download speed.
- On screen keyboard.
- Can download anything available on the NUS.
- Custom folder names for downloaded titles.

# Install
To install the app, download and unzip the contents of the [latest release](https://github.com/V10lator/NUSspli/releases) and depending on how you will run the app, follow the next steps:

### Aroma
- Move NUSspli.wuhb to (SD:/wiiu/apps/).
- Run it from the HOME Menu.

### Channel
- Move the folder to (SD:/install/) and install it with WUPInstaller.
- Run it from the HOME Menu.

### HBL
- Move the folder to (SD:/wiiu/apps/).
- Run the app from HBL through Haxchi, Browserhax or any exploit you want.

# Building
- On Linux/WSL/Mac, install devkitPro.
- Install WUT with devktpros pacman.
- Install [libiosuhax](https://github.com/wiiu-env/libiosuhax) and [librpxloader](https://github.com/wiiu-env/librpxloader) from wiiu-env.
- Clone the repo.
- Open the folder in a terminal and type `./build.sh`.
- If everything goes fine, you will have the resulting folder "zips".

# Building with docker
- Use `docker build -t nussplibuilder .` to build the container
- Use `docker run -it --rm -v ${PWD}:/project nussplibuilder make` to build NUSspli

# Info
NUSspli is based on [WUPDownloader](https://github.com/Pokes303/WUPDownloader) by Pokes303.
