# Namespace `Level`

Represents a level in the game. Provides methods to interact with and manipulate levels.

## Variables

### `tag`

```lua
--- static
---@type string
Level.tag
```

The tag associated with the level, used for categorization and identification.

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** Yes

___

### `localData`

```lua
--- static
---@type RawLocalData
Level.localData
```

The local data associated with the level.

- **Type:** `RawLocalData`
- **Read\-only:** Yes
- **Static:** Yes

___

### `type`

```lua
--- static
---@type EntityType
Level.type
```

- **Type:** `EntityType`
- **Read\-only:** Yes
- **Static:** Yes

___

### `campaignGlobalData`

```lua
--- static
---@type LocalData
Level.campaignGlobalData
```

The global data storage for the campaign.

- **Type:** `LocalData`
- **Read\-only:** Yes
- **Static:** Yes

___

### `mainSection`

```lua
--- static
---@type LevelSection
Level.mainSection
```

The main section of the level.

- **Type:** `LevelSection`
- **Read\-only:** Yes
- **Static:** Yes

___

### `campaign`

```lua
--- static
---@type string
Level.campaign
```

The name of the campaign the level belongs to.

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** Yes

___

### `campaignEpisode`

```lua
--- static
---@type string
Level.campaignEpisode
```

The name of the current episode in the campaign.

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** Yes

___

### `campaignEpisodeIndex`

```lua
--- static
---@type integer
Level.campaignEpisodeIndex
```

The index of the current episode in the campaign.

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** Yes

___

### `campaignLevelName`

```lua
--- static
---@type string
Level.campaignLevelName
```

The name of the current level in the campaign.

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** Yes

___

### `campaignLevelIndex`

```lua
--- static
---@type integer
Level.campaignLevelIndex
```

The index of the current level in the campaign.

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** Yes

___

### `isCampaignNormalLevel`

```lua
--- static
---@type boolean
Level.isCampaignNormalLevel
```

Indicates if the current level is a normal level.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** Yes

___

### `isCampaignBonusLevel`

```lua
--- static
---@type boolean
Level.isCampaignBonusLevel
```

Indicates if the current level is a bonus level.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** Yes

___

### `isCampaignSecretLevel`

```lua
--- static
---@type boolean
Level.isCampaignSecretLevel
```

Indicates if the current level is a secret level.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** Yes

___

### `campaignNormalLevelNumber`

```lua
--- static
---@type integer
Level.campaignNormalLevelNumber
```

The number of the current normal level in the campaign.

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** Yes

___

### `visitableBlocksCount`

```lua
--- static
---@type integer
Level.visitableBlocksCount
```

The number of visitable blocks in the level.

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** Yes

___

### `keysCount`

```lua
--- static
---@type integer
Level.keysCount
```

The number of keys in the level.

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** Yes

___

### `treasureCount`

```lua
--- static
---@type integer
Level.treasureCount
```

The number of treasures in the level.

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** Yes

___

### `hasFruit`

```lua
--- static
---@type boolean
Level.hasFruit
```

Indicates if the level has fruit.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** Yes

___

### `treasureTotalScore`

```lua
--- static
---@type integer
Level.treasureTotalScore
```

The total score of treasures in the level.

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** Yes

___

### `maxTime`

```lua
--- static
---@type number
Level.maxTime
```

The maximum time allowed for the level.

- **Type:** `number`
- **Read\-only:** Yes
- **Static:** Yes

___

### `initialTime`

```lua
--- static
---@type number
Level.initialTime
```

The initial time for the level.

- **Type:** `number`
- **Read\-only:** Yes
- **Static:** Yes

___

### `timer`

```lua
--- static
---@type Timer
Level.timer
```

The timer for the level.

- **Type:** `Timer`
- **Read\-only:** Yes
- **Static:** Yes

___

### `currentBall`

```lua
--- static
---@type Ball
Level.currentBall
```

The current ball in the level.

- **Type:** `Ball`
- **Read\-only:** Yes
- **Static:** Yes

___

### `areFruitsEnabled`

```lua
--- static
---@type boolean
Level.areFruitsEnabled
```

Indicates if fruits are enabled in the level.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** Yes

___

### `currentFruitIndex`

```lua
--- static
---@type integer
Level.currentFruitIndex
```

The index of the current fruit.

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** Yes

___

### `areAllRequiredFruitsToBonusCollected`

```lua
--- static
---@type boolean
Level.areAllRequiredFruitsToBonusCollected
```

Indicates if all required fruits for the bonus are collected.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** Yes

