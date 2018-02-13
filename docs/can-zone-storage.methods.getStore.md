@function {Object} can-zone-storage.getStore
@parent can-zone-storage.methods

@signature `getStore()`

Retrieves the current store.  

If the [can-zone] library has been imported, `getStore` returns the `CanZone.current.data` object.

```javascript
import zoneStorage from "can-zone-storage";
import Zone from "can-zone";
const store = zoneStorage.getStore();

store === window.CanZone.current.data // true
```

If the [can-zone] library has NOT been imported, `getStore` returns the internal [can-zone-storage.data] object.

```javascript
import zoneStorage from "can-zone-storage";
const store = zoneStorage.getStore();

store === zoneStorage.data // true
```
