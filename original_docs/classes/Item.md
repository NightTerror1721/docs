# Class `Item`

Represents an item in the game. Provides methods to interact with and manipulate items.

## Properties

### `type`

```lua
---@type EntityType
Item.type
```

- **Type:** `EntityType`
- **Read\-only:** Yes
- **Static:** No

___

### `name`

```lua
---@type string
Item.name
```

The name of the item, derived from its template.

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** No

___

### `tag`

```lua
---@type string
Item.tag
```

The tag associated with the item, used for categorization and identification.

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** No

___

### `position`

```lua
---@type Vector3
Item.position
```

The position of the item in the game world.

- **Type:** `Vector3`
- **Read\-only:** Yes
- **Static:** No

___

### `rotation`

```lua
---@type Quaternion
Item.rotation
```

The rotation of the item in the game world.

- **Type:** `Quaternion`
- **Read\-only:** Yes
- **Static:** No

___

### `basis`

```lua
---@type Basis
Item.basis
```

The basis of the item, representing its local coordinate system.

- **Type:** `Basis`
- **Read\-only:** Yes
- **Static:** No

___

### `slot`

```lua
---@type BlockSlot
Item.slot
```

The block slot associated with the item.

- **Type:** `BlockSlot`
- **Read\-only:** Yes
- **Static:** No

___

### `section`

```lua
---@type string
Item.section
```

The section to which the item belongs.

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** No

___

### `isEnabled`

```lua
---@type boolean
Item.isEnabled
```

Indicates whether the item is enabled.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `isTreasure`

```lua
---@type boolean
Item.isTreasure
```

Indicates whether the item is a treasure.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `isKey`

```lua
---@type boolean
Item.isKey
```

Indicates whether the item is a key.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `isFruit`

```lua
---@type boolean
Item.isFruit
```

Indicates whether the item is a fruit.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `treasureScore`

```lua
---@type integer
Item.treasureScore
```

The score associated with the treasure item.

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** No

___

### `developerModeOnly`

```lua
---@type boolean
Item.developerModeOnly
```

Indicates whether the item is only available in developer mode.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `properties`

```lua
---@type ElementPropertyPool
Item.properties
```

The property pool associated with the item.

- **Type:** `ElementPropertyPool`
- **Read\-only:** Yes
- **Static:** No

___

### `localData`

```lua
---@type RawLocalData
Item.localData
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
function Item:collect(collectorBall)
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
function Item:enable()
```

Enables the item.

- **Static:** No
- **Returns:** `any`

___

### `disable`

```lua
--- @return any
function Item:disable()
```

Disables the item.

- **Static:** No
- **Returns:** `any`

___

### `asLevel`

```lua
--- @return Level
function Item:asLevel()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Level`

___

### `asBlock`

```lua
--- @return Block
function Item:asBlock()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Block`

___

### `asSide`

```lua
--- @return Side
function Item:asSide()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Side`

___

### `asItem`

```lua
--- @return Item
function Item:asItem()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Item`

___

### `asEnemy`

```lua
--- @return Enemy
function Item:asEnemy()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Enemy`

___

### `asBall`

```lua
--- @return Ball
function Item:asBall()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Ball`

___

### `asDecoration`

```lua
--- @return Decoration
function Item:asDecoration()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Decoration`