___

### `areAllFruitsCollected`

```lua
--- static
---@type boolean
Level.areAllFruitsCollected
```

Indicates if all fruits are collected.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** Yes

___

### `glassesTime`

```lua
--- static
---@type number
Level.glassesTime
```

The time for the glasses effect.

- **Type:** `number`
- **Read\-only:** No
- **Static:** Yes

___

### `isDarkModeEnabled`

```lua
--- static
---@type boolean
Level.isDarkModeEnabled
```

Indicates if dark mode is enabled in the level.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** Yes

___

### `lavaPool`

```lua
--- static
---@type LavaPool
Level.lavaPool
```

The lava pool in the level environment.

- **Type:** `LavaPool`
- **Read\-only:** Yes
- **Static:** Yes

___

### `remainingTime`

```lua
--- static
---@type number
Level.remainingTime
```

The remaining time for the level (hourglass time).

- **Type:** `number`
- **Read\-only:** Yes
- **Static:** Yes

___

### `isHourglassEnabled`

```lua
--- static
---@type boolean
Level.isHourglassEnabled
```

Indicates if the hourglass is enabled.

- **Type:** `boolean`
- **Read\-only:** No
- **Static:** Yes

___

### `isHourglassBlocked`

```lua
--- static
---@type boolean
Level.isHourglassBlocked
```

Indicates if the hourglass is blocked.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** Yes

___

### `hourglassEndsCausesLoseLevel`

```lua
--- static
---@type boolean
Level.hourglassEndsCausesLoseLevel
```

Indicates if the hourglass ending causes the player to lose the level.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** Yes

___

### `currentLives`

```lua
--- static
---@type integer
Level.currentLives
```

The current number of lives.

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** Yes

___

### `hasInfiniteLives`

```lua
--- static
---@type boolean
Level.hasInfiniteLives
```

Indicates if the player has infinite lives.

- **Type:** `boolean`
- **Read\-only:** No
- **Static:** Yes

___

### `remainingKeys`

```lua
--- static
---@type integer
Level.remainingKeys
```

The number of remaining keys.

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** Yes

___

### `collectedKeys`

```lua
--- static
---@type integer
Level.collectedKeys
```

The number of collected keys.

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** Yes

___

### `areAllKeysCollected`

```lua
--- static
---@type boolean
Level.areAllKeysCollected
```

Indicates if all keys are collected.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** Yes

___

### `isPlayerScoreEnabled`

```lua
--- static
---@type boolean
Level.isPlayerScoreEnabled
```

Indicates if the player score is enabled.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** Yes

___

### `isLevelScoreEnabled`

```lua
--- static
---@type boolean
Level.isLevelScoreEnabled
```

Indicates if the level score is enabled.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** Yes

___

### `playerScore`

```lua
--- static
---@type integer
Level.playerScore
```

The player's current score.

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** Yes

___

### `levelScore`

```lua
--- static
---@type integer
Level.levelScore
```

The current level score.

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** Yes

___

### `levelLosePenalty`

```lua
--- static
---@type integer
Level.levelLosePenalty
```

The penalty for losing the level.

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** Yes

___

### `levelRestartPenalty`

```lua
--- static
---@type integer
Level.levelRestartPenalty
```

The penalty for restarting the level.

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** Yes

___

### `treasureScoreCount`

```lua
--- static
---@type integer
Level.treasureScoreCount
```

The number of treasures collected in the level.

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** Yes

___

### `treasureCollected`

```lua
--- static
---@type integer
Level.treasureCollected
```

The number of treasures collected by the player.

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** Yes

___

### `treasureScoreCollected`

```lua
--- static
---@type integer
Level.treasureScoreCollected
```

The score from collected treasures.

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** Yes

___

### `treasureCollectedPercentage`

```lua
--- static
---@type number
Level.treasureCollectedPercentage
```

The percentage of treasures collected.

- **Type:** `number`
- **Read\-only:** Yes
- **Static:** Yes

___

### `isElapsedTimeEnabled`

```lua
--- static
---@type boolean
Level.isElapsedTimeEnabled
```

Indicates if the elapsed time is enabled.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** Yes

___

### `elapsedTime`

```lua
--- static
---@type number
Level.elapsedTime
```

The elapsed time for the level.

- **Type:** `number`
- **Read\-only:** Yes
- **Static:** Yes

___

### `isSleepingPillEffectActive`

```lua
--- static
---@type boolean
Level.isSleepingPillEffectActive
```

Indicates if the sleeping pill effect is active.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** Yes

