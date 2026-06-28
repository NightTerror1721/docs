# Class `ElementPropertyPool`

Represents a pool of element properties, allowing access to individual properties and their values.

## Properties

### `count`

```lua
---@type integer
ElementPropertyPool.count
```

The number of properties.

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** No

___

### `names`

```lua
---@type string[]
ElementPropertyPool.names
```

The names of all properties.

- **Type:** `string[]`
- **Read\-only:** Yes
- **Static:** No

___

### `namesArray`

```lua
---@type any[]
ElementPropertyPool.namesArray
```

The names of all properties as an array.

- **Type:** `any[]`
- **Read\-only:** Yes
- **Static:** No

___

### `[][string]: any`

```lua
---@param index string
---@return any
function ElementPropertyPool.__index(index)
```

Gets the property with the given name.

- **Type:** `any`
- **Read\-only:** Yes

## Methods

### `hasProperty`

```lua
--- @param name string
--- @return boolean
function ElementPropertyPool:hasProperty(name)
```

Checks if a property with the given name exists.

- **Static:** No
- #### Parameters:
  - **name:** `string`
- **Returns:** `boolean`

___

### `getProperty`

```lua
--- @param name string
--- @return ElementProperty
function ElementPropertyPool:getProperty(name)
```

Gets the property with the given name.

- **Static:** No
- #### Parameters:
  - **name:** `string`
- **Returns:** `ElementProperty`

___

### `getPropertyValue`

```lua
--- @param name string
--- @return any
function ElementPropertyPool:getPropertyValue(name)
```

Gets the value of the property with the given name.

- **Static:** No
- #### Parameters:
  - **name:** `string`
- **Returns:** `any`

___

### `getEnumerator`

```lua
--- @return IEnumerator<ElementProperty>
function ElementPropertyPool:getEnumerator()
```

Returns an enumerator that iterates through the collection of element properties.

- **Static:** No
- **Returns:** `IEnumerator<ElementProperty>`

## Static Properties

### `luaClassName`

```lua
--- static
---@type string
ElementPropertyPool.luaClassName
```

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** Yes
