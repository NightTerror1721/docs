# Class `SideOneWay`

Inherits from `Side`

## Properties

### `direction`

```lua
---@type Orientation
SideOneWay.direction
```

- **Type:** `Orientation`
- **Read\-only:** Yes
- **Static:** No

___

### `type`

```lua
---@type EntityType
SideOneWay.type
```

- **Type:** `EntityType`
- **Read\-only:** Yes
- **Static:** No

___

### `id`

```lua
---@type integer
SideOneWay.id
```

The unique identifier of the side.

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** No

___

### `name`

```lua
---@type string
SideOneWay.name
```

The name of the side.

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** No

___

### `tag`

```lua
---@type string
SideOneWay.tag
```

The tag associated with the side.

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** No

___

### `position`

```lua
---@type Vector3
SideOneWay.position
```

The position of the side.

- **Type:** `Vector3`
- **Read\-only:** Yes
- **Static:** No

___

### `rotation`

```lua
---@type Quaternion
SideOneWay.rotation
```

The rotation of the side.

- **Type:** `Quaternion`
- **Read\-only:** Yes
- **Static:** No

___

### `centerPosition`

```lua
---@type Vector3
SideOneWay.centerPosition
```

The center position of the side.

- **Type:** `Vector3`
- **Read\-only:** Yes
- **Static:** No

___

### `normalVector`

```lua
---@type Vector3
SideOneWay.normalVector
```

The normal vector of the side.

- **Type:** `Vector3`
- **Read\-only:** Yes
- **Static:** No

___

### `tangentVector`

```lua
---@type Vector3
SideOneWay.tangentVector
```

The tangent vector of the side.

- **Type:** `Vector3`
- **Read\-only:** Yes
- **Static:** No

___

### `bitangentVector`

```lua
---@type Vector3
SideOneWay.bitangentVector
```

The bitangent vector of the side.

- **Type:** `Vector3`
- **Read\-only:** Yes
- **Static:** No

___

### `block`

```lua
---@type Block
SideOneWay.block
```

The block to which the side belongs.

- **Type:** `Block`
- **Read\-only:** Yes
- **Static:** No

___

### `blockSlot`

```lua
---@type BlockSlot
SideOneWay.blockSlot
```

The slot of the block to which the side belongs.

- **Type:** `BlockSlot`
- **Read\-only:** Yes
- **Static:** No

___

### `face`

```lua
---@type Face
SideOneWay.face
```

The face to which the side belongs.

- **Type:** `Face`
- **Read\-only:** Yes
- **Static:** No

___

### `faceName`

```lua
---@type string
SideOneWay.faceName
```

The name of the face to which the side belongs.

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** No

___

### `section`

```lua
---@type string
SideOneWay.section
```

The section to which the side belongs.

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** No

___

### `isIntangible`

```lua
---@type boolean
SideOneWay.isIntangible
```

Indicates whether the side is intangible.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `hasJumpBan`

```lua
---@type boolean
SideOneWay.hasJumpBan
```

Indicates whether the side has a jump ban.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `hasMoveBan`

```lua
---@type boolean
SideOneWay.hasMoveBan
```

Indicates whether the side has a move ban.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `item`

```lua
---@type Item
SideOneWay.item
```

The item associated with the side, if any.

- **Type:** `Item`
- **Read\-only:** Yes
- **Static:** No

___

### `hasItem`

```lua
---@type boolean
SideOneWay.hasItem
```

Indicates whether the side has an associated item.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `decoration`

```lua
---@type Decoration
SideOneWay.decoration
```

The decoration associated with the side, if any.

- **Type:** `Decoration`
- **Read\-only:** Yes
- **Static:** No

___

### `hasDecoration`

```lua
---@type boolean
SideOneWay.hasDecoration
```

Indicates whether the side has an associated decoration.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `properties`

```lua
---@type ElementPropertyPool
SideOneWay.properties
```

Gets the properties of the side.

- **Type:** `ElementPropertyPool`
- **Read\-only:** Yes
- **Static:** No

___

### `localData`

```lua
---@type RawLocalData
SideOneWay.localData
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
function SideOneWay:getAssociatedBasis(orientation)
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
function SideOneWay:getAssociatedBasis(orientation)
```

Gets the associated basis of the side for a given orientation ID.

- **Static:** No
- #### Parameters:
  - **orientation:** `integer`
- **Returns:** `Basis`

___
```lua
--- @return Basis
function SideOneWay:getAssociatedBasis()
```

Gets the associated basis of the side for the default orientation.

- **Static:** No
- **Returns:** `Basis`

___

### `isDirectionBlocked`

```lua
--- @param orientation Orientation
--- @return boolean
function SideOneWay:isDirectionBlocked(orientation)
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
function SideOneWay:isDirectionBlocked(orientation)
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
function SideOneWay:asLevel()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Level`

___

### `asBlock`

```lua
--- @return Block
function SideOneWay:asBlock()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Block`

___

### `asSide`

```lua
--- @return Side
function SideOneWay:asSide()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Side`

___

### `asItem`

```lua
--- @return Item
function SideOneWay:asItem()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Item`

___

### `asEnemy`

```lua
--- @return Enemy
function SideOneWay:asEnemy()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Enemy`

___

### `asBall`

```lua
--- @return Ball
function SideOneWay:asBall()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Ball`

___

### `asDecoration`

```lua
--- @return Decoration
function SideOneWay:asDecoration()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Decoration`
