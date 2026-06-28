# Class `LocalData`

Manages local data storage and retrieval. Provides methods to set, get, and delete various types of data. This class is used to interact with the local data storage system.

## Methods

### `delete`

```lua
--- @param key string
--- @return any
function LocalData:delete(key)
```

Deletes the data associated with the specified key.

- **Static:** No
- #### Parameters:
  - **key:** `string`
- **Returns:** `any`

___

### `setBool`

```lua
--- @param key string
--- @param value boolean
--- @return any
function LocalData:setBool(key, value)
```

Sets a boolean value for the specified key.

- **Static:** No
- #### Parameters:
  - **key:** `string`
  - **value:** `boolean`
- **Returns:** `any`

___

### `setInteger`

```lua
--- @param key string
--- @param value integer
--- @return any
function LocalData:setInteger(key, value)
```

Sets an integer value for the specified key.

- **Static:** No
- #### Parameters:
  - **key:** `string`
  - **value:** `integer`
- **Returns:** `any`

___

### `setNumber`

```lua
--- @param key string
--- @param value number
--- @return any
function LocalData:setNumber(key, value)
```

Sets a number value for the specified key.

- **Static:** No
- #### Parameters:
  - **key:** `string`
  - **value:** `number`
- **Returns:** `any`

___

### `setString`

```lua
--- @param key string
--- @param value string
--- @return any
function LocalData:setString(key, value)
```

Sets a string value for the specified key.

- **Static:** No
- #### Parameters:
  - **key:** `string`
  - **value:** `string`
- **Returns:** `any`

___

### `setTable`

```lua
--- @param key string
--- @param table table
--- @return any
function LocalData:setTable(key, table)
```

Sets a table value for the specified key.

- **Static:** No
- #### Parameters:
  - **key:** `string`
  - **table:** `table`
- **Returns:** `any`

___

### `exists`

```lua
--- @param key string
--- @return boolean
function LocalData:exists(key)
```

Checks if the specified key exists in the local data.

- **Static:** No
- #### Parameters:
  - **key:** `string`
- **Returns:** `boolean`

___

### `existsAsType`

```lua
--- @param key string
--- @param sType string
--- @return boolean
function LocalData:existsAsType(key, sType)
```

Checks if the specified key exists in the local data and is of the specified type.

- **Static:** No
- #### Parameters:
  - **key:** `string`
  - **sType:** `string`
- **Returns:** `boolean`

___

### `getBool`

```lua
--- @param key string
--- @param defaultValue boolean
--- @return boolean
function LocalData:getBool(key, defaultValue)
```

Retrieves a boolean value associated with the specified key. If the key does not exist, returns the provided default value.

- **Static:** No
- #### Parameters:
  - **key:** `string`
  - **defaultValue:** `boolean`
- **Returns:** `boolean`

___

### `getInteger`

```lua
--- @param key string
--- @param defaultValue integer
--- @return integer
function LocalData:getInteger(key, defaultValue)
```

Retrieves an integer value associated with the specified key. If the key does not exist, returns the provided default value.

- **Static:** No
- #### Parameters:
  - **key:** `string`
  - **defaultValue:** `integer`
- **Returns:** `integer`

___

### `getNumber`

```lua
--- @param key string
--- @param defaultValue number
--- @return number
function LocalData:getNumber(key, defaultValue)
```

Retrieves a number value associated with the specified key. If the key does not exist, returns the provided default value.

- **Static:** No
- #### Parameters:
  - **key:** `string`
  - **defaultValue:** `number`
- **Returns:** `number`

___

### `getString`

```lua
--- @param key string
--- @param defaultValue string
--- @return string
function LocalData:getString(key, defaultValue)
```

Retrieves a string value associated with the specified key. If the key does not exist, returns the provided default value.

- **Static:** No
- #### Parameters:
  - **key:** `string`
  - **defaultValue:** `string`
- **Returns:** `string`

___

### `getTable`

```lua
--- @param key string
--- @param defaultValue table
--- @return table
function LocalData:getTable(key, defaultValue)
```

Retrieves a table value associated with the specified key. If the key does not exist, returns the provided default value.

- **Static:** No
- #### Parameters:
  - **key:** `string`
  - **defaultValue:** `table`
- **Returns:** `table`

___
```lua
--- @param key string
--- @return table
function LocalData:getTable(key)
```

Retrieves a table value associated with the specified key. If the key does not exist, returns an empty table.

- **Static:** No
- #### Parameters:
  - **key:** `string`
- **Returns:** `table`
