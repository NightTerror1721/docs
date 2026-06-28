# Class `LevelSectionData`

## Properties

### `isMainSection`

```lua
---@type boolean
LevelSectionData.isMainSection
```

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `sectionId`

```lua
---@type string
LevelSectionData.sectionId
```

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** No

___

### `theme`

```lua
---@type string
LevelSectionData.theme
```

- **Type:** `string`
- **Read\-only:** No
- **Static:** No

___

### `music`

```lua
---@type string
LevelSectionData.music
```

- **Type:** `string`
- **Read\-only:** No
- **Static:** No

___

### `darkMode`

```lua
---@type boolean
LevelSectionData.darkMode
```

- **Type:** `boolean`
- **Read\-only:** No
- **Static:** No

___

### `skyboxGridEnabled`

```lua
---@type boolean
LevelSectionData.skyboxGridEnabled
```

- **Type:** `boolean`
- **Read\-only:** No
- **Static:** No

___

### `themeMode`

```lua
---@type ThemeMode
LevelSectionData.themeMode
```

- **Type:** `ThemeMode`
- **Read\-only:** No
- **Static:** No

___

### `lavaPool`

```lua
---@type PoolData
LevelSectionData.lavaPool
```

The lava pool settings for this level section.

- **Type:** `PoolData`
- **Read\-only:** Yes
- **Static:** No

___

### `blocksCount`

```lua
---@type integer
LevelSectionData.blocksCount
```

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** No

___

### `enemiesCount`

```lua
---@type integer
LevelSectionData.enemiesCount
```

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** No

___

### `ballsCount`

```lua
---@type integer
LevelSectionData.ballsCount
```

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** No

## Methods

### `createNewBlock`

```lua
--- @param slot BlockSlot
--- @param template string
--- @return BlockData
function LevelSectionData:createNewBlock(slot, template)
```

- **Static:** No
- #### Parameters:
  - **slot:** `BlockSlot`
  - **template:** `string`
- **Returns:** `BlockData`

___
```lua
--- @param x integer
--- @param y integer
--- @param z integer
--- @param template string
--- @return BlockData
function LevelSectionData:createNewBlock(x, y, z, template)
```

- **Static:** No
- #### Parameters:
  - **x:** `integer`
  - **y:** `integer`
  - **z:** `integer`
  - **template:** `string`
- **Returns:** `BlockData`

___

### `hasBlock`

```lua
--- @param slot BlockSlot
--- @return boolean
function LevelSectionData:hasBlock(slot)
```

- **Static:** No
- #### Parameters:
  - **slot:** `BlockSlot`
- **Returns:** `boolean`

___
```lua
--- @param x integer
--- @param y integer
--- @param z integer
--- @return boolean
function LevelSectionData:hasBlock(x, y, z)
```

- **Static:** No
- #### Parameters:
  - **x:** `integer`
  - **y:** `integer`
  - **z:** `integer`
- **Returns:** `boolean`

___

### `getBlock`

```lua
--- @param slot BlockSlot
--- @return BlockData
function LevelSectionData:getBlock(slot)
```

- **Static:** No
- #### Parameters:
  - **slot:** `BlockSlot`
- **Returns:** `BlockData`

___
```lua
--- @param x integer
--- @param y integer
--- @param z integer
--- @return BlockData
function LevelSectionData:getBlock(x, y, z)
```

- **Static:** No
- #### Parameters:
  - **x:** `integer`
  - **y:** `integer`
  - **z:** `integer`
- **Returns:** `BlockData`

___

### `getAllBlocksIterator`

```lua
--- @return BlockData[]
function LevelSectionData:getAllBlocksIterator()
```

- **Static:** No
- **Returns:** `BlockData[]`

___

### `getAllBlocks`

```lua
--- @return BlockData[]
function LevelSectionData:getAllBlocks()
```

- **Static:** No
- **Returns:** `BlockData[]`

___

### `removeBlock`

```lua
--- @param slot BlockSlot
--- @return boolean
function LevelSectionData:removeBlock(slot)
```

- **Static:** No
- #### Parameters:
  - **slot:** `BlockSlot`
- **Returns:** `boolean`

___
```lua
--- @param x integer
--- @param y integer
--- @param z integer
--- @return boolean
function LevelSectionData:removeBlock(x, y, z)
```

- **Static:** No
- #### Parameters:
  - **x:** `integer`
  - **y:** `integer`
  - **z:** `integer`
- **Returns:** `boolean`

___

### `createNewEnemy`

```lua
--- @param template string
--- @return EnemyData
function LevelSectionData:createNewEnemy(template)
```

- **Static:** No
- #### Parameters:
  - **template:** `string`
- **Returns:** `EnemyData`

___

### `getEnemy`

```lua
--- @param index integer
--- @return EnemyData
function LevelSectionData:getEnemy(index)
```

- **Static:** No
- #### Parameters:
  - **index:** `integer`
- **Returns:** `EnemyData`

___

### `getAllEnemiesIterator`

```lua
--- @return EnemyData[]
function LevelSectionData:getAllEnemiesIterator()
```

- **Static:** No
- **Returns:** `EnemyData[]`

___

### `getAllEnemies`

```lua
--- @return EnemyData[]
function LevelSectionData:getAllEnemies()
```

- **Static:** No
- **Returns:** `EnemyData[]`

___

### `removeEnemy`

```lua
--- @param enemy EnemyData
--- @return boolean
function LevelSectionData:removeEnemy(enemy)
```

- **Static:** No
- #### Parameters:
  - **enemy:** `EnemyData`
- **Returns:** `boolean`

___
```lua
--- @param index integer
--- @return boolean
function LevelSectionData:removeEnemy(index)
```

- **Static:** No
- #### Parameters:
  - **index:** `integer`
- **Returns:** `boolean`

___

### `createNewBall`

```lua
--- @param template string
--- @param order integer
--- @return BallData
function LevelSectionData:createNewBall(template, order)
```

- **Static:** No
- #### Parameters:
  - **template:** `string`
  - **order:** `integer`
- **Returns:** `BallData`

___

### `getBall`

```lua
--- @param index integer
--- @return BallData
function LevelSectionData:getBall(index)
```

- **Static:** No
- #### Parameters:
  - **index:** `integer`
- **Returns:** `BallData`

___

### `getAllBallsIterator`

```lua
--- @return BallData[]
function LevelSectionData:getAllBallsIterator()
```

- **Static:** No
- **Returns:** `BallData[]`

___

### `getAllBalls`

```lua
--- @return BallData[]
function LevelSectionData:getAllBalls()
```

- **Static:** No
- **Returns:** `BallData[]`

___

### `removeBall`

```lua
--- @param ball BallData
--- @return boolean
function LevelSectionData:removeBall(ball)
```

- **Static:** No
- #### Parameters:
  - **ball:** `BallData`
- **Returns:** `boolean`

___
```lua
--- @param index integer
--- @return boolean
function LevelSectionData:removeBall(index)
```

- **Static:** No
- #### Parameters:
  - **index:** `integer`
- **Returns:** `boolean`
