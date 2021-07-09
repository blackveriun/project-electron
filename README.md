


<details>
 <summary><b> Iniciando un proyecto en electron  🔨 </b></summary>
 </details>

---
<br>

> Comandos: <br>
> `npm init -y` <br>
> `npm i electron electron-reload`

<br>

> Remplazar el `package.json` <br>

```javascript
 {
  "name": "project-electron",
  "version": "1.0.0",
  "description": "Comandos",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "keywords": [],
  "author": "Blackveriun",
  "license": "ISC",
  "dependencies": {
    "electron": "^13.1.6",
    "electron-reload": "^1.5.0"
  }
}
  ```
  <br>

> por este otro `package.json` <br>
> o tambien puede hacer cambios en main y en test
```javascript
 {
  "name": "project-electron",
  "version": "1.0.0",
  "description": "Comandos",
  "main": "src/index.js",
  "scripts": {
    "start": "electron ."
  },
  "keywords": [],
  "author": "Blackveriun",
  "license": "ISC",
  "dependencies": {
    "electron": "^13.1.6",
    "electron-reload": "^1.5.0"
  }
}
  ```
  > Comando final para iniciar la aplicacion: <br>
> `npm start` <br>
-------------------------------------------
