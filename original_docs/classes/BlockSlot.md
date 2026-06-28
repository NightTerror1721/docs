# Class `BlockSlot`

Represents a slot within a block. A block slot defines a specific position within a block where elements can be placed.

## Properties

### `x`

```lua
---@type integer
BlockSlot.x
```

Gets the X coordinate of the block slot.

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** No

___

### `y`

```lua
---@type integer
BlockSlot.y
```

Gets the Y coordinate of the block slot.

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** No

___

### `z`

```lua
---@type integer
BlockSlot.z
```

Gets the Z coordinate of the block slot.

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** No

___

### `position`

```lua
---@type Vector3
BlockSlot.position
```

Gets the position of the block slot as a vector.

- **Type:** `Vector3`
- **Read\-only:** Yes
- **Static:** No

## Methods

### `translate`

```lua
--- @param dx integer
--- @param dy integer
--- @param dz integer
--- @return BlockSlot
function BlockSlot:translate(dx, dy, dz)
```

Translates the block slot by the specified offsets.

- **Static:** No
- #### Parameters:
  - **dx:** `integer`
  - **dy:** `integer`
  - **dz:** `integer`
- **Returns:** `BlockSlot`

___

### `translateFromBasis`

```lua
--- @param basis Basis
--- @param dx integer
--- @param dy integer
--- @param dz integer
--- @return BlockSlot
function BlockSlot:translateFromBasis(basis, dx, dy, dz)
```

Translates the block slot from a given basis by the specified offsets.

- **Static:** No
- #### Parameters:
  - **basis:** `Basis`
  - **dx:** `integer`
  - **dy:** `integer`
  - **dz:** `integer`
- **Returns:** `BlockSlot`

## Static Properties

### `default`

```lua
--- static
---@type BlockSlot
BlockSlot.default
```

Gets the default block slot, which is typically the origin (0, 0, 0) of a block.

- **Type:** `BlockSlot`
- **Read\-only:** Yes
- **Static:** Yes

## Static Methods

### `new`

```lua
--- @param x integer
--- @param y integer
--- @param z integer
--- @return BlockSlot
function BlockSlot.new(x, y, z)
```

Creates a new block slot with the specified coordinates.

- **Static:** Yes
- #### Parameters:
  - **x:** `integer`
  - **y:** `integer`
  - **z:** `integer`
- **Returns:** `BlockSlot`
