# Class `Block`

Represents a block in the game. Blocks are the fundamental building units of the game world. They can have various properties, sides, and neighbors.

## Properties

### `type`

```lua
---@type EntityType
Block.type
```

- **Type:** `EntityType`
- **Read\-only:** Yes
- **Static:** No

___

### `id`

```lua
---@type integer
Block.id
```

The unique identifier of the block.

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** No

___

### `name`

```lua
---@type string
Block.name
```

The name of the block.

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** No

___

### `tag`

```lua
---@type string
Block.tag
```

The tag of the block.

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** No

___

### `position`

```lua
---@type Vector3
Block.position
```

The position of the block.

- **Type:** `Vector3`
- **Read\-only:** Yes
- **Static:** No

___

### `rotation`

```lua
---@type Quaternion
Block.rotation
```

The rotation of the block.

- **Type:** `Quaternion`
- **Read\-only:** Yes
- **Static:** No

___

### `slot`

```lua
---@type BlockSlot
Block.slot
```

The Block Slot (world position) of the block.

- **Type:** `BlockSlot`
- **Read\-only:** Yes
- **Static:** No

___

### `upSide`

```lua
---@type Side
Block.upSide
```

The up side of the block.

- **Type:** `Side`
- **Read\-only:** Yes
- **Static:** No

___

### `downSide`

```lua
---@type Side
Block.downSide
```

The down side of the block.

- **Type:** `Side`
- **Read\-only:** Yes
- **Static:** No

___

### `leftSide`

```lua
---@type Side
Block.leftSide
```

The left side of the block.

- **Type:** `Side`
- **Read\-only:** Yes
- **Static:** No

___

### `rightSide`

```lua
---@type Side
Block.rightSide
```

The right side of the block.

- **Type:** `Side`
- **Read\-only:** Yes
- **Static:** No

___

### `frontSide`

```lua
---@type Side
Block.frontSide
```

The front side of the block.

- **Type:** `Side`
- **Read\-only:** Yes
- **Static:** No

___

### `backSide`

```lua
---@type Side
Block.backSide
```

The back side of the block.

- **Type:** `Side`
- **Read\-only:** Yes
- **Static:** No

___

### `sides`

```lua
---@type Side[]
Block.sides
```

Gets all sides of the block.

- **Type:** `Side[]`
- **Read\-only:** Yes
- **Static:** No

___

### `neighbors`

```lua
---@type Block[]
Block.neighbors
```

Gets all neighboring blocks.

- **Type:** `Block[]`
- **Read\-only:** Yes
- **Static:** No

___

### `adjacent`

```lua
---@type Block[]
Block.adjacent
```

Gets all adjacent blocks.

- **Type:** `Block[]`
- **Read\-only:** Yes
- **Static:** No

___

### `upNeighbor`

```lua
---@type Block
Block.upNeighbor
```

Gets the block above this block.

- **Type:** `Block`
- **Read\-only:** Yes
- **Static:** No

___

### `downNeighbor`

```lua
---@type Block
Block.downNeighbor
```

Gets the block below this block.

- **Type:** `Block`
- **Read\-only:** Yes
- **Static:** No

___

### `rightNeighbor`

```lua
---@type Block
Block.rightNeighbor
```

Gets the block to the right of this block.

- **Type:** `Block`
- **Read\-only:** Yes
- **Static:** No

___

### `leftNeighbor`

```lua
---@type Block
Block.leftNeighbor
```

Gets the block to the left of this block.

- **Type:** `Block`
- **Read\-only:** Yes
- **Static:** No

___

### `frontNeighbor`

```lua
---@type Block
Block.frontNeighbor
```

Gets the block in front of this block.

- **Type:** `Block`
- **Read\-only:** Yes
- **Static:** No

___

### `backNeighbor`

```lua
---@type Block
Block.backNeighbor
```

Gets the block behind this block.

- **Type:** `Block`
- **Read\-only:** Yes
- **Static:** No

___

### `section`

```lua
---@type string
Block.section
```

Gets the section of the block.

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** No

___

### `isVisited`

```lua
---@type boolean
Block.isVisited
```

Indicates whether the block has been visited.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `isMoving`

```lua
---@type boolean
Block.isMoving
```

Indicates whether the block is currently moving.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `movingSpeed`

```lua
---@type number
Block.movingSpeed
```

Gets the speed at which the block is moving.

- **Type:** `number`
- **Read\-only:** Yes
- **Static:** No

___

### `movingDirection`

```lua
---@type Vector3
Block.movingDirection
```

Gets the direction in which the block is moving.

- **Type:** `Vector3`
- **Read\-only:** Yes
- **Static:** No

___

### `isInMovingRest`

```lua
---@type boolean
Block.isInMovingRest
```

Indicates whether the block is in a moving rest state.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `intangible`

```lua
---@type boolean
Block.intangible
```

Indicates whether the block is intangible.

- **Type:** `boolean`
- **Read\-only:** No
- **Static:** No

___

### `properties`

```lua
---@type ElementPropertyPool
Block.properties
```

Gets the properties of the block.

- **Type:** `ElementPropertyPool`
- **Read\-only:** Yes
- **Static:** No

___

### `localData`

```lua
---@type RawLocalData
Block.localData
```

The local data associated with this element.

- **Type:** `RawLocalData`
- **Read\-only:** Yes
- **Static:** No

## Methods

### `getSide`

```lua
--- @param face Face
--- @return Side
function Block:getSide(face)
```

Gets the side of the block corresponding to the given face.

- **Static:** No
- #### Parameters:
  - **face:** `Face`
- **Returns:** `Side`

___

### `markAsVisited`

```lua
--- @return any
function Block:markAsVisited()
```

Marks the block as visited.

- **Static:** No
- **Returns:** `any`

___

### `enable`

```lua
--- @return any
function Block:enable()
```

Enables the block.

- **Static:** No
- **Returns:** `any`

___

### `disable`

```lua
--- @return any
function Block:disable()
```

Disables the block.

- **Static:** No
- **Returns:** `any`

___

### `asLevel`

```lua
--- @return Level
function Block:asLevel()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Level`

___

### `asBlock`

```lua
--- @return Block
function Block:asBlock()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Block`

___

### `asSide`

```lua
--- @return Side
function Block:asSide()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Side`

___

### `asItem`

```lua
--- @return Item
function Block:asItem()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Item`

___

### `asEnemy`

```lua
--- @return Enemy
function Block:asEnemy()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Enemy`

___

### `asBall`

```lua
--- @return Ball
function Block:asBall()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Ball`

___

### `asDecoration`

```lua
--- @return Decoration
function Block:asDecoration()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Decoration`
