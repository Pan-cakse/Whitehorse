# Whitehorse
Purpur-based fork for BromineMC. 

## Building
You will need:

- Java JDK 17 or higher. (e.g. [Temurin](https://adoptium.net/))
- 4 GB of available RAM.
- A bit of storage.

How to:
- Ensure your JDK is set up properly. (i.e. JDK path is in `JAVA_HOME` environment variable)
- Clone this repo or download it. (e.g. via `git clone https://github.com/BromineMC/Whitehorse`)
- Open the terminal (command prompt) there.
- Run `./gradlew applyPatches`.
- Run `./gradlew createReobfPaperclipJar`.
- Grab JARs from `/build/libs/`

## License
This project is licensed under [GNU General Public License v3.0](LICENSE).

## Features
This project is designed to be server-dependendant. (i.e. it's **not a community-oriented fork**)
It offers:
- Simple version fetcher. (No requests to any update servers)
- Custom item max stack size via NBT tag. (`Whitehorse.MaxStackSize`)
- Removing spam logs from "moving too quickly" or "moving wrongly".
- Removing chat reports and "unsecure chat" toast.
- Readding legacy (1.19.3) blast protection. (Disabled by default)
