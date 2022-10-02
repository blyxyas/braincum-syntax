# Braincum Syntax

This is the syntax highlighting tool for the [Braincum esolang](https://github.com/qexat/braincum).

![Screenshot from 2022-10-01 23-46-01](https://user-images.githubusercontent.com/73757586/193429480-47c4dade-d15f-489e-a4a1-a5aef2b161c8.png)

## Installation

Currently the tool isn't on the Visual Studio Code Marketplace, so you'll have to download the `.vsix` file from *Releases* or package the source yourself.

### Downloading the binary

Head over to [*Releases*](https://github.com/blyxyas/braincum-syntax/releases) and download the binary from the latest release. Here you can choose from a `tar.gz` file or a `.zip` file, choose one.

When you've download the compressed file, uncompress it:

**`.zip`**

```
unzip <Downloaded file .zip>
```

(If you're using Windows you already know what to do)

**`.tar.gz`**

```
tar xzvf <Downloaded file .tar.gz>
```

**Both ways will leave you with a `.vsix` file.**

### Building from source

(If you get stuck, check the [VSCode docs](https://code.visualstudio.com/api/working-with-extensions/publishing-extension#vsce))

1. Clone the repo

<sup>(or download the zip file)</sup>

```bash
git clone https://github.com/blyxyas/braincum-syntax
```

2. Install the `vsce` Node.js CLI.

```bash
npm install -g vsce
```

3. Package the extension

```bash
cd braincum-syntax
vsce package
# braincum-syntax-<Version>.vsix generated
```

This will leave you with a `.vsix` file in the root directory of the repo.

### Installing the binary

1. Open VSCode
2. <kbd>Ctrl / ⌘</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd>
3. Write *"Extensions: Install from VSIX"*
4. This will open a file explorer, select the `.vsix` file you downloaded earlier.
5. **Enjoy your new extension!**

## Usage

Now you can open any `.bc` file and enjoy the syntax highlighting!

## License

Check the *LICENSE* file for licensing information.