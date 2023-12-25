# sariot-countries

A ReactJS hook to get the country information.

## 🫶 Support
Liked it? You can show your support with a STAR(⭐).


## How to use it?

You can use the project in this way:

### Install
```bash
# with npm
npm install sariot-countries

# with yarn
yarn add sariot-countries
```

### Usage

- Import the package in your app:
```js
import {useCountry} from 'sariot-countries';
```
- Get the country information from the hook:
```js
const {loading, error, country} = useCountry('Bangladesh')'
```