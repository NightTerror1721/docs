# Namespace `string`

## Functions

### `byte`

```lua
--- @param s string
--- @param i? number
--- @param j? number
--- @return string
function byte(s, i?, j?)
```

- **Static:** Yes
- #### Parameters:
  - **s:** `string`
  - **i?:** `number`
  - **j?:** `number`
- **Returns:** `string`

___

### `char`

```lua
--- @param charCodes number
--- @return string
function char(charCodes)
```

- **Static:** Yes
- #### Parameters:
  - **charCodes:** `number`
- **Returns:** `string`

___

### `find`

```lua
--- @param s string
--- @param pattern string
--- @param init? number
--- @param plain? boolean
--- @return number[]
function find(s, pattern, init?, plain?)
```

- **Static:** Yes
- #### Parameters:
  - **s:** `string`
  - **pattern:** `string`
  - **init?:** `number`
  - **plain?:** `boolean`
- **Returns:** `number[]`

___

### `format`

```lua
--- @param stringToFormat string
--- @param args any
--- @return string
function format(stringToFormat, args)
```

- **Static:** Yes
- #### Parameters:
  - **stringToFormat:** `string`
  - **args:** `any`
- **Returns:** `string`

___

### `gmatch`

```lua
--- @param s string
--- @param pattern string
--- @return Iterator<string>
function gmatch(s, pattern)
```

- **Static:** Yes
- #### Parameters:
  - **s:** `string`
  - **pattern:** `string`
- **Returns:** `Iterator<string>`

___

### `gsub`

```lua
--- @param s string
--- @param pattern string
--- @param repl string
--- @param n? number
--- @return string
function gsub(s, pattern, repl, n?)
```

- **Static:** Yes
- #### Parameters:
  - **s:** `string`
  - **pattern:** `string`
  - **repl:** `string`
  - **n?:** `number`
- **Returns:** `string`

___

### `len`

```lua
--- @param s string
--- @return number
function len(s)
```

- **Static:** Yes
- #### Parameters:
  - **s:** `string`
- **Returns:** `number`

___

### `lower`

```lua
--- @param s string
--- @return string
function lower(s)
```

- **Static:** Yes
- #### Parameters:
  - **s:** `string`
- **Returns:** `string`

___

### `match`

```lua
--- @param s string
--- @param pattern string
--- @param init? number
--- @return string?
function match(s, pattern, init?)
```

- **Static:** Yes
- #### Parameters:
  - **s:** `string`
  - **pattern:** `string`
  - **init?:** `number`
- **Returns:** `string?`

___

### `rep`

```lua
--- @param s string
--- @param n number
--- @param sep? string
--- @return string
function rep(s, n, sep?)
```

- **Static:** Yes
- #### Parameters:
  - **s:** `string`
  - **n:** `number`
  - **sep?:** `string`
- **Returns:** `string`

___

### `reverse`

```lua
--- @param s string
--- @return string
function reverse(s)
```

- **Static:** Yes
- #### Parameters:
  - **s:** `string`
- **Returns:** `string`

___

### `sub`

```lua
--- @param s string
--- @param i number
--- @param j? number
--- @return string
function sub(s, i, j?)
```

- **Static:** Yes
- #### Parameters:
  - **s:** `string`
  - **i:** `number`
  - **j?:** `number`
- **Returns:** `string`

___

### `upper`

```lua
--- @param s string
--- @return string
function upper(s)
```

- **Static:** Yes
- #### Parameters:
  - **s:** `string`
- **Returns:** `string`
