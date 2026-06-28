# Class `BlockWarp`

Inherits from `Block`

## Properties

### `isActivated`

```lua
---@type boolean
BlockWarp.isActivated
```

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `nextLevel`

```lua
---@type string
BlockWarp.nextLevel
```

- **Type:** `string`
- **Read\-only:** No
- **Static:** No

___

### `requiredAllKeys`

```lua
---@type boolean
BlockWarp.requiredAllKeys
```

- **Type:** `boolean`
- **Read\-only:** No
- **Static:** No

___

### `type`

```lua
---@type EntityType
BlockWarp.type
```

- **Type:** `EntityType`
- **Read\-only:** Yes
- **Static:** No

___

### `id`

```lua
---@type integer
BlockWarp.id
```

The unique identifier of the block.

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** No

___

### `name`

```lua
---@type string
BlockWarp.name
```

The name of the block.

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** No

___

### `tag`

```lua
---@type string
BlockWarp.tag
```

The tag of the block.

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** No

___

### `position`

```lua
---@type Vector3
BlockWarp.position
```

The position of the block.

- **Type:** `Vector3`
- **Read\-only:** Yes
- **Static:** No

___

### `rotation`

```lua
---@type Quaternion
BlockWarp.rotation
```

The rotation of the block.

- **Type:** `Quaternion`
- **Read\-only:** Yes
- **Static:** No

___

### `slot`

```lua
---@type BlockSlot
BlockWarp.slot
```

The Block Slot (world position) of the block.

- **Type:** `BlockSlot`
- **Read\-only:** Yes
- **Static:** No

___

### `upSide`

```lua
---@type Side
BlockWarp.upSide
```

The up side of the block.

- **Type:** `Side`
- **Read\-only:** Yes
- **Static:** No

___

### `downSide`

```lua
---@type Side
BlockWarp.downSide
```

The down side of the block.

- **Type:** `Side`
- **Read\-only:** Yes
- **Static:** No

___

### `leftSide`

```lua
---@type Side
BlockWarp.leftSide
```

The left side of the block.

- **Type:** `Side`
- **Read\-only:** Yes
- **Static:** No

___

### `rightSide`

```lua
---@type Side
BlockWarp.rightSide
```

The right side of the block.

- **Type:** `Side`
- **Read\-only:** Yes
- **Static:** No

___

### `frontSide`

```lua
---@type Side
BlockWarp.frontSide
```

The front side of the block.

- **Type:** `Side`
- **Read\-only:** Yes
- **Static:** No

___

### `backSide`

```lua
---@type Side
BlockWarp.backSide
```

The back side of the block.

- **Type:** `Side`
- **Read\-only:** Yes
- **Static:** No

___

### `sides`

```lua
---@type Side[]
BlockWarp.sides
```

Gets all sides of the block.

- **Type:** `Side[]`
- **Read\-only:** Yes
- **Static:** No

___

### `neighbors`

```lua
---@type Block[]
BlockWarp.neighbors
```

Gets all neighboring blocks.

- **Type:** `Block[]`
- **Read\-only:** Yes
- **Static:** No

___

### `adjacent`

```lua
---@type Block[]
BlockWarp.adjacent
```

Gets all adjacent blocks.

- **Type:** `Block[]`
- **Read\-only:** Yes
- **Static:** No

___

### `upNeighbor`

```lua
---@type Block
BlockWarp.upNeighbor
```

Gets the block above this block.

- **Type:** `Block`
- **Read\-only:** Yes
- **Static:** No

___

### `downNeighbor`

```lua
---@type Block
BlockWarp.downNeighbor
```

Gets the block below this block.

- **Type:** `Block`
- **Read\-only:** Yes
- **Static:** No

___

### `rightNeighbor`

```lua
---@type Block
BlockWarp.rightNeighbor
```

Gets the block to the right of this block.

- **Type:** `Block`
- **Read\-only:** Yes
- **Static:** No

___

### `leftNeighbor`

```lua
---@type Block
BlockWarp.leftNeighbor
```

Gets the block to the left of this block.

- **Type:** `Block`
- **Read\-only:** Yes
- **Static:** No

___

### `frontNeighbor`

```lua
---@type Block
BlockWarp.frontNeighbor
```

Gets the block in front of this block.

- **Type:** `Block`
- **Read\-only:** Yes
- **Static:** No

___

### `backNeighbor`

```lua
---@type Block
BlockWarp.backNeighbor
```

Gets the block behind this block.

- **Type:** `Block`
- **Read\-only:** Yes
- **Static:** No

___

### `section`

```lua
---@type string
BlockWarp.section
```

Gets the section of the block.

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** No

___

### `isVisited`

```lua
---@type boolean
BlockWarp.isVisited
```

Indicates whether the block has been visited.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `isMoving`

```lua
---@type boolean
BlockWarp.isMoving
```

Indicates whether the block is currently moving.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `movingSpeed`

```lua
---@type number
BlockWarp.movingSpeed
```

Gets the speed at which the block is moving.

- **Type:** `number`
- **Read\-only:** Yes
- **Static:** No

___

### `movingDirection`

```lua
---@type Vector3
BlockWarp.movingDirection
```

Gets the direction in which the block is moving.

- **Type:** `Vector3`
- **Read\-only:** Yes
- **Static:** No

___

### `isInMovingRest`

```lua
---@type boolean
BlockWarp.isInMovingRest
```

Indicates whether the block is in a moving rest state.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `intangible`

```lua
---@type boolean
BlockWarp.intangible
```

Indicates whether the block is intangible.

- **Type:** `boolean`
- **Read\-only:** No
- **Static:** No

___

### `properties`

```lua
---@type ElementPropertyPool
BlockWarp.properties
```

Gets the properties of the block.

- **Type:** `ElementPropertyPool`
- **Read\-only:** Yes
- **Static:** No

___

### `localData`

```lua
---@type RawLocalData
BlockWarp.localData
```

The local data associated with this element.

- **Type:** `RawLocalData`
- **Read\-only:** Yes
- **Static:** No

## Methods

### `activate`

```lua
--- @return any
function BlockWarp:activate()
```

- **Static:** No
- **Returns:** `any`

___

### `deactivate`

```lua
--- @return any
function BlockWarp:deactivate()
```

- **Static:** No
- **Returns:** `any`

___

### `getSide`

```lua
--- @param face Face
--- @return Side
function BlockWarp:getSide(face)
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
function BlockWarp:markAsVisited()
```

Marks the block as visited.

- **Static:** No
- **Returns:** `any`

___

### `enable`

```lua
--- @return any
function BlockWarp:enable()
```

Enables the block.

- **Static:** No
- **Returns:** `any`

___

### `disable`

```lua
--- @return any
function BlockWarp:disable()
```

Disables the block.

- **Static:** No
- **Returns:** `any`

___

### `asLevel`

```lua
--- @return Level
function BlockWarp:asLevel()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Level`

___

### `asBlock`

```lua
--- @return Block
function BlockWarp:asBlock()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Block`

___

### `asSide`

```lua
--- @return Side
function BlockWarp:asSide()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Side`

___

### `asItem`

```lua
--- @return Item
function BlockWarp:asItem()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Item`

___

### `asEnemy`

```lua
--- @return Enemy
function BlockWarp:asEnemy()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Enemy`

___

### `asBall`

```lua
--- @return Ball
function BlockWarp:asBall()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Ball`

___

### `asDecoration`

```lua
--- @return Decoration
function BlockWarp:asDecoration()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Decoration`
