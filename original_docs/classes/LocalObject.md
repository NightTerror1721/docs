# Class `LocalObject`

## Properties

### `count`

```lua
---@type integer
LocalObject.count
```

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** No

___

### `[][string]: nil|number|string|boolean|LocalArray|LocalObject`

```lua
---@param index string
---@return nil|number|string|boolean|LocalArray|LocalObject
function LocalObject.__index(index)

---@param index string
---@param value nil|number|string|boolean|LocalArray|LocalObject
function LocalObject.__newindex(index, value)
```

- **Type:** `nil|number|string|boolean|LocalArray|LocalObject`
- **Read\-only:** No

## Methods

### `add`

```lua
--- @param key string
--- @param value nil|number|string|boolean|LocalArray|LocalObject
--- @return any
function LocalObject:add(key, value)
```

- **Static:** No
- #### Parameters:
  - **key:** `string`
  - **value:** `nil|number|string|boolean|LocalArray|LocalObject`
- **Returns:** `any`

___

### `get`

```lua
--- @param key string
--- @return nil|number|string|boolean|LocalArray|LocalObject
function LocalObject:get(key)
```

- **Static:** No
- #### Parameters:
  - **key:** `string`
- **Returns:** `nil|number|string|boolean|LocalArray|LocalObject`

___

### `hasKey`

```lua
--- @param key string
--- @return boolean
function LocalObject:hasKey(key)
```

- **Static:** No
- #### Parameters:
  - **key:** `string`
- **Returns:** `boolean`

___

### `remove`

```lua
--- @param key string
--- @return boolean
function LocalObject:remove(key)
```

- **Static:** No
- #### Parameters:
  - **key:** `string`
- **Returns:** `boolean`

___

### `clear`

```lua
--- @return any
function LocalObject:clear()
```

- **Static:** No
- **Returns:** `any`

___

### `clone`

```lua
--- @return nil|number|string|boolean|LocalArray|LocalObject
function LocalObject:clone()
```

- **Static:** No
- **Returns:** `nil|number|string|boolean|LocalArray|LocalObject`

## Static Methods

### `new`

```lua
--- @return LocalObject
function LocalObject.new()
```

- **Static:** Yes
- **Returns:** `LocalObject`

___

### `newFrom`

```lua
--- @param obj LocalObject
--- @return LocalObject
function LocalObject.newFrom(obj)
```

- **Static:** Yes
- #### Parameters:
  - **obj:** `LocalObject`
- **Returns:** `LocalObject`

___
```lua
--- @param table table
--- @return LocalObject
function LocalObject.newFrom(table)
```

- **Static:** Yes
- #### Parameters:
  - **table:** `table`
- **Returns:** `LocalObject`
