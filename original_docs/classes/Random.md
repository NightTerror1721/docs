# Class `Random`

Represents a random number generator.

## Methods

### `nextInteger`

```lua
--- @return integer
function Random:nextInteger()
```

Returns a random integer between 1 and the maximum value.

- **Static:** No
- **Returns:** `integer`

___
```lua
--- @param minInclusive integer
--- @param maxInclusive integer
--- @return integer
function Random:nextInteger(minInclusive, maxInclusive)
```

Returns a random integer between the specified minimum and maximum values.

- **Static:** No
- #### Parameters:
  - **minInclusive:** `integer`
  - **maxInclusive:** `integer`
- **Returns:** `integer`

___
```lua
--- @param maxInclusive integer
--- @return integer
function Random:nextInteger(maxInclusive)
```

Returns a random integer between 1 and the specified maximum value.

- **Static:** No
- #### Parameters:
  - **maxInclusive:** `integer`
- **Returns:** `integer`

___

### `nextNumber`

```lua
--- @return number
function Random:nextNumber()
```

Returns a random double between 0 and 1.

- **Static:** No
- **Returns:** `number`

___
```lua
--- @param minInclusive number
--- @param maxExclusive number
--- @return number
function Random:nextNumber(minInclusive, maxExclusive)
```

Returns a random double between the specified minimum (inclusive) and maximum (exclusive) values.

- **Static:** No
- #### Parameters:
  - **minInclusive:** `number`
  - **maxExclusive:** `number`
- **Returns:** `number`

___
```lua
--- @param maxExclusive number
--- @return number
function Random:nextNumber(maxExclusive)
```

Returns a random double between 0 and the specified maximum (exclusive) value.

- **Static:** No
- #### Parameters:
  - **maxExclusive:** `number`
- **Returns:** `number`

___

### `nextGaussian`

```lua
--- @return number
function Random:nextGaussian()
```

Returns a random number following a Gaussian distribution.

- **Static:** No
- **Returns:** `number`

___

### `nextBoolean`

```lua
--- @return boolean
function Random:nextBoolean()
```

Returns a random boolean value.

- **Static:** No
- **Returns:** `boolean`

___

### `shuffle`

```lua
--- @param table table
--- @return any
function Random:shuffle(table)
```

Shuffles the elements of the specified table in place.

- **Static:** No
- #### Parameters:
  - **table:** `table`
- **Returns:** `any`

___

### `nextElement`

```lua
--- @param table table
--- @return any
function Random:nextElement(table)
```

Returns a random element from the specified table.

- **Static:** No
- #### Parameters:
  - **table:** `table`
- **Returns:** `any`

___

### `nextIndex`

```lua
--- @param table table
--- @return integer
function Random:nextIndex(table)
```

Returns a random index from the specified table.

- **Static:** No
- #### Parameters:
  - **table:** `table`
- **Returns:** `integer`

___

### `serializeToTable`

```lua
--- @return table
function Random:serializeToTable()
```

Serializes the random number generator state to a Lua table.

- **Static:** No
- **Returns:** `table`

___

### `serialize`

```lua
--- @return LocalObject
function Random:serialize()
```

Serializes the random number generator state to a Lua local object.

- **Static:** No
- **Returns:** `LocalObject`

## Static Methods

### `new`

```lua
--- @return Random
function Random.new()
```

Creates a new random number generator with a random seed.

- **Static:** Yes
- **Returns:** `Random`

___
```lua
--- @param seed integer
--- @return Random
function Random.new(seed)
```

Creates a new random number generator with the specified seed.

- **Static:** Yes
- #### Parameters:
  - **seed:** `integer`
- **Returns:** `Random`

___
```lua
--- @param seed string
--- @return Random
function Random.new(seed)
```

Creates a new random number generator with the specified string seed.

- **Static:** Yes
- #### Parameters:
  - **seed:** `string`
- **Returns:** `Random`

___

### `deserializeFromTable`

```lua
--- @param table table
--- @return Random
function Random.deserializeFromTable(table)
```

Deserializes a random number generator from a Lua table.

- **Static:** Yes
- #### Parameters:
  - **table:** `table`
- **Returns:** `Random`

___

### `deserialize`

```lua
--- @param obj LocalObject
--- @return Random
function Random.deserialize(obj)
```

Deserializes a random number generator from a Lua local object.

- **Static:** Yes
- #### Parameters:
  - **obj:** `LocalObject`
- **Returns:** `Random`

___

### `randomSeed`

```lua
--- @return integer
function Random.randomSeed()
```

Returns a random seed value.

- **Static:** Yes
- **Returns:** `integer`

___

### `randomStringSeed`

```lua
--- @return string
function Random.randomStringSeed()
```

Returns a random string seed value.

- **Static:** Yes
- **Returns:** `string`
