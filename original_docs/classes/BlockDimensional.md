# Class `BlockDimensional`

Inherits from `Block`

## Properties

### `isUpSideActivated`

```lua
---@type boolean
BlockDimensional.isUpSideActivated
```

- **Type:** `boolean`
- **Read\-only:** No
- **Static:** No

___

### `isDownSideActivated`

```lua
---@type boolean
BlockDimensional.isDownSideActivated
```

- **Type:** `boolean`
- **Read\-only:** No
- **Static:** No

___

### `isLeftSideActivated`

```lua
---@type boolean
BlockDimensional.isLeftSideActivated
```

- **Type:** `boolean`
- **Read\-only:** No
- **Static:** No

___

### `isRightSideActivated`

```lua
---@type boolean
BlockDimensional.isRightSideActivated
```

- **Type:** `boolean`
- **Read\-only:** No
- **Static:** No

___

### `isFrontSideActivated`

```lua
---@type boolean
BlockDimensional.isFrontSideActivated
```

- **Type:** `boolean`
- **Read\-only:** No
- **Static:** No

___

### `isBackSideActivated`

```lua
---@type boolean
BlockDimensional.isBackSideActivated
```

- **Type:** `boolean`
- **Read\-only:** No
- **Static:** No

___

### `type`

```lua
---@type EntityType
BlockDimensional.type
```

- **Type:** `EntityType`
- **Read\-only:** Yes
- **Static:** No

___

### `id`

```lua
---@type integer
BlockDimensional.id
```

The unique identifier of the block.

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** No

___

### `name`

```lua
---@type string
BlockDimensional.name
```

The name of the block.

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** No

___

### `tag`

```lua
---@type string
BlockDimensional.tag
```

The tag of the block.

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** No

___

### `position`

```lua
---@type Vector3
BlockDimensional.position
```

The position of the block.

- **Type:** `Vector3`
- **Read\-only:** Yes
- **Static:** No

___

### `rotation`

```lua
---@type Quaternion
BlockDimensional.rotation
```

The rotation of the block.

- **Type:** `Quaternion`
- **Read\-only:** Yes
- **Static:** No

___

### `slot`

```lua
---@type BlockSlot
BlockDimensional.slot
```

The Block Slot (world position) of the block.

- **Type:** `BlockSlot`
- **Read\-only:** Yes
- **Static:** No

___

### `upSide`

```lua
---@type Side
BlockDimensional.upSide
```

The up side of the block.

- **Type:** `Side`
- **Read\-only:** Yes
- **Static:** No

___

### `downSide`

```lua
---@type Side
BlockDimensional.downSide
```

The down side of the block.

- **Type:** `Side`
- **Read\-only:** Yes
- **Static:** No

___

### `leftSide`

```lua
---@type Side
BlockDimensional.leftSide
```

The left side of the block.

- **Type:** `Side`
- **Read\-only:** Yes
- **Static:** No

___

### `rightSide`

```lua
---@type Side
BlockDimensional.rightSide
```

The right side of the block.

- **Type:** `Side`
- **Read\-only:** Yes
- **Static:** No

___

### `frontSide`

```lua
---@type Side
BlockDimensional.frontSide
```

The front side of the block.

- **Type:** `Side`
- **Read\-only:** Yes
- **Static:** No

___

### `backSide`

```lua
---@type Side
BlockDimensional.backSide
```

The back side of the block.

- **Type:** `Side`
- **Read\-only:** Yes
- **Static:** No

___

### `sides`

```lua
---@type Side[]
BlockDimensional.sides
```

Gets all sides of the block.

- **Type:** `Side[]`
- **Read\-only:** Yes
- **Static:** No

___

### `neighbors`

```lua
---@type Block[]
BlockDimensional.neighbors
```

Gets all neighboring blocks.

- **Type:** `Block[]`
- **Read\-only:** Yes
- **Static:** No

___

### `adjacent`

```lua
---@type Block[]
BlockDimensional.adjacent
```

Gets all adjacent blocks.

- **Type:** `Block[]`
- **Read\-only:** Yes
- **Static:** No

___

### `upNeighbor`

```lua
---@type Block
BlockDimensional.upNeighbor
```

Gets the block above this block.

- **Type:** `Block`
- **Read\-only:** Yes
- **Static:** No

___

### `downNeighbor`

