# Class `CampaignCompletionState`

## Methods

### `getEpisodeState`

```lua
--- @param episode CampaignEpisode
--- @return EpisodeCompletionState
function CampaignCompletionState:getEpisodeState(episode)
```

- **Static:** No
- #### Parameters:
  - **episode:** `CampaignEpisode`
- **Returns:** `EpisodeCompletionState`

___

### `getLevelState`

```lua
--- @param level CampaignLevel
--- @return LevelCompletionState
function CampaignCompletionState:getLevelState(level)
```

- **Static:** No
- #### Parameters:
  - **level:** `CampaignLevel`
- **Returns:** `LevelCompletionState`

___

### `isLevelCompleted`

```lua
--- @param level CampaignLevel
--- @return boolean
function CampaignCompletionState:isLevelCompleted(level)
```

- **Static:** No
- #### Parameters:
  - **level:** `CampaignLevel`
- **Returns:** `boolean`

___

### `hasAllFruitsCollected`

```lua
--- @param campaign Campaign
--- @return boolean
function CampaignCompletionState:hasAllFruitsCollected(campaign)
```

- **Static:** No
- #### Parameters:
  - **campaign:** `Campaign`
- **Returns:** `boolean`

___

### `updateLevelState`

```lua
--- @param level CampaignLevel
--- @param isDiscovered boolean?
--- @param isCompleted boolean?
--- @param isTreasureCollected boolean?
--- @param isFruitCollected boolean?
--- @param isCompletedWithinHourglassTime boolean?
--- @param bestScoreLevel integer?
--- @param bestLevelTime number?
--- @return any
function CampaignCompletionState:updateLevelState(level, isDiscovered, isCompleted, isTreasureCollected, isFruitCollected, isCompletedWithinHourglassTime, bestScoreLevel, bestLevelTime)
```

- **Static:** No
- #### Parameters:
  - **level:** `CampaignLevel`
  - **isDiscovered:** `boolean?`
  - **isCompleted:** `boolean?`
  - **isTreasureCollected:** `boolean?`
  - **isFruitCollected:** `boolean?`
  - **isCompletedWithinHourglassTime:** `boolean?`
  - **bestScoreLevel:** `integer?`
  - **bestLevelTime:** `number?`
- **Returns:** `any`

___

### `createUpdateLevelRequest`

```lua
--- @param level CampaignLevel
--- @return UpdateLevelRequest
function CampaignCompletionState:createUpdateLevelRequest(level)
```

- **Static:** No
- #### Parameters:
  - **level:** `CampaignLevel`
- **Returns:** `UpdateLevelRequest`

___

### `applyUpdateLevelRequest`

```lua
--- @param request UpdateLevelRequest
--- @return any
function CampaignCompletionState:applyUpdateLevelRequest(request)
```

- **Static:** No
- #### Parameters:
  - **request:** `UpdateLevelRequest`
- **Returns:** `any`

___

### `setLevelIsCompleted`

```lua
--- @param level CampaignLevel
--- @param isCompleted boolean
--- @return any
function CampaignCompletionState:setLevelIsCompleted(level, isCompleted)
```

- **Static:** No
- #### Parameters:
  - **level:** `CampaignLevel`
  - **isCompleted:** `boolean`
- **Returns:** `any`

___

### `setLevelIsDiscovered`

```lua
--- @param level CampaignLevel
--- @param isDiscovered boolean
--- @return any
function CampaignCompletionState:setLevelIsDiscovered(level, isDiscovered)
```

- **Static:** No
- #### Parameters:
  - **level:** `CampaignLevel`
  - **isDiscovered:** `boolean`
- **Returns:** `any`

___

### `setLevelIsTreasureCollected`

```lua
--- @param level CampaignLevel
--- @param isTreasureCollected boolean
--- @return any
function CampaignCompletionState:setLevelIsTreasureCollected(level, isTreasureCollected)
```

- **Static:** No
- #### Parameters:
  - **level:** `CampaignLevel`
  - **isTreasureCollected:** `boolean`
- **Returns:** `any`

___

### `setLevelIsFruitCollected`

```lua
--- @param level CampaignLevel
--- @param isFruitCollected boolean
--- @return any
function CampaignCompletionState:setLevelIsFruitCollected(level, isFruitCollected)
```

- **Static:** No
- #### Parameters:
  - **level:** `CampaignLevel`
  - **isFruitCollected:** `boolean`
- **Returns:** `any`

___

### `setLevelIsCompletedWithinHourglassTime`

```lua
--- @param level CampaignLevel
--- @param isCompletedWithinHourglassTime boolean
--- @return any
function CampaignCompletionState:setLevelIsCompletedWithinHourglassTime(level, isCompletedWithinHourglassTime)
```

- **Static:** No
- #### Parameters:
  - **level:** `CampaignLevel`
  - **isCompletedWithinHourglassTime:** `boolean`
- **Returns:** `any`

___

### `setLevelBestScoreLevel`

```lua
--- @param level CampaignLevel
--- @param bestScoreLevel integer
--- @return any
function CampaignCompletionState:setLevelBestScoreLevel(level, bestScoreLevel)
```

- **Static:** No
- #### Parameters:
  - **level:** `CampaignLevel`
  - **bestScoreLevel:** `integer`
- **Returns:** `any`

___

### `setLevelBestLevelTime`

```lua
--- @param level CampaignLevel
--- @param bestLevelTime number
--- @return any
function CampaignCompletionState:setLevelBestLevelTime(level, bestLevelTime)
```

- **Static:** No
- #### Parameters:
  - **level:** `CampaignLevel`
  - **bestLevelTime:** `number`
- **Returns:** `any`
