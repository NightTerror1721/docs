# Class `LevelSection`

## Properties

### `isMainSection`

```lua
---@type boolean
LevelSection.isMainSection
```

Indicates whether this section is the main section of the level.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `sectionId`

```lua
---@type string
LevelSection.sectionId
```

Gets the unique identifier of this section.

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** No

___

### `theme`

```lua
---@type string
LevelSection.theme
```

Gets the theme of this section.

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** No

___

### `themeMode`

```lua
---@type ThemeMode
LevelSection.themeMode
```

Gets the mode of the theme for this section.

- **Type:** `ThemeMode`
- **Read\-only:** Yes
- **Static:** No

___

### `visitableBlocksCount`

```lua
---@type integer
LevelSection.visitableBlocksCount
```

Gets the color of the level for this section.

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** No

___

### `keysCount`

```lua
---@type integer
LevelSection.keysCount
```

Gets the number of keys in this section.

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** No

___

### `treasureCount`

```lua
---@type integer
LevelSection.treasureCount
```

Gets the number of treasures in this section.

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** No

___

### `hasFruit`

```lua
---@type boolean
LevelSection.hasFruit
```

Indicates whether this section has fruit.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `treasureTotalScore`

```lua
---@type integer
LevelSection.treasureTotalScore
```

Gets the total score of treasures in this section.

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** No

## Methods

### `getBlocksIterator`

```lua
--- @return Block[]
function LevelSection:getBlocksIterator()
```

Gets an iterator for the blocks in this section.

- **Static:** No
- **Returns:** `Block[]`

___

### `getEnemiesIterator`

```lua
--- @return Enemy[]
function LevelSection:getEnemiesIterator()
```

Gets an iterator for the enemies in this section.

- **Static:** No
- **Returns:** `Enemy[]`

___

### `getBallsIterator`

```lua
--- @return Ball[]
function LevelSection:getBallsIterator()
```

Gets an iterator for the balls in this section.

- **Static:** No
- **Returns:** `Ball[]`

___

### `getItemsIterator`

```lua
--- @return Item[]
function LevelSection:getItemsIterator()
```

Gets an iterator for the items in this section.

- **Static:** No
- **Returns:** `Item[]`

___

### `getDecorationsIterator`

```lua
--- @return Decoration[]
function LevelSection:getDecorationsIterator()
```

Gets an iterator for the decorations in this section.

- **Static:** No
- **Returns:** `Decoration[]`

___

### `getBlocks`

```lua
--- @return table
function LevelSection:getBlocks()
```

Gets a table of the blocks in this section.

- **Static:** No
- **Returns:** `table`

___

### `getEnemies`

```lua
--- @return table
function LevelSection:getEnemies()
```

Gets a table of the enemies in this section.

- **Static:** No
- **Returns:** `table`

___

### `getBalls`

```lua
--- @return table
function LevelSection:getBalls()
```

Gets a table of the balls in this section.

- **Static:** No
- **Returns:** `table`

___

### `getItems`

```lua
--- @return table
function LevelSection:getItems()
```

Gets a table of the items in this section.

- **Static:** No
- **Returns:** `table`

___

### `getDecorations`

```lua
--- @return table
function LevelSection:getDecorations()
```

Gets a table of the decorations in this section.

- **Static:** No
- **Returns:** `table`

___

### `getAvailableProjectileSkins`

```lua
--- @return table
function LevelSection:getAvailableProjectileSkins()
```

Gets a table of the available projectile skins in this section.

- **Static:** No
- **Returns:** `table`

___

### `getNextTeleportTarget`

```lua
--- @param origin Side
--- @return Side
function LevelSection:getNextTeleportTarget(origin)
```

- **Static:** No
- #### Parameters:
  - **origin:** `Side`
- **Returns:** `Side`

___

### `getPortalSide`

```lua
--- @param color LevelColor
--- @return Side
function LevelSection:getPortalSide(color)
```

- **Static:** No
- #### Parameters:
  - **color:** `LevelColor`
- **Returns:** `Side`

___

### `getBlock`

```lua
--- @param x integer
--- @param y integer
--- @param z integer
--- @return Block
function LevelSection:getBlock(x, y, z)
```

- **Static:** No
- #### Parameters:
  - **x:** `integer`
  - **y:** `integer`
  - **z:** `integer`
- **Returns:** `Block`

___
```lua
--- @param slot BlockSlot
--- @return Block
function LevelSection:getBlock(slot)
```

- **Static:** No
- #### Parameters:
  - **slot:** `BlockSlot`
- **Returns:** `Block`

___

### `hasBlock`

```lua
--- @param x integer
--- @param y integer
--- @param z integer
--- @return boolean
function LevelSection:hasBlock(x, y, z)
```

Checks if there is a block at the specified coordinates.

- **Static:** No
- #### Parameters:
  - **x:** `integer`
  - **y:** `integer`
  - **z:** `integer`
- **Returns:** `boolean`

___
```lua
--- @param slot BlockSlot
--- @return boolean
function LevelSection:hasBlock(slot)
```

Checks if there is a block for the specified block slot.

- **Static:** No
- #### Parameters:
  - **slot:** `BlockSlot`
- **Returns:** `boolean`

___

### `createProjectile`

```lua
--- @param projectileProperties { skin: string, origin: Vector3, rotation: Quaternion, tag: string?, power: number?, lifetime: number?, speed: number?, acceleration: number?, angularSpeed: number?, angularAcceleration: number?, angularLocalAxisRotation: Vector3, homingStrength: number?, maxHomingRange: number?, autoFire: boolean?, explodeOnCollideWithBlocks: boolean?, explodeOnCollideWithItems: boolean?, explodeOnCollideWithEnemies: boolean?, explodeOnCollideWithBalls: boolean?, explodeOnCollideWithDecorations: boolean?, explodeOnCollideWithProjectiles: boolean?, onFire: function?, onExplode: function?, onUpdate: function? }
--- @return Projectile
function LevelSection:createProjectile(projectileProperties)
```

Creates a projectile with the specified properties.

- **Static:** No
- #### Parameters:
  - **projectileProperties:** `{ skin: string, origin: Vector3, rotation: Quaternion, tag: string?, power: number?, lifetime: number?, speed: number?, acceleration: number?, angularSpeed: number?, angularAcceleration: number?, angularLocalAxisRotation: Vector3, homingStrength: number?, maxHomingRange: number?, autoFire: boolean?, explodeOnCollideWithBlocks: boolean?, explodeOnCollideWithItems: boolean?, explodeOnCollideWithEnemies: boolean?, explodeOnCollideWithBalls: boolean?, explodeOnCollideWithDecorations: boolean?, explodeOnCollideWithProjectiles: boolean?, onFire: function?, onExplode: function?, onUpdate: function? }`
- **Returns:** `Projectile`

___
```lua
--- @param request ProjectileRequest
--- @return Projectile
function LevelSection:createProjectile(request)
```

Creates a projectile with the specified properties.

- **Static:** No
- #### Parameters:
  - **request:** `ProjectileRequest`
- **Returns:** `Projectile`
