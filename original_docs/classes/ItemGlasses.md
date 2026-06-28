# Class `ItemGlasses`

Inherits from `Item`

## Properties

### `score`

```lua
---@type integer
ItemGlasses.score
```

- **Type:** `integer`
- **Read\-only:** No
- **Static:** No

___

### `seconds`

```lua
---@type number
ItemGlasses.seconds
```

- **Type:** `number`
- **Read\-only:** No
- **Static:** No

___

### `isAdditive`

```lua
---@type boolean
ItemGlasses.isAdditive
```

- **Type:** `boolean`
- **Read\-only:** No
- **Static:** No

___

### `type`

```lua
---@type EntityType
ItemGlasses.type
```

- **Type:** `EntityType`
- **Read\-only:** Yes
- **Static:** No

___

### `name`

```lua
---@type string
ItemGlasses.name
```

The name of the item, derived from its template.

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** No

___

### `tag`

```lua
---@type string
ItemGlasses.tag
```

The tag associated with the item, used for categorization and identification.

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** No

___

### `position`

```lua
---@type Vector3
ItemGlasses.position
```

The position of the item in the game world.

- **Type:** `Vector3`
- **Read\-only:** Yes
- **Static:** No

___

### `rotation`

```lua
---@type Quaternion
ItemGlasses.rotation
```

The rotation of the item in the game world.

- **Type:** `Quaternion`
- **Read\-only:** Yes
- **Static:** No

___

### `basis`

```lua
---@type Basis
ItemGlasses.basis
```

The basis of the item, representing its local coordinate system.

- **Type:** `Basis`
- **Read\-only:** Yes
- **Static:** No

___

### `slot`

```lua
---@type BlockSlot
ItemGlasses.slot
```

The block slot associated with the item.

- **Type:** `BlockSlot`
- **Read\-only:** Yes
- **Static:** No

___

### `section`

```lua
---@type string
ItemGlasses.section
```

The section to which the item belongs.

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** No

___

### `isEnabled`

```lua
---@type boolean
ItemGlasses.isEnabled
```

Indicates whether the item is enabled.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `isTreasure`

```lua
---@type boolean
ItemGlasses.isTreasure
```

Indicates whether the item is a treasure.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `isKey`

```lua
---@type boolean
ItemGlasses.isKey
```

Indicates whether the item is a key.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `isFruit`

```lua
---@type boolean
ItemGlasses.isFruit
```

Indicates whether the item is a fruit.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `treasureScore`

```lua
---@type integer
ItemGlasses.treasureScore
```

The score associated with the treasure item.

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** No

___

### `developerModeOnly`

```lua
---@type boolean
ItemGlasses.developerModeOnly
```

Indicates whether the item is only available in developer mode.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `properties`

```lua
---@type ElementPropertyPool
ItemGlasses.properties
```

The property pool associated with the item.

- **Type:** `ElementPropertyPool`
- **Read\-only:** Yes
- **Static:** No

___

### `localData`

```lua
---@type RawLocalData
ItemGlasses.localData
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
function ItemGlasses:collect(collectorBall)
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
function ItemGlasses:enable()
```

Enables the item.

- **Static:** No
- **Returns:** `any`

___

### `disable`

```lua
--- @return any
function ItemGlasses:disable()
```

Disables the item.

- **Static:** No
- **Returns:** `any`

___

### `asLevel`

```lua
--- @return Level
function ItemGlasses:asLevel()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Level`

___

### `asBlock`

```lua
--- @return Block
function ItemGlasses:asBlock()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Block`

___

### `asSide`

```lua
--- @return Side
function ItemGlasses:asSide()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Side`

___

### `asItem`

```lua
--- @return Item
function ItemGlasses:asItem()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Item`

___

### `asEnemy`

```lua
--- @return Enemy
function ItemGlasses:asEnemy()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Enemy`

___

### `asBall`

```lua
--- @return Ball
function ItemGlasses:asBall()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Ball`

___

### `asDecoration`

```lua
--- @return Decoration
function ItemGlasses:asDecoration()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Decoration`
