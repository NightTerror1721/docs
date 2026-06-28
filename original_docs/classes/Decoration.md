# Class `Decoration`

Represents a decoration in the game. Decorations are non\-interactive elements that enhance the visual appearance of the game world.

## Properties

### `type`

```lua
---@type EntityType
Decoration.type
```

- **Type:** `EntityType`
- **Read\-only:** Yes
- **Static:** No

___

### `name`

```lua
---@type string
Decoration.name
```

The name of the decoration template.

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** No

___

### `tag`

```lua
---@type string
Decoration.tag
```

The tag of the decoration.

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** No

___

### `position`

```lua
---@type Vector3
Decoration.position
```

The position of the decoration in world space.

- **Type:** `Vector3`
- **Read\-only:** Yes
- **Static:** No

___

### `rotation`

```lua
---@type Quaternion
Decoration.rotation
```

The rotation of the decoration in world space.

- **Type:** `Quaternion`
- **Read\-only:** Yes
- **Static:** No

___

### `basis`

```lua
---@type Basis
Decoration.basis
```

The basis of the decoration.

- **Type:** `Basis`
- **Read\-only:** Yes
- **Static:** No

___

### `slot`

```lua
---@type BlockSlot
Decoration.slot
```

The block slot of the decoration.

- **Type:** `BlockSlot`
- **Read\-only:** Yes
- **Static:** No

___

### `section`

```lua
---@type string
Decoration.section
```

The section of the decoration.

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** No

___

### `isEnabled`

```lua
---@type boolean
Decoration.isEnabled
```

Indicates whether the decoration is enabled.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `properties`

```lua
---@type ElementPropertyPool
Decoration.properties
```

- **Type:** `ElementPropertyPool`
- **Read\-only:** Yes
- **Static:** No

___

### `localData`

```lua
---@type RawLocalData
Decoration.localData
```

The local data associated with this element.

- **Type:** `RawLocalData`
- **Read\-only:** Yes
- **Static:** No

## Methods

### `enable`

```lua
--- @return any
function Decoration:enable()
```

Enables the decoration.

- **Static:** No
- **Returns:** `any`

___

### `disable`

```lua
--- @return any
function Decoration:disable()
```

Disables the decoration.

- **Static:** No
- **Returns:** `any`

___

### `asLevel`

```lua
--- @return Level
function Decoration:asLevel()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Level`

___

### `asBlock`

```lua
--- @return Block
function Decoration:asBlock()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Block`

___

### `asSide`

```lua
--- @return Side
function Decoration:asSide()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Side`

___

### `asItem`

```lua
--- @return Item
function Decoration:asItem()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Item`

___

### `asEnemy`

```lua
--- @return Enemy
function Decoration:asEnemy()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Enemy`

___

### `asBall`

```lua
--- @return Ball
function Decoration:asBall()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Ball`

___

### `asDecoration`

```lua
--- @return Decoration
function Decoration:asDecoration()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Decoration`
