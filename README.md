# Submodule Mapping Test

This project demonstrates mapping NodeJS submodules as named imports with wildcard substituion.

## Usage

```
git clone git@github.com:besworks/submodule-mapping.git
npm run start
```

There are no dependencies to install, just run the package and observe the console output. You will notice how all the nested submodule exports are available. Each nested path contains an `index.js` file which exports it's siblings. You can see how they are imported in `./common/index.js`.