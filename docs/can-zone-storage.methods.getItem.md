@function {Object} can-zone-storage.getItem
@parent can-zone-storage.methods

@signature `getItem(key)`

Stores keyed data in the current data store.

```js
import zoneStorage from "can-zone-storage";

const test = zoneStorage.getItem( "key-name" ); // test === undefined

const value = "Store me";

zoneStorage.setItem( "key-name", value );
zoneStorage.getItem( "key-name" ); // test === 'Store me'

```

@param {String} key The key name from which the data will be retrieved.