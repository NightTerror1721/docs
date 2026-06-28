# Class `Enemy`

Represents an enemy in the game. Provides access to the enemy's properties, interactions, and state. Allows enabling, disabling, and killing the enemy, as well as managing its interactions.

## Properties

### `type`

```lua
---@type EntityType
Enemy.type
```

- **Type:** `EntityType`
- **Read\-only:** Yes
- **Static:** No

___

### `name`

```lua
---@type string
Enemy.name
```

The name of the enemy.

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** No

___

### `tag`

```lua
---@type string
Enemy.tag
```

The tag of the enemy.

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** No

___

### `position`

```lua
---@type Vector3
Enemy.position
```

The position of the enemy in the game world.

- **Type:** `Vector3`
- **Read\-only:** Yes
- **Static:** No

___

### `rotation`

```lua
---@type Quaternion
Enemy.rotation
```

The rotation of the enemy in the game world.

- **Type:** `Quaternion`
- **Read\-only:** Yes
- **Static:** No

___

### `basis`

```lua
---@type Basis
Enemy.basis
```

The basis of the enemy.

- **Type:** `Basis`
- **Read\-only:** Yes
- **Static:** No

___

### `section`

```lua
---@type string
Enemy.section
```

The section of the level that the enemy is currently in.

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** No

___

### `currentGroundSide`

```lua
---@type Side
Enemy.currentGroundSide
```

The current side of the ground that the enemy is on.

- **Type:** `Side`
- **Read\-only:** Yes
- **Static:** No

___

### `properties`

```lua
---@type ElementPropertyPool
Enemy.properties
```

Gets a list of all interactions that are currently enabled for the enemy.

- **Type:** `ElementPropertyPool`
- **Read\-only:** Yes
- **Static:** No

___

### `localData`

```lua
---@type RawLocalData
Enemy.localData
```

The local data associated with this element.

- **Type:** `RawLocalData`
- **Read\-only:** Yes
- **Static:** No

## Methods

### `enable`

```lua
--- @return any
function Enemy:enable()
```

Enables the enemy.

- **Static:** No
- **Returns:** `any`

___

### `disable`

```lua
--- @return any
function Enemy:disable()
```

Disables the enemy.

- **Static:** No
- **Returns:** `any`

___

### `kill`

```lua
--- @return any
function Enemy:kill()
```

Kills the enemy.

- **Static:** No
- **Returns:** `any`

___

### `enableInteraction`

```lua
--- @param interaction EnemyInteraction
--- @return any
function Enemy:enableInteraction(interaction)
```

Enables a specific interaction for the enemy.

- **Static:** No
- #### Parameters:
  - **interaction:** `EnemyInteraction`
- **Returns:** `any`

___

### `disableInteraction`

```lua
--- @param interaction EnemyInteraction
--- @return any
function Enemy:disableInteraction(interaction)
```

Disables a specific interaction for the enemy.

- **Static:** No
- #### Parameters:
  - **interaction:** `EnemyInteraction`
- **Returns:** `any`

___

### `setInteractionEnabled`

```lua
--- @param interaction EnemyInteraction
--- @param enabled boolean
--- @return any
function Enemy:setInteractionEnabled(interaction, enabled)
```

Sets whether a specific interaction is enabled for the enemy.

- **Static:** No
- #### Parameters:
  - **interaction:** `EnemyInteraction`
  - **enabled:** `boolean`
- **Returns:** `any`

___

### `isInteractionEnabled`

```lua
--- @param interaction EnemyInteraction
--- @return boolean
function Enemy:isInteractionEnabled(interaction)
```

Checks if a specific interaction is enabled for the enemy.

- **Static:** No
- #### Parameters:
  - **interaction:** `EnemyInteraction`
- **Returns:** `boolean`

___

### `asLevel`

```lua
--- @return Level
function Enemy:asLevel()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Level`

___

### `asBlock`

```lua
--- @return Block
function Enemy:asBlock()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Block`

___

### `asSide`

```lua
--- @return Side
function Enemy:asSide()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Side`

___

### `asItem`

```lua
--- @return Item
function Enemy:asItem()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Item`

___

### `asEnemy`

```lua
--- @return Enemy
function Enemy:asEnemy()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Enemy`

___

### `asBall`

```lua
--- @return Ball
function Enemy:asBall()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Ball`

___

### `asDecoration`

```lua
--- @return Decoration
function Enemy:asDecoration()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Decoration`
