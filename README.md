[![Node.js CI](https://github.com/nurikk/zigbee2mqtt-frontend/actions/workflows/node.js.yml/badge.svg)](https://github.com/nurikk/zigbee2mqtt-frontend/actions/workflows/node.js.yml)
[![codebeat badge](https://codebeat.co/badges/5ca1254f-569b-4ec0-99fa-fe6f0fa2896b)](https://codebeat.co/projects/github-com-nurikk-zigbee2mqtt-frontend-dev)

# Screenshots

![](images/screenshot_home.png)
![](images/screenshot_map.png)

# Develop

Install dependencies

```bash
npm install
````

Develop using mock data

```bash
npm run start
open http://localhost:3030/
````

Develop using your z2m instance

```bash
Z2M_API_URI="ws://192.168.1.200:8080" npm run start
open http://localhost:3030/
```

# Build

```bash
npm install
npm run build //compiled files at ./dist
```

# Sponsors

[JetHome](http://jethome.ru/)


