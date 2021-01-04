# Sparky CLI [![made-with-Go](https://img.shields.io/badge/Made%20with-Go-1f425f.svg)](http://golang.org) 

Sparky is a faithful data dog that runs everywhere collecting sensor data delivers it to the Aquaponics AI cloud.  For full documentation please check out the [developer docs](https://docs.aquaponics.ai).

![Sparky Demo](/images/sparky-demo.gif)

### Installing with Homebrew

If you're on Mac or using some other homebrew enabled device you can install the application using our [homebrew](https://brew.sh/) tap.

```sh
brew tap aquaponics-ai/homebrew-tap
brew install sparky
```

### Installing with Scoop

If you're on a Windows machine and use a package manager like [Scoop](https://github.com/lukesampson/scoop) we've got you covered.

```sh
scoop bucket add stripe https://github.com/aquaponics-ai/scoop-sparky-cli.git
scoop install sparky
```

## Usage

Installing the CLI provides access to the `sparky` command.

```sh
sparky [command]

# Run `--help` for detailed information about CLI commands
sparky [command] help
```

Created with ❤️ by [Aquaponics AI](https://aquaponics.ai/?ref=github.com)