```lua
---@type Block
BlockDimensional.downNeighbor
```

Gets the block below this block.

- **Type:** `Block`
- **Read\-only:** Yes
- **Static:** No

___

### `rightNeighbor`

```lua
---@type Block
BlockDimensional.rightNeighbor
```

Gets the block to the right of this block.

- **Type:** `Block`
- **Read\-only:** Yes
- **Static:** No

___

### `leftNeighbor`

```lua
---@type Block
BlockDimensional.leftNeighbor
```

Gets the block to the left of this block.

- **Type:** `Block`
- **Read\-only:** Yes
- **Static:** No

___

### `frontNeighbor`

```lua
---@type Block
BlockDimensional.frontNeighbor
```

Gets the block in front of this block.

- **Type:** `Block`
- **Read\-only:** Yes
- **Static:** No

___

### `backNeighbor`

```lua
---@type Block
BlockDimensional.backNeighbor
```

Gets the block behind this block.

- **Type:** `Block`
- **Read\-only:** Yes
- **Static:** No

___

### `section`

```lua
---@type string
BlockDimensional.section
```

Gets the section of the block.

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** No

___

### `isVisited`

```lua
---@type boolean
BlockDimensional.isVisited
```

Indicates whether the block has been visited.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `isMoving`

```lua
---@type boolean
BlockDimensional.isMoving
```

Indicates whether the block is currently moving.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `movingSpeed`

```lua
---@type number
BlockDimensional.movingSpeed
```

Gets the speed at which the block is moving.

- **Type:** `number`
- **Read\-only:** Yes
- **Static:** No

___

### `movingDirection`

```lua
---@type Vector3
BlockDimensional.movingDirection
```

Gets the direction in which the block is moving.

- **Type:** `Vector3`
- **Read\-only:** Yes
- **Static:** No

___

### `isInMovingRest`

```lua
---@type boolean
BlockDimensional.isInMovingRest
```

Indicates whether the block is in a moving rest state.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `intangible`

```lua
---@type boolean
BlockDimensional.intangible
```

Indicates whether the block is intangible.

- **Type:** `boolean`
- **Read\-only:** No
- **Static:** No

___

### `properties`

```lua
---@type ElementPropertyPool
BlockDimensional.properties
```

Gets the properties of the block.

- **Type:** `ElementPropertyPool`
- **Read\-only:** Yes
- **Static:** No

___

### `localData`

```lua
---@type RawLocalData
BlockDimensional.localData
```

The local data associated with this element.

- **Type:** `RawLocalData`
- **Read\-only:** Yes
- **Static:** No

## Methods

### `isSideActivated`

```lua
--- @param face Face
--- @return boolean
function BlockDimensional:isSideActivated(face)
```

- **Static:** No
- #### Parameters:
  - **face:** `Face`
- **Returns:** `boolean`

___

### `setSideActivated`

```lua
--- @param face Face
--- @param activated boolean
--- @return any
function BlockDimensional:setSideActivated(face, activated)
```

- **Static:** No
- #### Parameters:
  - **face:** `Face`
  - **activated:** `boolean`
- **Returns:** `any`

___

### `getSide`

```lua
--- @param face Face
--- @return Side
function BlockDimensional:getSide(face)
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
function BlockDimensional:markAsVisited()
```

Marks the block as visited.

- **Static:** No
- **Returns:** `any`

___

### `enable`

```lua
--- @return any
function BlockDimensional:enable()
```

Enables the block.

- **Static:** No
- **Returns:** `any`

___

### `disable`

```lua
--- @return any
function BlockDimensional:disable()
```

Disables the block.

- **Static:** No
- **Returns:** `any`

___

### `asLevel`

```lua
--- @return Level
function BlockDimensional:asLevel()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Level`

___

### `asBlock`

```lua
--- @return Block
function BlockDimensional:asBlock()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Block`

___

### `asSide`

```lua
--- @return Side
function BlockDimensional:asSide()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Side`

___

### `asItem`

```lua
--- @return Item
function BlockDimensional:asItem()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Item`

___

### `asEnemy`

```lua
--- @return Enemy
function BlockDimensional:asEnemy()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Enemy`

___

### `asBall`

```lua
--- @return Ball
function BlockDimensional:asBall()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Ball`

___

### `asDecoration`

```lua
--- @return Decoration
function BlockDimensional:asDecoration()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Decoration`
