# Class `BlockBreaking`

Inherits from `Block`

## Properties

### `isBroken`

```lua
---@type boolean
BlockBreaking.isBroken
```

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `type`

```lua
---@type EntityType
BlockBreaking.type
```

- **Type:** `EntityType`
- **Read\-only:** Yes
- **Static:** No

___

### `id`

```lua
---@type integer
BlockBreaking.id
```

The unique identifier of the block.

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** No

___

### `name`

```lua
---@type string
BlockBreaking.name
```

The name of the block.

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** No

___

### `tag`

```lua
---@type string
BlockBreaking.tag
```

The tag of the block.

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** No

___

### `position`

```lua
---@type Vector3
BlockBreaking.position
```

The position of the block.

- **Type:** `Vector3`
- **Read\-only:** Yes
- **Static:** No

___

### `rotation`

```lua
---@type Quaternion
BlockBreaking.rotation
```

The rotation of the block.

- **Type:** `Quaternion`
- **Read\-only:** Yes
- **Static:** No

___

### `slot`

```lua
---@type BlockSlot
BlockBreaking.slot
```

The Block Slot (world position) of the block.

- **Type:** `BlockSlot`
- **Read\-only:** Yes
- **Static:** No

___

### `upSide`

```lua
---@type Side
BlockBreaking.upSide
```

The up side of the block.

- **Type:** `Side`
- **Read\-only:** Yes
- **Static:** No

___

### `downSide`

```lua
---@type Side
BlockBreaking.downSide
```

The down side of the block.

- **Type:** `Side`
- **Read\-only:** Yes
- **Static:** No

___

### `leftSide`

```lua
---@type Side
BlockBreaking.leftSide
```

The left side of the block.

- **Type:** `Side`
- **Read\-only:** Yes
- **Static:** No

___

### `rightSide`

```lua
---@type Side
BlockBreaking.rightSide
```

The right side of the block.

- **Type:** `Side`
- **Read\-only:** Yes
- **Static:** No

___

### `frontSide`

```lua
---@type Side
BlockBreaking.frontSide
```

The front side of the block.

- **Type:** `Side`
- **Read\-only:** Yes
- **Static:** No

___

### `backSide`

```lua
---@type Side
BlockBreaking.backSide
```

The back side of the block.

- **Type:** `Side`
- **Read\-only:** Yes
- **Static:** No

___

### `sides`

```lua
---@type Side[]
BlockBreaking.sides
```

Gets all sides of the block.

- **Type:** `Side[]`
- **Read\-only:** Yes
- **Static:** No

___

### `neighbors`

```lua
---@type Block[]
BlockBreaking.neighbors
```

Gets all neighboring blocks.

- **Type:** `Block[]`
- **Read\-only:** Yes
- **Static:** No

___

### `adjacent`

```lua
---@type Block[]
BlockBreaking.adjacent
```

Gets all adjacent blocks.

- **Type:** `Block[]`
- **Read\-only:** Yes
- **Static:** No

___

### `upNeighbor`

```lua
---@type Block
BlockBreaking.upNeighbor
```

Gets the block above this block.

- **Type:** `Block`
- **Read\-only:** Yes
- **Static:** No

___

### `downNeighbor`

```lua
---@type Block
BlockBreaking.downNeighbor
```

Gets the block below this block.

- **Type:** `Block`
- **Read\-only:** Yes
- **Static:** No

___

### `rightNeighbor`

```lua
---@type Block
BlockBreaking.rightNeighbor
```

Gets the block to the right of this block.

- **Type:** `Block`
- **Read\-only:** Yes
- **Static:** No

___

### `leftNeighbor`

```lua
---@type Block
BlockBreaking.leftNeighbor
```

Gets the block to the left of this block.

- **Type:** `Block`
- **Read\-only:** Yes
- **Static:** No

___

### `frontNeighbor`

```lua
---@type Block
BlockBreaking.frontNeighbor
```

Gets the block in front of this block.

- **Type:** `Block`
- **Read\-only:** Yes
- **Static:** No

___

### `backNeighbor`

```lua
---@type Block
BlockBreaking.backNeighbor
```

Gets the block behind this block.

- **Type:** `Block`
- **Read\-only:** Yes
- **Static:** No

___

### `section`

```lua
---@type string
BlockBreaking.section
```

Gets the section of the block.

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** No

___

### `isVisited`

```lua
---@type boolean
BlockBreaking.isVisited
```

Indicates whether the block has been visited.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `isMoving`

```lua
---@type boolean
BlockBreaking.isMoving
```

Indicates whether the block is currently moving.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `movingSpeed`

```lua
---@type number
BlockBreaking.movingSpeed
```

Gets the speed at which the block is moving.

- **Type:** `number`
- **Read\-only:** Yes
- **Static:** No

___

### `movingDirection`

```lua
---@type Vector3
BlockBreaking.movingDirection
```

Gets the direction in which the block is moving.

- **Type:** `Vector3`
- **Read\-only:** Yes
- **Static:** No

___

### `isInMovingRest`

```lua
---@type boolean
BlockBreaking.isInMovingRest
```

Indicates whether the block is in a moving rest state.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `intangible`

```lua
---@type boolean
BlockBreaking.intangible
```

Indicates whether the block is intangible.

- **Type:** `boolean`
- **Read\-only:** No
- **Static:** No

___

### `properties`

```lua
---@type ElementPropertyPool
BlockBreaking.properties
```

Gets the properties of the block.

- **Type:** `ElementPropertyPool`
- **Read\-only:** Yes
- **Static:** No

___

### `localData`

```lua
---@type RawLocalData
BlockBreaking.localData
```

The local data associated with this element.

- **Type:** `RawLocalData`
- **Read\-only:** Yes
- **Static:** No

## Methods

### `breakBlock`

```lua
--- @return any
function BlockBreaking:breakBlock()
```

- **Static:** No
- **Returns:** `any`

___

### `getSide`

```lua
--- @param face Face
--- @return Side
function BlockBreaking:getSide(face)
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
function BlockBreaking:markAsVisited()
```

Marks the block as visited.

- **Static:** No
- **Returns:** `any`

___

### `enable`

```lua
--- @return any
function BlockBreaking:enable()
```

Enables the block.

- **Static:** No
- **Returns:** `any`

___

### `disable`

```lua
--- @return any
function BlockBreaking:disable()
```

Disables the block.

- **Static:** No
- **Returns:** `any`

___

### `asLevel`

```lua
--- @return Level
function BlockBreaking:asLevel()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Level`

___

### `asBlock`

```lua
--- @return Block
function BlockBreaking:asBlock()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Block`

___

### `asSide`

```lua
--- @return Side
function BlockBreaking:asSide()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Side`

___

### `asItem`

```lua
--- @return Item
function BlockBreaking:asItem()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Item`

___

### `asEnemy`

```lua
--- @return Enemy
function BlockBreaking:asEnemy()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Enemy`

___

### `asBall`

```lua
--- @return Ball
function BlockBreaking:asBall()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Ball`

___

### `asDecoration`

```lua
--- @return Decoration
function BlockBreaking:asDecoration()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Decoration`

## Custom Events

Specific events that `BlockBreaking` can trigger and that are captured with the `OnCustomEvent` hook.

### `break`

___

### `ballBreak`

- `ball: Ball`

___

### `enemyBreak`

- `enemy: Ball`
