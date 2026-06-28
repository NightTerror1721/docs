# Class `Color`

Represents a color in the game. Provides methods to create and manipulate colors.

## Properties

### `grayscale`

```lua
---@type number
Color.grayscale
```

The Grayscale value of the color.

- **Type:** `number`
- **Read\-only:** Yes
- **Static:** No

___

### `r`

```lua
---@type number
Color.r
```

The red component of the color.

- **Type:** `number`
- **Read\-only:** Yes
- **Static:** No

___

### `g`

```lua
---@type number
Color.g
```

The green component of the color.

- **Type:** `number`
- **Read\-only:** Yes
- **Static:** No

___

### `b`

```lua
---@type number
Color.b
```

The blue component of the color.

- **Type:** `number`
- **Read\-only:** Yes
- **Static:** No

___

### `a`

```lua
---@type number
Color.a
```

The alpha component of the color.

- **Type:** `number`
- **Read\-only:** Yes
- **Static:** No

___

### `linear`

```lua
---@type Color
Color.linear
```

The linear color space representation of the color.

- **Type:** `Color`
- **Read\-only:** Yes
- **Static:** No

___

### `gamma`

```lua
---@type Color
Color.gamma
```

The gamma color space representation of the color.

- **Type:** `Color`
- **Read\-only:** Yes
- **Static:** No

___

### `maxColorComponent`

```lua
---@type number
Color.maxColorComponent
```

The maximum color component value of the color.

- **Type:** `number`
- **Read\-only:** Yes
- **Static:** No

___

### `[][integer]: number`

```lua
---@param index integer
---@return number
function Color.__index(index)

---@param index integer
---@param value number
function Color.__newindex(index, value)
```

Gets or sets the color component at the specified index (1 \= R, 2 \= G, 3 \= B, 4 \= A).

- **Type:** `number`
- **Read\-only:** No

## Static Properties

### `red`

```lua
--- static
---@type Color
Color.red
```

- **Type:** `Color`
- **Read\-only:** Yes
- **Static:** Yes

___

### `green`

```lua
--- static
---@type Color
Color.green
```

- **Type:** `Color`
- **Read\-only:** Yes
- **Static:** Yes

___

### `blue`

```lua
--- static
---@type Color
Color.blue
```

- **Type:** `Color`
- **Read\-only:** Yes
- **Static:** Yes

___

### `white`

```lua
--- static
---@type Color
Color.white
```

- **Type:** `Color`
- **Read\-only:** Yes
- **Static:** Yes

___

### `black`

```lua
--- static
---@type Color
Color.black
```

- **Type:** `Color`
- **Read\-only:** Yes
- **Static:** Yes

___

### `yellow`

```lua
--- static
---@type Color
Color.yellow
```

- **Type:** `Color`
- **Read\-only:** Yes
- **Static:** Yes

___

### `cyan`

```lua
--- static
---@type Color
Color.cyan
```

- **Type:** `Color`
- **Read\-only:** Yes
- **Static:** Yes

___

### `magenta`

```lua
--- static
---@type Color
Color.magenta
```

- **Type:** `Color`
- **Read\-only:** Yes
- **Static:** Yes

___

### `gray`

```lua
--- static
---@type Color
Color.gray
```

- **Type:** `Color`
- **Read\-only:** Yes
- **Static:** Yes

___

### `grey`

```lua
--- static
---@type Color
Color.grey
```

- **Type:** `Color`
- **Read\-only:** Yes
- **Static:** Yes

___

### `clear`

```lua
--- static
---@type Color
Color.clear
```

- **Type:** `Color`
- **Read\-only:** Yes
- **Static:** Yes

## Static Methods

### `new`

```lua
--- @return Color
function Color.new()
```

Creates a new color with the specified red, green, blue, and alpha values.

- **Static:** Yes
- **Returns:** `Color`

___
```lua
--- @param r number
--- @param g number
--- @param b number
--- @return Color
function Color.new(r, g, b)
```

Creates a new color with the specified red, green, and blue values.

- **Static:** Yes
- #### Parameters:
  - **r:** `number`
  - **g:** `number`
  - **b:** `number`
- **Returns:** `Color`

___
```lua
--- @param r number
--- @param g number
--- @param b number
--- @param a number
--- @return Color
function Color.new(r, g, b, a)
```

Creates a new color with the specified red, green, blue, and alpha values.

- **Static:** Yes
- #### Parameters:
  - **r:** `number`
  - **g:** `number`
  - **b:** `number`
  - **a:** `number`
- **Returns:** `Color`

___
```lua
--- @param grayscale number
--- @return Color
function Color.new(grayscale)
```

Creates a new color with the specified grayscale value.

- **Static:** Yes
- #### Parameters:
  - **grayscale:** `number`
- **Returns:** `Color`

___
```lua
--- @param grayscale number
--- @param alpha number
--- @return Color
function Color.new(grayscale, alpha)
```

Creates a new color with the specified grayscale and alpha values.

- **Static:** Yes
- #### Parameters:
  - **grayscale:** `number`
  - **alpha:** `number`
- **Returns:** `Color`

___

### `lerp`

```lua
--- @param a Color
--- @param b Color
--- @param t number
--- @return Color
function Color.lerp(a, b, t)
```

- **Static:** Yes
- #### Parameters:
  - **a:** `Color`
  - **b:** `Color`
  - **t:** `number`
- **Returns:** `Color`

___

### `lerpUnclamped`

```lua
--- @param a Color
--- @param b Color
--- @param t number
--- @return Color
function Color.lerpUnclamped(a, b, t)
```

- **Static:** Yes
- #### Parameters:
  - **a:** `Color`
  - **b:** `Color`
  - **t:** `number`
- **Returns:** `Color`
