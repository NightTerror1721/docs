# Class `SideExit`

Inherits from `Side`

## Properties

### `isOpened`

```lua
---@type boolean
SideExit.isOpened
```

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `isClosed`

```lua
---@type boolean
SideExit.isClosed
```

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `nextLevel`

```lua
---@type string
SideExit.nextLevel
```

- **Type:** `string`
- **Read\-only:** No
- **Static:** No

___

### `isSecret`

```lua
---@type boolean
SideExit.isSecret
```

- **Type:** `boolean`
- **Read\-only:** No
- **Static:** No

___

### `canOpenCollectingAllKeys`

```lua
---@type boolean
SideExit.canOpenCollectingAllKeys
```

- **Type:** `boolean`
- **Read\-only:** No
- **Static:** No

___

### `type`

```lua
---@type EntityType
SideExit.type
```

- **Type:** `EntityType`
- **Read\-only:** Yes
- **Static:** No

___

### `id`

```lua
---@type integer
SideExit.id
```

The unique identifier of the side.

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** No

___

### `name`

```lua
---@type string
SideExit.name
```

The name of the side.

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** No

___

### `tag`

```lua
---@type string
SideExit.tag
```

The tag associated with the side.

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** No

___

### `position`

```lua
---@type Vector3
SideExit.position
```

The position of the side.

- **Type:** `Vector3`
- **Read\-only:** Yes
- **Static:** No

___

### `rotation`

```lua
---@type Quaternion
SideExit.rotation
```

The rotation of the side.

- **Type:** `Quaternion`
- **Read\-only:** Yes
- **Static:** No

___

### `centerPosition`

```lua
---@type Vector3
SideExit.centerPosition
```

The center position of the side.

- **Type:** `Vector3`
- **Read\-only:** Yes
- **Static:** No

___

### `normalVector`

```lua
---@type Vector3
SideExit.normalVector
```

The normal vector of the side.

- **Type:** `Vector3`
- **Read\-only:** Yes
- **Static:** No

___

### `tangentVector`

```lua
---@type Vector3
SideExit.tangentVector
```

The tangent vector of the side.

- **Type:** `Vector3`
- **Read\-only:** Yes
- **Static:** No

___

### `bitangentVector`

```lua
---@type Vector3
SideExit.bitangentVector
```

The bitangent vector of the side.

- **Type:** `Vector3`
- **Read\-only:** Yes
- **Static:** No

___

### `block`

```lua
---@type Block
SideExit.block
```

The block to which the side belongs.

- **Type:** `Block`
- **Read\-only:** Yes
- **Static:** No

___

### `blockSlot`

```lua
---@type BlockSlot
SideExit.blockSlot
```

The slot of the block to which the side belongs.

- **Type:** `BlockSlot`
- **Read\-only:** Yes
- **Static:** No

___

### `face`

```lua
---@type Face
SideExit.face
```

The face to which the side belongs.

- **Type:** `Face`
- **Read\-only:** Yes
- **Static:** No

___

### `faceName`

```lua
---@type string
SideExit.faceName
```

The name of the face to which the side belongs.

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** No

___

### `section`

```lua
---@type string
SideExit.section
```

The section to which the side belongs.

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** No

___

### `isIntangible`

```lua
---@type boolean
SideExit.isIntangible
```

Indicates whether the side is intangible.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `hasJumpBan`

```lua
---@type boolean
SideExit.hasJumpBan
```

Indicates whether the side has a jump ban.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `hasMoveBan`

```lua
---@type boolean
SideExit.hasMoveBan
```

Indicates whether the side has a move ban.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `item`

```lua
---@type Item
SideExit.item
```

The item associated with the side, if any.

- **Type:** `Item`
- **Read\-only:** Yes
- **Static:** No

___

### `hasItem`

```lua
---@type boolean
SideExit.hasItem
```

Indicates whether the side has an associated item.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `decoration`

```lua
---@type Decoration
SideExit.decoration
```

The decoration associated with the side, if any.

- **Type:** `Decoration`
- **Read\-only:** Yes
- **Static:** No

___

### `hasDecoration`

```lua
---@type boolean
SideExit.hasDecoration
```

Indicates whether the side has an associated decoration.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `properties`

```lua
---@type ElementPropertyPool
SideExit.properties
```

Gets the properties of the side.

- **Type:** `ElementPropertyPool`
- **Read\-only:** Yes
- **Static:** No

___

### `localData`

```lua
---@type RawLocalData
SideExit.localData
```

The local data associated with this element.

- **Type:** `RawLocalData`
- **Read\-only:** Yes
- **Static:** No

## Methods

### `open`

```lua
--- @return any
function SideExit:open()
```

- **Static:** No
- **Returns:** `any`

___

### `close`

```lua
--- @return any
function SideExit:close()
```

- **Static:** No
- **Returns:** `any`

___

### `getAssociatedBasis`

```lua
--- @param orientation Orientation
--- @return Basis
function SideExit:getAssociatedBasis(orientation)
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
function SideExit:getAssociatedBasis(orientation)
```

Gets the associated basis of the side for a given orientation ID.

- **Static:** No
- #### Parameters:
  - **orientation:** `integer`
- **Returns:** `Basis`

___
```lua
--- @return Basis
function SideExit:getAssociatedBasis()
```

Gets the associated basis of the side for the default orientation.

- **Static:** No
- **Returns:** `Basis`

___

### `isDirectionBlocked`

```lua
--- @param orientation Orientation
--- @return boolean
function SideExit:isDirectionBlocked(orientation)
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
function SideExit:isDirectionBlocked(orientation)
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
function SideExit:asLevel()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Level`

___

### `asBlock`

```lua
--- @return Block
function SideExit:asBlock()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Block`

___

### `asSide`

```lua
--- @return Side
function SideExit:asSide()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Side`

___

### `asItem`

```lua
--- @return Item
function SideExit:asItem()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Item`

___

### `asEnemy`

```lua
--- @return Enemy
function SideExit:asEnemy()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Enemy`

___

### `asBall`

```lua
--- @return Ball
function SideExit:asBall()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Ball`

___

### `asDecoration`

```lua
--- @return Decoration
function SideExit:asDecoration()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Decoration`

## Custom Events

Specific events that `SideExit` can trigger and that are captured with the `OnCustomEvent` hook.

### `open`

___

### `close`
