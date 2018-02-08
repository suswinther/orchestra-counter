# Orchestra Counter

This project is the standard Orchestra Counter Application found in Orchestra 7

## Getting Started

These instructions will help you get started running this project on your local machine for,
1. Development
    1. Local Development
    2. Remote Development
2. Creating the Production Build
3. Create the war package for distribution

## What is include in this project

1. Web App
2. Utts
3. Language properties file

## Prerequisites

Make sure you have installed 
1. Node 8 or above.
2. LiveReload on Chrome (Optional) - Required only for development
    https://chrome.google.com/webstore/detail/livereload/jnihajbhpnppcggbcgedagnkighmdlei

## Development

1. Clone the project
2. Run the following command to install all dependencies

```
npm install
```

### Local Development

In the case you have Orchestra installed on your local machine.

To start development run the following command

```
npm start
```

Visit localhost:1337 to see the application. (If you have LiveReload installed. You should see a chrome browser open and launch the application. Please make sure live reload is enabled on the browser.)

### Remote Development

In the case you have Orchestra installed on a remote machine.

Create a config.gulp.json file in the root of the project and make sure to add the remote ip,port and host details in the structure shown below.

```
{
    "proxy": {
        "host": "10.2.2.210",
        "port": "8080",
        "protocol": "http"
    }
}
```

To start development run the following command

```
npm start
```

Visit localhost:1337 to see the application. (If you have LiveReload installed. You should see a chrome browser open and launch the application. Please make sure live reload is enabled on the browser.)

## Creating the Production Build

Comming soon...

## Creating the war package for distribution

To create the war package run the following command

```
npm run war
```
You will find the war package and the default properties file in the dist folder.

## License

### Apache Font License
Copyright 2018 Qmatic

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
