<img alt="React Native Performant Marker" src="assets/logo.png" width="1050"/>

[![Battle Tested ✅](https://img.shields.io/badge/-Battle--Tested%20%E2%9C%85-03666e?style=for-the-badge)](https://github.com/WrathChaos/react-native-performant-marker)

[![React Native Performant Marker](https://img.shields.io/badge/-React%20Native%20Library%20Boilerplate-lightgrey?style=for-the-badge)](https://github.com/WrathChaos/react-native-performant-marker)

[![npm version](https://img.shields.io/npm/v/react-native-performant-marker.svg?style=for-the-badge)](https://www.npmjs.com/package/react-native-performant-marker)
[![npm](https://img.shields.io/npm/dt/react-native-performant-marker.svg?style=for-the-badge)](https://www.npmjs.com/package/react-native-performant-marker)
![Platform - Android and iOS](https://img.shields.io/badge/platform-Android%20%7C%20iOS-blue.svg?style=for-the-badge)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![styled with prettier](https://img.shields.io/badge/styled_with-prettier-ff69b4.svg?style=for-the-badge)](https://github.com/prettier/prettier)

<p align="center">
  <img alt="React Native Performant Marker"
        src="assets/Screenshots/marker.png" height="300" width="300" />
</p>

# Installation

Add the dependency:

```ruby
npm i react-native-performant-marker
```

## Peer Dependencies

###### IMPORTANT! You need install them

```js
"react-native-maps": ">= 0.26.1",
```

# Usage

## Import

```js
import PerformantMarker from "react-native-performant-marker";
```

## Basic Usage

This is just an example of usage PerformantMarker.
You can simply use the MapView.Marker's every prop and same usage.
Inside of the FastImage is just a recommendation for CustomMarker image usage. It performs the best on react-native community.

```js
<PerformantMarker
  title="Test"
  key="some-key-id"
  tracksViewChanges={false}
  onPress={() => {}}
  coordinate={{
    latitude,
    longitude,
  }}
>
  <FastImage source={markerIcon} style={styles.markerStyle} />
</PerformantMarker>
```

## Credits

Thank you so much for the cool icon by (Flaticon)[https://www.flaticon.com/free-icon/landscape_3069254]

## Author

FreakyCoder, kurayogun@gmail.com

## License

React Native Performant Marker is available under the MIT license. See the LICENSE file for more info.