## Functions

### `getAllBlocksIterator`

```lua
--- @return Block[]
function Level.getAllBlocksIterator()
```

Gets all blocks in the main section.

- **Static:** No
- **Returns:** `Block[]`

___

### `getAllEnemiesIterator`

```lua
--- @return Enemy[]
function Level.getAllEnemiesIterator()
```

Gets all enemies in the main section.

- **Static:** No
- **Returns:** `Enemy[]`

___

### `getAllBallsIterator`

```lua
--- @return Ball[]
function Level.getAllBallsIterator()
```

Gets all balls in the main section.

- **Static:** No
- **Returns:** `Ball[]`

___

### `getAllItemsIterator`

```lua
--- @return Item[]
function Level.getAllItemsIterator()
```

Gets all items in the main section.

- **Static:** No
- **Returns:** `Item[]`

___

### `getAllDecorationsIterator`

```lua
--- @return Decoration[]
function Level.getAllDecorationsIterator()
```

Gets all decorations in the main section.

- **Static:** No
- **Returns:** `Decoration[]`

___

### `getBlocks`

```lua
--- @return Block[]
function Level.getBlocks()
```

- **Static:** No
- **Returns:** `Block[]`

___

### `getEnemies`

```lua
--- @return Enemy[]
function Level.getEnemies()
```

- **Static:** No
- **Returns:** `Enemy[]`

___

### `getBalls`

```lua
--- @return Ball[]
function Level.getBalls()
```

- **Static:** No
- **Returns:** `Ball[]`

___

### `getItems`

```lua
--- @return Item[]
function Level.getItems()
```

- **Static:** No
- **Returns:** `Item[]`

___

### `getDecorations`

```lua
--- @return Decoration[]
function Level.getDecorations()
```

- **Static:** No
- **Returns:** `Decoration[]`

___

### `getBall`

```lua
--- @param index integer
--- @return Ball
function Level.getBall(index)
```

Gets a ball by its index.

- **Static:** No
- #### Parameters:
  - **index:** `integer`
- **Returns:** `Ball`

___

### `getNextTeleportTarget`

```lua
--- @param origin Side
--- @return Side
function Level.getNextTeleportTarget(origin)
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
function Level.getPortalSide(color)
```

- **Static:** No
- #### Parameters:
  - **color:** `LevelColor`
- **Returns:** `Side`

___
```lua
--- @param sectionId string
--- @param color LevelColor
--- @return Side
function Level.getPortalSide(sectionId, color)
```

- **Static:** No
- #### Parameters:
  - **sectionId:** `string`
  - **color:** `LevelColor`
- **Returns:** `Side`

___

### `getBlock`

```lua
--- @param x integer
--- @param y integer
--- @param z integer
--- @return Block
function Level.getBlock(x, y, z)
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
function Level.getBlock(slot)
```

- **Static:** No
- #### Parameters:
  - **slot:** `BlockSlot`
- **Returns:** `Block`

___
```lua
--- @param sectionId string
--- @param x integer
--- @param y integer
--- @param z integer
--- @return Block
function Level.getBlock(sectionId, x, y, z)
```

- **Static:** No
- #### Parameters:
  - **sectionId:** `string`
  - **x:** `integer`
  - **y:** `integer`
  - **z:** `integer`
- **Returns:** `Block`

___
```lua
--- @param sectionId string
--- @param slot BlockSlot
--- @return Block
function Level.getBlock(sectionId, slot)
```

- **Static:** No
- #### Parameters:
  - **sectionId:** `string`
  - **slot:** `BlockSlot`
- **Returns:** `Block`

___

### `hasBlock`

```lua
--- @param x integer
--- @param y integer
--- @param z integer
--- @return boolean
function Level.hasBlock(x, y, z)
```

