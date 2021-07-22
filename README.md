# `@astuteo/prettier-config`

## Usage

**Install**:

_Note: If the project has our @astuteo/build-config 5.2+ installed, you do not need to install this package seperately. That is installed and kept up-to-date in that package._

```bash
$ yarn add --dev @astuteo/prettier-config
```

**Edit `package.json`**:

```jsonc
{
  // ...
  "prettier": "@astuteo/prettier-config"
}
```

**VSCode**

After installing the Prettier plugin, make sure in your settings it is set as the default formatter.

<img width="801" alt="CleanShot 2021-07-22 at 17 19 25@2x" src="https://user-images.githubusercontent.com/360177/126716660-63797c3a-74fe-4547-8f16-335cb81c3019.png">

After restarting, the plugin should pick up on our config. If not, you can set the config and the package:
```
./node_modules/@astuteo/prettier-config/index.json
./node_modules/prettier
```
