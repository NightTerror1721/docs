# Class `SideTeleport`

Inherits from `Side`

## Properties

### `isActivated`

```lua
---@type boolean
SideTeleport.isActivated
```

- **Type:** `boolean`
- **Read\-only:** No
- **Static:** No

___

### `color`

```lua
---@type LevelColor
SideTeleport.color
```

- **Type:** `LevelColor`
- **Read\-only:** Yes
- **Static:** No

___

### `teleportTarget`

```lua
---@type Side
SideTeleport.teleportTarget
```

- **Type:** `Side`
- **Read\-only:** Yes
- **Static:** No

___

### `customTeleportTarget`

```lua
---@type Side
SideTeleport.customTeleportTarget
```

- **Type:** `Side`
- **Read\-only:** No
- **Static:** No

___

### `hasCustomTeleportTarget`

```lua
---@type boolean
SideTeleport.hasCustomTeleportTarget
```

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `type`

```lua
---@type EntityType
SideTeleport.type
```

- **Type:** `EntityType`
- **Read\-only:** Yes
- **Static:** No

___

### `id`

```lua
---@type integer
SideTeleport.id
```

The unique identifier of the side.

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** No

___

### `name`

```lua
---@type string
SideTeleport.name
```

The name of the side.

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** No

___

### `tag`

```lua
---@type string
SideTeleport.tag
```

The tag associated with the side.

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** No

___

### `position`

```lua
---@type Vector3
SideTeleport.position
```

The position of the side.

- **Type:** `Vector3`
- **Read\-only:** Yes
- **Static:** No

___

### `rotation`

```lua
---@type Quaternion
SideTeleport.rotation
```

The rotation of the side.

- **Type:** `Quaternion`
- **Read\-only:** Yes
- **Static:** No

___

### `centerPosition`

```lua
---@type Vector3
SideTeleport.centerPosition
```

The center position of the side.

- **Type:** `Vector3`
- **Read\-only:** Yes
- **Static:** No

___

### `normalVector`

```lua
---@type Vector3
SideTeleport.normalVector
```

The normal vector of the side.

- **Type:** `Vector3`
- **Read\-only:** Yes
- **Static:** No

___

### `tangentVector`

```lua
---@type Vector3
SideTeleport.tangentVector
```

The tangent vector of the side.

- **Type:** `Vector3`
- **Read\-only:** Yes
- **Static:** No

___

### `bitangentVector`

```lua
---@type Vector3
SideTeleport.bitangentVector
```

The bitangent vector of the side.

- **Type:** `Vector3`
- **Read\-only:** Yes
- **Static:** No

___

### `block`

```lua
---@type Block
SideTeleport.block
```

The block to which the side belongs.

- **Type:** `Block`
- **Read\-only:** Yes
- **Static:** No

___

### `blockSlot`

```lua
---@type BlockSlot
SideTeleport.blockSlot
```

The slot of the block to which the side belongs.

- **Type:** `BlockSlot`
- **Read\-only:** Yes
- **Static:** No

___

### `face`

```lua
---@type Face
SideTeleport.face
```

The face to which the side belongs.

- **Type:** `Face`
- **Read\-only:** Yes
- **Static:** No

___

### `faceName`

```lua
---@type string
SideTeleport.faceName
```

The name of the face to which the side belongs.

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** No

___

### `section`

```lua
---@type string
SideTeleport.section
```

The section to which the side belongs.

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** No

___

### `isIntangible`

```lua
---@type boolean
SideTeleport.isIntangible
```

Indicates whether the side is intangible.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `hasJumpBan`

```lua
---@type boolean
SideTeleport.hasJumpBan
```

Indicates whether the side has a jump ban.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `hasMoveBan`

```lua
---@type boolean
SideTeleport.hasMoveBan
```

Indicates whether the side has a move ban.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `item`

```lua
---@type Item
SideTeleport.item
```

The item associated with the side, if any.

- **Type:** `Item`
- **Read\-only:** Yes
- **Static:** No

___

### `hasItem`

```lua
---@type boolean
SideTeleport.hasItem
```

Indicates whether the side has an associated item.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `decoration`

```lua
---@type Decoration
SideTeleport.decoration
```

The decoration associated with the side, if any.

- **Type:** `Decoration`
- **Read\-only:** Yes
- **Static:** No

___

### `hasDecoration`

```lua
---@type boolean
SideTeleport.hasDecoration
```

Indicates whether the side has an associated decoration.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `properties`

```lua
---@type ElementPropertyPool
SideTeleport.properties
```

Gets the properties of the side.

- **Type:** `ElementPropertyPool`
- **Read\-only:** Yes
- **Static:** No

___

### `localData`

```lua
---@type RawLocalData
SideTeleport.localData
```

The local data associated with this element.

- **Type:** `RawLocalData`
- **Read\-only:** Yes
- **Static:** No

## Methods

### `activate`

```lua
--- @return any
function SideTeleport:activate()
```

- **Static:** No
- **Returns:** `any`

___

### `deactivate`

```lua
--- @return any
function SideTeleport:deactivate()
```

- **Static:** No
- **Returns:** `any`

___

### `getAssociatedBasis`

```lua
--- @param orientation Orientation
--- @return Basis
function SideTeleport:getAssociatedBasis(orientation)
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
function SideTeleport:getAssociatedBasis(orientation)
```

Gets the associated basis of the side for a given orientation ID.

- **Static:** No
- #### Parameters:
  - **orientation:** `integer`
- **Returns:** `Basis`

___
```lua
--- @return Basis
function SideTeleport:getAssociatedBasis()
```

Gets the associated basis of the side for the default orientation.

- **Static:** No
- **Returns:** `Basis`

___

### `isDirectionBlocked`

```lua
--- @param orientation Orientation
--- @return boolean
function SideTeleport:isDirectionBlocked(orientation)
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
function SideTeleport:isDirectionBlocked(orientation)
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
function SideTeleport:asLevel()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Level`

___

### `asBlock`

```lua
--- @return Block
function SideTeleport:asBlock()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Block`

___

### `asSide`

```lua
--- @return Side
function SideTeleport:asSide()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Side`

___

### `asItem`

```lua
--- @return Item
function SideTeleport:asItem()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Item`

___

### `asEnemy`

```lua
--- @return Enemy
function SideTeleport:asEnemy()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Enemy`

___

### `asBall`

```lua
--- @return Ball
function SideTeleport:asBall()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Ball`

___

### `asDecoration`

```lua
--- @return Decoration
function SideTeleport:asDecoration()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Decoration`

## Custom Events

Specific events that `SideTeleport` can trigger and that are captured with the `OnCustomEvent` hook.

### `activate`

___

### `deactivate`

___

### `teleportBall`

- `ball: Ball`

___

### `teleportEnemy`

- `enemy: Enemy`
