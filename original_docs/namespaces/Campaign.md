# Namespace `Campaign`

## Variables

### `isArcadeMode`

```lua
--- static
---@type boolean
Campaign.isArcadeMode
```

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** Yes

___

### `isExplorationMode`

```lua
--- static
---@type boolean
Campaign.isExplorationMode
```

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** Yes

___

### `name`

```lua
--- static
---@type string
Campaign.name
```

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** Yes

___

### `requiredFruitsToBonus`

```lua
--- static
---@type integer
Campaign.requiredFruitsToBonus
```

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** Yes

___

### `levelsUntilSaveGame`

```lua
--- static
---@type integer
Campaign.levelsUntilSaveGame
```

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** Yes

___

### `normalLevelsCount`

```lua
--- static
---@type integer
Campaign.normalLevelsCount
```

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** Yes

___

### `firstNormalLevel`

```lua
--- static
---@type CampaignLevel
Campaign.firstNormalLevel
```

- **Type:** `CampaignLevel`
- **Read\-only:** Yes
- **Static:** Yes

___

### `episodeCount`

```lua
--- static
---@type integer
Campaign.episodeCount
```

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** Yes

___

### `episodes`

```lua
--- static
---@type CampaignEpisode[]
Campaign.episodes
```

- **Type:** `CampaignEpisode[]`
- **Read\-only:** Yes
- **Static:** Yes

___

### `randomBonusMusicCount`

```lua
--- static
---@type integer
Campaign.randomBonusMusicCount
```

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** Yes

___

### `randomBonusMusic`

```lua
--- static
---@type string[]
Campaign.randomBonusMusic
```

- **Type:** `string[]`
- **Read\-only:** Yes
- **Static:** Yes

___

### `randomBonusBallsCount`

```lua
--- static
---@type integer
Campaign.randomBonusBallsCount
```

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** Yes

___

### `globalData`

```lua
--- static
---@type LocalData
Campaign.globalData
```

- **Type:** `LocalData`
- **Read\-only:** Yes
- **Static:** Yes

___

### `isNormalSaveGameEnabled`

```lua
--- static
---@type boolean
Campaign.isNormalSaveGameEnabled
```

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** Yes

___

### `isLoopModeEnabled`

```lua
--- static
---@type boolean
Campaign.isLoopModeEnabled
```

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** Yes

___

### `completionState`

```lua
--- static
---@type CampaignCompletionState
Campaign.completionState
```

- **Type:** `CampaignCompletionState`
- **Read\-only:** Yes
- **Static:** Yes

## Functions

### `getNormalLevelByNumber`

```lua
--- @param number integer
--- @return CampaignLevel
function Campaign.getNormalLevelByNumber(number)
```

- **Static:** No
- #### Parameters:
  - **number:** `integer`
- **Returns:** `CampaignLevel`

___

### `getEpisode`

```lua
--- @param index integer
--- @return CampaignEpisode
function Campaign.getEpisode(index)
```

- **Static:** No
- #### Parameters:
  - **index:** `integer`
- **Returns:** `CampaignEpisode`

___
```lua
--- @param name string
--- @return CampaignEpisode
function Campaign.getEpisode(name)
```

- **Static:** No
- #### Parameters:
  - **name:** `string`
- **Returns:** `CampaignEpisode`

___

### `hasEpisode`

```lua
--- @param name string
--- @return boolean
function Campaign.hasEpisode(name)
```

- **Static:** No
- #### Parameters:
  - **name:** `string`
- **Returns:** `boolean`
