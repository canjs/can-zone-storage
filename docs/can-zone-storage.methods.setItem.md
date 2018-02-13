@function {Object} can-zone-storage.setItem
@parent can-zone-storage.methods

@signature `setItem(key, value)`

Stores keyed data in the current data store.

```javascript
import zoneStorage from "can-zone-storage";

const value = 'Store me';

zoneStorage.setItem('key-name', value);
```

@param {String} key The key name under which the data will be stored.
@param {Any} value The data to be stored.