Checks if a block exists at the given coordinates.

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
function Level.hasBlock(slot)
```

Checks if a block exists at the given slot.

- **Static:** No
- #### Parameters:
  - **slot:** `BlockSlot`
- **Returns:** `boolean`

___
```lua
--- @param sectionId string
--- @param x integer
--- @param y integer
--- @param z integer
--- @return boolean
function Level.hasBlock(sectionId, x, y, z)
```

Checks if a block exists at the given coordinates in a specified section.

- **Static:** No
- #### Parameters:
  - **sectionId:** `string`
  - **x:** `integer`
  - **y:** `integer`
  - **z:** `integer`
- **Returns:** `boolean`

___
```lua
--- @param sectionId string
--- @param slot BlockSlot
--- @return boolean
function Level.hasBlock(sectionId, slot)
```

Checks if a block exists at the given slot in a specified section.

- **Static:** No
- #### Parameters:
  - **sectionId:** `string`
  - **slot:** `BlockSlot`
- **Returns:** `boolean`

___

### `getSectionsIterator`

```lua
--- @return LevelSection[]
function Level.getSectionsIterator()
```

Gets all sections in the level.

- **Static:** No
- **Returns:** `LevelSection[]`

___

### `getAllSectionsBlocksIterator`

```lua
--- @return Block[]
function Level.getAllSectionsBlocksIterator()
```

Gets all blocks in all sections.

- **Static:** No
- **Returns:** `Block[]`

___

### `getAllSectionsEnemiesIterator`

```lua
--- @return Enemy[]
function Level.getAllSectionsEnemiesIterator()
```

Gets all enemies in all sections.

- **Static:** No
- **Returns:** `Enemy[]`

___

### `getAllSectionsBallsIterator`

```lua
--- @return Ball[]
function Level.getAllSectionsBallsIterator()
```

Gets all balls in all sections.

- **Static:** No
- **Returns:** `Ball[]`

___

### `getAllSectionsItemsIterator`

```lua
--- @return Item[]
function Level.getAllSectionsItemsIterator()
```

Gets all items in all sections.

- **Static:** No
- **Returns:** `Item[]`

___

### `getAllSectionsDecorationsIterator`

```lua
--- @return Decoration[]
function Level.getAllSectionsDecorationsIterator()
```

Gets all decorations in all sections.

- **Static:** No
- **Returns:** `Decoration[]`

___

### `getSections`

```lua
--- @return table
function Level.getSections()
```

Gets all sections in the level as a Lua table.

- **Static:** No
- **Returns:** `table`

___

### `getAllSectionsBlocks`

```lua
--- @return table
function Level.getAllSectionsBlocks()
```

Gets all blocks in all sections as a Lua table.

- **Static:** No
- **Returns:** `table`

___

### `getAllSectionsEnemies`

```lua
--- @return table
function Level.getAllSectionsEnemies()
```

Gets all enemies in all sections as a Lua table.

- **Static:** No
- **Returns:** `table`

___

### `getAllSectionsBalls`

```lua
--- @return table
function Level.getAllSectionsBalls()
```

Gets all balls in all sections as a Lua table.

- **Static:** No
- **Returns:** `table`

___

### `getAllSectionsItems`

```lua
--- @return table
function Level.getAllSectionsItems()
```

Gets all items in all sections as a Lua table.

- **Static:** No
- **Returns:** `table`

___

### `getAllSectionsDecorations`

```lua
--- @return table
function Level.getAllSectionsDecorations()
```

Gets all decorations in all sections as a Lua table.

- **Static:** No
- **Returns:** `table`

___

### `getSection`

```lua
--- @param sectionId string
--- @return LevelSection
function Level.getSection(sectionId)
```

- **Static:** No
- #### Parameters:
  - **sectionId:** `string`
- **Returns:** `LevelSection`

___

### `hasSection`

```lua
--- @param sectionId string
--- @return boolean
function Level.hasSection(sectionId)
```

Checks if a section exists by its ID.

- **Static:** No
- #### Parameters:
  - **sectionId:** `string`
- **Returns:** `boolean`

___

### `delayAction`

```lua
--- @param delayTime number
--- @param action fun(): void
--- @return any
function Level.delayAction(delayTime, action)
```

Delays the execution of an action by a specified time.

- **Static:** No
- #### Parameters:
  - **delayTime:** `number`
  - **action:** `fun(): void`
- **Returns:** `any`

___

### `isFruitEnabled`

```lua
--- @param fruitIndex integer
--- @return boolean
function Level.isFruitEnabled(fruitIndex)
```

Checks if a fruit is enabled by its index.

- **Static:** No
- #### Parameters:
  - **fruitIndex:** `integer`
- **Returns:** `boolean`

___

### `isFruitCollected`

```lua
--- @param fruitIndex integer
--- @return boolean
function Level.isFruitCollected(fruitIndex)
```

Checks if a fruit is collected by its index.

- **Static:** No
- #### Parameters:
  - **fruitIndex:** `integer`
- **Returns:** `boolean`

___

### `activateDarkMode`

```lua
--- @return any
function Level.activateDarkMode()
```

Activates dark mode.

- **Static:** No
- **Returns:** `any`

___

### `deactivateDarkMode`

```lua
--- @return any
function Level.deactivateDarkMode()
```

Deactivates dark mode.

- **Static:** No
- **Returns:** `any`

___

### `invertHourglass`

```lua
--- @return any
function Level.invertHourglass()
```

Inverts the hourglass, flipping its state.

- **Static:** No
- **Returns:** `any`

___

### `increaseHourglassTime`

```lua
--- @param amount number
--- @return any
function Level.increaseHourglassTime(amount)
```

Increases the hourglass time by a specified amount.

- **Static:** No
- #### Parameters:
  - **amount:** `number`
- **Returns:** `any`

___

### `decreaseHourglassTime`

```lua
--- @param amount number
--- @return any
function Level.decreaseHourglassTime(amount)
```

Decreases the hourglass time by a specified amount.

- **Static:** No
- #### Parameters:
  - **amount:** `number`
- **Returns:** `any`

___

### `giveLives`

```lua
--- @param amount integer
--- @return any
function Level.giveLives(amount)
```

Gives a specified amount of lives to the player.

- **Static:** No
- #### Parameters:
  - **amount:** `integer`
- **Returns:** `any`

___

### `loseLives`

```lua
--- @param amount integer
--- @return any
function Level.loseLives(amount)
```

Loses a specified amount of lives from the player.

- **Static:** No
- #### Parameters:
  - **amount:** `integer`
- **Returns:** `any`

___

### `giveScore`

```lua
--- @param score integer
--- @return any
function Level.giveScore(score)
```

Gives a specified amount of score to the player.

- **Static:** No
- #### Parameters:
  - **score:** `integer`
- **Returns:** `any`

___

### `activateSleepingPillEffect`

```lua
--- @param seconds number
--- @return any
function Level.activateSleepingPillEffect(seconds)
```

Activates the sleeping pill effect for a specified duration.

- **Static:** No
- #### Parameters:
  - **seconds:** `number`
- **Returns:** `any`

___

### `deactivateSleepingPillEffect`

```lua
--- @return any
function Level.deactivateSleepingPillEffect()
```

Deactivates the sleeping pill effect.

- **Static:** No
- **Returns:** `any`

___

### `saveCheckpoint`

```lua
--- @return any
function Level.saveCheckpoint()
```

Saves the current state of the level as a checkpoint.

- **Static:** No
- **Returns:** `any`

___
```lua
--- @param side Side
--- @return any
function Level.saveCheckpoint(side)
```

Saves the current state of the level as a checkpoint for a specific side.

- **Static:** No
- #### Parameters:
  - **side:** `Side`
- **Returns:** `any`

___

### `loseLevel`

```lua
--- @param cause LostLevelCause
--- @return any
function Level.loseLevel(cause)
```

Loses the level with a specified cause.

- **Static:** No
- #### Parameters:
  - **cause:** `LostLevelCause`
- **Returns:** `any`

___
```lua
--- @param cause string
--- @param causeIcon LostLevelCause
--- @return any
function Level.loseLevel(cause, causeIcon)
```

Loses the level with a custom cause and icon.

- **Static:** No
- #### Parameters:
  - **cause:** `string`
  - **causeIcon:** `LostLevelCause`
- **Returns:** `any`

___
```lua
--- @param cause string
--- @return any
function Level.loseLevel(cause)
```

Loses the level with a custom cause.

- **Static:** No
- #### Parameters:
  - **cause:** `string`
- **Returns:** `any`

___

### `restartLevel`

```lua
--- @return any
function Level.restartLevel()
```

Restarts the current level.

- **Static:** No
- **Returns:** `any`

___

### `completeLevel`

```lua
--- @param nextLevel string
--- @return any
function Level.completeLevel(nextLevel)
```

Completes the current level.

- **Static:** No
- #### Parameters:
  - **nextLevel:** `string`
- **Returns:** `any`

___
```lua
--- @return any
function Level.completeLevel()
```

Completes the current level.

- **Static:** No
- **Returns:** `any`

___

### `createProjectile`

```lua
--- @param sectionId string
--- @param projectileProperties { skin: string, origin: Vector3, rotation: Quaternion, tag: string?, power: number?, lifetime: number?, speed: number?, acceleration: number?, angularSpeed: number?, angularAcceleration: number?, angularLocalAxisRotation: Vector3, homingStrength: number?, maxHomingRange: number?, autoFire: boolean?, explodeOnCollideWithBlocks: boolean?, explodeOnCollideWithItems: boolean?, explodeOnCollideWithEnemies: boolean?, explodeOnCollideWithBalls: boolean?, explodeOnCollideWithDecorations: boolean?, explodeOnCollideWithProjectiles: boolean?, onFire: function?, onExplode: function?, onUpdate: function? }
--- @return Projectile
function Level.createProjectile(sectionId, projectileProperties)
```

Creates a projectile in the specified section with given properties.

- **Static:** No
- #### Parameters:
  - **sectionId:** `string`
  - **projectileProperties:** `{ skin: string, origin: Vector3, rotation: Quaternion, tag: string?, power: number?, lifetime: number?, speed: number?, acceleration: number?, angularSpeed: number?, angularAcceleration: number?, angularLocalAxisRotation: Vector3, homingStrength: number?, maxHomingRange: number?, autoFire: boolean?, explodeOnCollideWithBlocks: boolean?, explodeOnCollideWithItems: boolean?, explodeOnCollideWithEnemies: boolean?, explodeOnCollideWithBalls: boolean?, explodeOnCollideWithDecorations: boolean?, explodeOnCollideWithProjectiles: boolean?, onFire: function?, onExplode: function?, onUpdate: function? }`
- **Returns:** `Projectile`

___
```lua
--- @param sectionId string
--- @param request ProjectileRequest
--- @return Projectile
function Level.createProjectile(sectionId, request)
```

Creates a projectile in the specified section with given request parameters.

- **Static:** No
- #### Parameters:
  - **sectionId:** `string`
  - **request:** `ProjectileRequest`
- **Returns:** `Projectile`

___
```lua
--- @param projectileProperties { skin: string, origin: Vector3, rotation: Quaternion, tag: string?, power: number?, lifetime: number?, speed: number?, acceleration: number?, angularSpeed: number?, angularAcceleration: number?, angularLocalAxisRotation: Vector3, homingStrength: number?, maxHomingRange: number?, autoFire: boolean?, explodeOnCollideWithBlocks: boolean?, explodeOnCollideWithItems: boolean?, explodeOnCollideWithEnemies: boolean?, explodeOnCollideWithBalls: boolean?, explodeOnCollideWithDecorations: boolean?, explodeOnCollideWithProjectiles: boolean?, onFire: function?, onExplode: function?, onUpdate: function? }
--- @return Projectile
function Level.createProjectile(projectileProperties)
```

Creates a projectile in the main section with given properties.

- **Static:** No
- #### Parameters:
  - **projectileProperties:** `{ skin: string, origin: Vector3, rotation: Quaternion, tag: string?, power: number?, lifetime: number?, speed: number?, acceleration: number?, angularSpeed: number?, angularAcceleration: number?, angularLocalAxisRotation: Vector3, homingStrength: number?, maxHomingRange: number?, autoFire: boolean?, explodeOnCollideWithBlocks: boolean?, explodeOnCollideWithItems: boolean?, explodeOnCollideWithEnemies: boolean?, explodeOnCollideWithBalls: boolean?, explodeOnCollideWithDecorations: boolean?, explodeOnCollideWithProjectiles: boolean?, onFire: function?, onExplode: function?, onUpdate: function? }`
- **Returns:** `Projectile`

___
```lua
--- @param request ProjectileRequest
--- @return Projectile
function Level.createProjectile(request)
```

Creates a projectile in the main section with given request parameters.

- **Static:** No
- #### Parameters:
  - **request:** `ProjectileRequest`
- **Returns:** `Projectile`

___

### `getAvailableProjectileSkins`

```lua
--- @param sectionId string
--- @return table
function Level.getAvailableProjectileSkins(sectionId)
```

Gets the available projectile skins in the specified section.

- **Static:** No
- #### Parameters:
  - **sectionId:** `string`
- **Returns:** `table`

___
```lua
--- @return table
function Level.getAvailableProjectileSkins()
```

Gets the available projectile skins in the main section.

- **Static:** No
- **Returns:** `table`

___

### `asLevel`

```lua
--- @return Level
function Level.asLevel()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Level`

___

### `asBlock`

```lua
--- @return Block
function Level.asBlock()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Block`

___

### `asSide`

```lua
--- @return Side
function Level.asSide()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Side`

___

### `asItem`

```lua
--- @return Item
function Level.asItem()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Item`

___

### `asEnemy`

```lua
--- @return Enemy
function Level.asEnemy()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Enemy`

___

### `asBall`

```lua
--- @return Ball
function Level.asBall()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Ball`

___

### `asDecoration`

```lua
--- @return Decoration
function Level.asDecoration()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Decoration`
