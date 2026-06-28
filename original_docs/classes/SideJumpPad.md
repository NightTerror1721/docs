# Class `SideJumpPad`

Inherits from `Side`

## Properties

### `type`

```lua
---@type EntityType
SideJumpPad.type
```

- **Type:** `EntityType`
- **Read\-only:** Yes
- **Static:** No

___

### `id`

```lua
---@type integer
SideJumpPad.id
```

The unique identifier of the side.

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** No

___

### `name`

```lua
---@type string
SideJumpPad.name
```

The name of the side.

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** No

___

### `tag`

```lua
---@type string
SideJumpPad.tag
```

The tag associated with the side.

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** No

___

### `position`

```lua
---@type Vector3
SideJumpPad.position
```

The position of the side.

- **Type:** `Vector3`
- **Read\-only:** Yes
- **Static:** No

___

### `rotation`

```lua
---@type Quaternion
SideJumpPad.rotation
```

The rotation of the side.

- **Type:** `Quaternion`
- **Read\-only:** Yes
- **Static:** No

___

### `centerPosition`

```lua
---@type Vector3
SideJumpPad.centerPosition
```

The center position of the side.

- **Type:** `Vector3`
- **Read\-only:** Yes
- **Static:** No

___

### `normalVector`

```lua
---@type Vector3
SideJumpPad.normalVector
```

The normal vector of the side.

- **Type:** `Vector3`
- **Read\-only:** Yes
- **Static:** No

___

### `tangentVector`

```lua
---@type Vector3
SideJumpPad.tangentVector
```

The tangent vector of the side.

- **Type:** `Vector3`
- **Read\-only:** Yes
- **Static:** No

___

### `bitangentVector`

```lua
---@type Vector3
SideJumpPad.bitangentVector
```

The bitangent vector of the side.

- **Type:** `Vector3`
- **Read\-only:** Yes
- **Static:** No

___

### `block`

```lua
---@type Block
SideJumpPad.block
```

The block to which the side belongs.

- **Type:** `Block`
- **Read\-only:** Yes
- **Static:** No

___

### `blockSlot`

```lua
---@type BlockSlot
SideJumpPad.blockSlot
```

The slot of the block to which the side belongs.

- **Type:** `BlockSlot`
- **Read\-only:** Yes
- **Static:** No

___

### `face`

```lua
---@type Face
SideJumpPad.face
```

The face to which the side belongs.

- **Type:** `Face`
- **Read\-only:** Yes
- **Static:** No

___

### `faceName`

```lua
---@type string
SideJumpPad.faceName
```

The name of the face to which the side belongs.

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** No

___

### `section`

```lua
---@type string
SideJumpPad.section
```

The section to which the side belongs.

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** No

___

### `isIntangible`

```lua
---@type boolean
SideJumpPad.isIntangible
```

Indicates whether the side is intangible.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `hasJumpBan`

```lua
---@type boolean
SideJumpPad.hasJumpBan
```

Indicates whether the side has a jump ban.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `hasMoveBan`

```lua
---@type boolean
SideJumpPad.hasMoveBan
```

Indicates whether the side has a move ban.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `item`

```lua
---@type Item
SideJumpPad.item
```

The item associated with the side, if any.

- **Type:** `Item`
- **Read\-only:** Yes
- **Static:** No

___

### `hasItem`

```lua
---@type boolean
SideJumpPad.hasItem
```

Indicates whether the side has an associated item.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `decoration`

```lua
---@type Decoration
SideJumpPad.decoration
```

The decoration associated with the side, if any.

- **Type:** `Decoration`
- **Read\-only:** Yes
- **Static:** No

___

### `hasDecoration`

```lua
---@type boolean
SideJumpPad.hasDecoration
```

Indicates whether the side has an associated decoration.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `properties`

```lua
---@type ElementPropertyPool
SideJumpPad.properties
```

Gets the properties of the side.

- **Type:** `ElementPropertyPool`
- **Read\-only:** Yes
- **Static:** No

___

### `localData`

```lua
---@type RawLocalData
SideJumpPad.localData
```

The local data associated with this element.

- **Type:** `RawLocalData`
- **Read\-only:** Yes
- **Static:** No

## Methods

### `getAssociatedBasis`

```lua
--- @param orientation Orientation
--- @return Basis
function SideJumpPad:getAssociatedBasis(orientation)
```

Gets the associated basis of the side for a given orientation.

- **Static:** No
- #### Parameters:
  - **orientation:** `Orientation`
- **Returns:** `Basis`

___
```lua
--- @param orientation integer
--- @return Basis
function SideJumpPad:getAssociatedBasis(orientation)
```

Gets the associated basis of the side for a given orientation ID.

- **Static:** No
- #### Parameters:
  - **orientation:** `integer`
- **Returns:** `Basis`

___
```lua
--- @return Basis
function SideJumpPad:getAssociatedBasis()
```

Gets the associated basis of the side for the default orientation.

- **Static:** No
- **Returns:** `Basis`

___

### `isDirectionBlocked`

```lua
--- @param orientation Orientation
--- @return boolean
function SideJumpPad:isDirectionBlocked(orientation)
```

Checks if a given orientation is blocked for the side.

- **Static:** No
- #### Parameters:
  - **orientation:** `Orientation`
- **Returns:** `boolean`

___
```lua
--- @param orientation integer
--- @return boolean
function SideJumpPad:isDirectionBlocked(orientation)
```

Checks if a given orientation ID is blocked for the side.

- **Static:** No
- #### Parameters:
  - **orientation:** `integer`
- **Returns:** `boolean`

___

### `asLevel`

```lua
--- @return Level
function SideJumpPad:asLevel()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Level`

___

### `asBlock`

```lua
--- @return Block
function SideJumpPad:asBlock()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Block`

___

### `asSide`

```lua
--- @return Side
function SideJumpPad:asSide()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Side`

___

### `asItem`

```lua
--- @return Item
function SideJumpPad:asItem()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Item`

___

### `asEnemy`

```lua
--- @return Enemy
function SideJumpPad:asEnemy()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Enemy`

___

### `asBall`

```lua
--- @return Ball
function SideJumpPad:asBall()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Ball`

___

### `asDecoration`

```lua
--- @return Decoration
function SideJumpPad:asDecoration()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Decoration`

## Custom Events

Specific events that `SideJumpPad` can trigger and that are captured with the `OnCustomEvent` hook.

### `farJump`

- `ball: Ball`

___

### `highJump`

- `ball: Ball`
