# Namespace `table`

## Functions

### `concat`

```lua
--- @param array (number|string)[]
--- @param sep? number|string
--- @param i? number
--- @param j? number
--- @return string
function concat(array, sep?, i?, j?)
```

- **Static:** Yes
- #### Parameters:
  - **array:** `(number|string)[]`
  - **sep?:** `number|string`
  - **i?:** `number`
  - **j?:** `number`
- **Returns:** `string`

___

### `insert`

```lua
--- @param array any[]
--- @param pos number
--- @param value any
--- @return void
function insert(array, pos, value)
```

- **Static:** Yes
- #### Parameters:
  - **array:** `any[]`
  - **pos:** `number`
  - **value:** `any`

___

### `upper`

```lua
--- @param array any[]
--- @param pos? number
--- @param value any?
--- @return void
function upper(array, pos?, value)
```

- **Static:** Yes
- #### Parameters:
  - **array:** `any[]`
  - **pos?:** `number`
  - **value:** `any?`

___

### `pack`

```lua
--- @param args any
--- @return table<any, any>
function pack(args)
```

- **Static:** Yes
- #### Parameters:
  - **args:** `any`
- **Returns:** `table<any, any>`

___

### `remove`

```lua
--- @param array any[]
--- @param pos? number
--- @return any
function remove(array, pos?)
```

- **Static:** Yes
- #### Parameters:
  - **array:** `any[]`
  - **pos?:** `number`
- **Returns:** `any`

___

### `sort`

```lua
--- @param array any[]
--- @param comp? (any, any) => number
--- @return void
function sort(array, comp?)
```

- **Static:** Yes
- #### Parameters:
  - **array:** `any[]`
  - **comp?:** `(any, any) => number`

___

### `unpack`

```lua
--- @param table table<any, any>
--- @param i? number
--- @param j? number
--- @return [any?...]
function unpack(table, i?, j?)
```

- **Static:** Yes
- #### Parameters:
  - **table:** `table<any, any>`
  - **i?:** `number`
  - **j?:** `number`
- **Returns:** `[any?...]`
