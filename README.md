# memopad

## Creation/Initialization
```bash
vue create memopad
cd memopad
npm install --save-dev nwjs-builder-phoenix
./node_modules/.bin/run .
npm install --save-dev nw@sdk

```

```json
// package.json
{
  "name": "memopad",
  "main": "http://localhost:8080", // ➕ Add "main" entry
  "scripts": {
    "serve": "vue-cli-service serve",
    "build": "vue-cli-service build",
    "nw-serve": "nw ." // ➕ Add "nw-serve" entry 📛 (DOESN'T WORK FOR ME)
  },
}
```


## 
* win
* mac
* linux
* x86
* x64
* chrome-app


## WSL Workaround
```bash
whereis powershell #to find location
# mountedPowershellLocation/powershell.exe ./node_modules/.bin/run .
/mnt/c/WINDOWS/System32/WindowsPowerShell/v1.0/powershell.exe ./node_modules/.bin/run .
```
## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

###⭐ Compiles and minifies for production (WIN 64 BIT)
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
