# Class `ItemPortalEntrance`

Inherits from `Item`

## Properties

### `color`

```lua
---@type LevelColor
ItemPortalEntrance.color
```

- **Type:** `LevelColor`
- **Read\-only:** Yes
- **Static:** No

___

### `teleportTarget`

```lua
---@type Side
ItemPortalEntrance.teleportTarget
```

- **Type:** `Side`
- **Read\-only:** Yes
- **Static:** No

___

### `customTeleportTarget`

```lua
---@type Side
ItemPortalEntrance.customTeleportTarget
```

- **Type:** `Side`
- **Read\-only:** No
- **Static:** No

___

### `hasCustomTeleportTarget`

```lua
---@type boolean
ItemPortalEntrance.hasCustomTeleportTarget
```

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `type`

```lua
---@type EntityType
ItemPortalEntrance.type
```

- **Type:** `EntityType`
- **Read\-only:** Yes
- **Static:** No

___

### `name`

```lua
---@type string
ItemPortalEntrance.name
```

The name of the item, derived from its template.

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** No

___

### `tag`

```lua
---@type string
ItemPortalEntrance.tag
```

The tag associated with the item, used for categorization and identification.

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** No

___

### `position`

```lua
---@type Vector3
ItemPortalEntrance.position
```

The position of the item in the game world.

- **Type:** `Vector3`
- **Read\-only:** Yes
- **Static:** No

___

### `rotation`

```lua
---@type Quaternion
ItemPortalEntrance.rotation
```

The rotation of the item in the game world.

- **Type:** `Quaternion`
- **Read\-only:** Yes
- **Static:** No

___

### `basis`

```lua
---@type Basis
ItemPortalEntrance.basis
```

The basis of the item, representing its local coordinate system.

- **Type:** `Basis`
- **Read\-only:** Yes
- **Static:** No

___

### `slot`

```lua
---@type BlockSlot
ItemPortalEntrance.slot
```

The block slot associated with the item.

- **Type:** `BlockSlot`
- **Read\-only:** Yes
- **Static:** No

___

### `section`

```lua
---@type string
ItemPortalEntrance.section
```

The section to which the item belongs.

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** No

___

### `isEnabled`

```lua
---@type boolean
ItemPortalEntrance.isEnabled
```

Indicates whether the item is enabled.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `isTreasure`

```lua
---@type boolean
ItemPortalEntrance.isTreasure
```

Indicates whether the item is a treasure.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `isKey`

```lua
---@type boolean
ItemPortalEntrance.isKey
```

Indicates whether the item is a key.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `isFruit`

```lua
---@type boolean
ItemPortalEntrance.isFruit
```

Indicates whether the item is a fruit.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `treasureScore`

```lua
---@type integer
ItemPortalEntrance.treasureScore
```

The score associated with the treasure item.

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** No

___

### `developerModeOnly`

```lua
---@type boolean
ItemPortalEntrance.developerModeOnly
```

Indicates whether the item is only available in developer mode.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `properties`

```lua
---@type ElementPropertyPool
ItemPortalEntrance.properties
```

The property pool associated with the item.

- **Type:** `ElementPropertyPool`
- **Read\-only:** Yes
- **Static:** No

___

### `localData`

```lua
---@type RawLocalData
ItemPortalEntrance.localData
```

The local data associated with this element.

- **Type:** `RawLocalData`
- **Read\-only:** Yes
- **Static:** No

## Methods

### `collect`

```lua
--- @param collectorBall Ball
--- @return any
function ItemPortalEntrance:collect(collectorBall)
```

Collects the item using the specified ball.

- **Static:** No
- #### Parameters:
  - **collectorBall:** `Ball`
- **Returns:** `any`

___

### `enable`

```lua
--- @return any
function ItemPortalEntrance:enable()
```

Enables the item.

- **Static:** No
- **Returns:** `any`

___

### `disable`

```lua
--- @return any
function ItemPortalEntrance:disable()
```

Disables the item.

- **Static:** No
- **Returns:** `any`

___

### `asLevel`

```lua
--- @return Level
function ItemPortalEntrance:asLevel()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Level`

___

### `asBlock`

```lua
--- @return Block
function ItemPortalEntrance:asBlock()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Block`

___

### `asSide`

```lua
--- @return Side
function ItemPortalEntrance:asSide()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Side`

___

### `asItem`

```lua
--- @return Item
function ItemPortalEntrance:asItem()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Item`

___

### `asEnemy`

```lua
--- @return Enemy
function ItemPortalEntrance:asEnemy()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Enemy`

___

### `asBall`

```lua
--- @return Ball
function ItemPortalEntrance:asBall()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Ball`

___

### `asDecoration`

```lua
--- @return Decoration
function ItemPortalEntrance:asDecoration()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Decoration`

## Custom Events

Specific events that `ItemPortalEntrance` can trigger and that are captured with the `OnCustomEvent` hook.

### `teleport`

- `ball: Ball`
