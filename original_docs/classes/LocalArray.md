# Class `LocalArray`

## Properties

### `[][integer]: nil|number|string|boolean|LocalArray|LocalObject`

```lua
---@param index integer
---@return nil|number|string|boolean|LocalArray|LocalObject
function LocalArray.__index(index)

---@param index integer
---@param value nil|number|string|boolean|LocalArray|LocalObject
function LocalArray.__newindex(index, value)
```

- **Type:** `nil|number|string|boolean|LocalArray|LocalObject`
- **Read\-only:** No

___

### `length`

```lua
---@type integer
LocalArray.length
```

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** No

## Methods

### `add`

```lua
--- @param value nil|number|string|boolean|LocalArray|LocalObject
--- @return any
function LocalArray:add(value)
```

- **Static:** No
- #### Parameters:
  - **value:** `nil|number|string|boolean|LocalArray|LocalObject`
- **Returns:** `any`

___

### `insert`

```lua
--- @param index integer
--- @param value nil|number|string|boolean|LocalArray|LocalObject
--- @return any
function LocalArray:insert(index, value)
```

- **Static:** No
- #### Parameters:
  - **index:** `integer`
  - **value:** `nil|number|string|boolean|LocalArray|LocalObject`
- **Returns:** `any`

___

### `removeAt`

```lua
--- @param index integer
--- @return any
function LocalArray:removeAt(index)
```

- **Static:** No
- #### Parameters:
  - **index:** `integer`
- **Returns:** `any`

___

### `clear`

```lua
--- @return any
function LocalArray:clear()
```

- **Static:** No
- **Returns:** `any`

___

### `clone`

```lua
--- @return nil|number|string|boolean|LocalArray|LocalObject
function LocalArray:clone()
```

- **Static:** No
- **Returns:** `nil|number|string|boolean|LocalArray|LocalObject`

## Static Methods

### `new`

```lua
--- @return LocalArray
function LocalArray.new()
```

- **Static:** Yes
- **Returns:** `LocalArray`

___
```lua
--- @param length integer
--- @return LocalArray
function LocalArray.new(length)
```

- **Static:** Yes
- #### Parameters:
  - **length:** `integer`
- **Returns:** `LocalArray`

___

### `newFrom`

```lua
--- @param arrayValues ... (nil|number|string|boolean|LocalArray|LocalObject)
--- @return LocalArray
function LocalArray.newFrom(arrayValues)
```

- **Static:** Yes
- #### Parameters:
  - **arrayValues:** `... (nil|number|string|boolean|LocalArray|LocalObject)`
- **Returns:** `LocalArray`

___
```lua
--- @param table table
--- @return LocalArray
function LocalArray.newFrom(table)
```

- **Static:** Yes
- #### Parameters:
  - **table:** `table`
- **Returns:** `LocalArray`
