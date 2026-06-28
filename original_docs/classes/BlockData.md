# Class `BlockData`

## Properties

### `x`

```lua
---@type integer
BlockData.x
```

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** No

___

### `y`

```lua
---@type integer
BlockData.y
```

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** No

___

### `z`

```lua
---@type integer
BlockData.z
```

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** No

___

### `up`

```lua
---@type SideData
BlockData.up
```

- **Type:** `SideData`
- **Read\-only:** Yes
- **Static:** No

___

### `down`

```lua
---@type SideData
BlockData.down
```

- **Type:** `SideData`
- **Read\-only:** Yes
- **Static:** No

___

### `left`

```lua
---@type SideData
BlockData.left
```

- **Type:** `SideData`
- **Read\-only:** Yes
- **Static:** No

___

### `right`

```lua
---@type SideData
BlockData.right
```

- **Type:** `SideData`
- **Read\-only:** Yes
- **Static:** No

___

### `front`

```lua
---@type SideData
BlockData.front
```

- **Type:** `SideData`
- **Read\-only:** Yes
- **Static:** No

___

### `back`

```lua
---@type SideData
BlockData.back
```

- **Type:** `SideData`
- **Read\-only:** Yes
- **Static:** No

___

### `template`

```lua
---@type string
BlockData.template
```

- **Type:** `string`
- **Read\-only:** No
- **Static:** No

___

### `scriptRef`

```lua
---@type string
BlockData.scriptRef
```

- **Type:** `string`
- **Read\-only:** No
- **Static:** No

___

### `scriptTag`

```lua
---@type string
BlockData.scriptTag
```

- **Type:** `string`
- **Read\-only:** No
- **Static:** No

___

### `scriptVars`

```lua
---@type ScriptVariables
BlockData.scriptVars
```

- **Type:** `ScriptVariables`
- **Read\-only:** Yes
- **Static:** No

___

### `properties`

```lua
---@type ElementPropertiesData
BlockData.properties
```

- **Type:** `ElementPropertiesData`
- **Read\-only:** Yes
- **Static:** No

## Methods

### `getSides`

```lua
--- @return table
function BlockData:getSides()
```

Returns a table containing the sides in the order: Up, Down, Left, Right, Front, Back.

- **Static:** No
- **Returns:** `table`

___

### `getSidesIterator`

```lua
--- @return SideData[]
function BlockData:getSidesIterator()
```

Returns an iterator over the sides in the order: Up, Down, Left, Right, Front, Back.

- **Static:** No
- **Returns:** `SideData[]`

___

### `clear`

```lua
--- @return any
function BlockData:clear()
```

- **Static:** No
- **Returns:** `any`
