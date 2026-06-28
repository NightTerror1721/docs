# Class `CampaignEpisode`

## Properties

### `campaign`

```lua
---@type Campaign
CampaignEpisode.campaign
```

- **Type:** `Campaign`
- **Read\-only:** Yes
- **Static:** No

___

### `name`

```lua
---@type string
CampaignEpisode.name
```

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** No

___

### `index`

```lua
---@type integer
CampaignEpisode.index
```

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** No

___

### `requiredFruitsToBonus`

```lua
---@type integer
CampaignEpisode.requiredFruitsToBonus
```

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** No

___

### `overrideMusic`

```lua
---@type string
CampaignEpisode.overrideMusic
```

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** No

___

### `overrideTheme`

```lua
---@type string
CampaignEpisode.overrideTheme
```

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** No

___

### `overrideThemeMode`

```lua
---@type ThemeMode?
CampaignEpisode.overrideThemeMode
```

- **Type:** `ThemeMode?`
- **Read\-only:** Yes
- **Static:** No

___

### `selectableBallsCount`

```lua
---@type integer
CampaignEpisode.selectableBallsCount
```

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** No

___

### `unlockedNormalLevels`

```lua
---@type integer
CampaignEpisode.unlockedNormalLevels
```

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** No

___

### `normalLevelsCount`

```lua
---@type integer
CampaignEpisode.normalLevelsCount
```

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** No

___

### `bonusLevelsCount`

```lua
---@type integer
CampaignEpisode.bonusLevelsCount
```

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** No

___

### `secretLevelsCount`

```lua
---@type integer
CampaignEpisode.secretLevelsCount
```

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** No

___

### `normalLevels`

```lua
---@type CampaignLevel[]
CampaignEpisode.normalLevels
```

- **Type:** `CampaignLevel[]`
- **Read\-only:** Yes
- **Static:** No

___

### `bonusLevels`

```lua
---@type CampaignLevel[]
CampaignEpisode.bonusLevels
```

- **Type:** `CampaignLevel[]`
- **Read\-only:** Yes
- **Static:** No

___

### `secretLevels`

```lua
---@type CampaignLevel[]
CampaignEpisode.secretLevels
```

- **Type:** `CampaignLevel[]`
- **Read\-only:** Yes
- **Static:** No

___

### `isUnlocked`

```lua
---@type boolean
CampaignEpisode.isUnlocked
```

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `isLocked`

```lua
---@type boolean
CampaignEpisode.isLocked
```

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

## Methods

### `getNormalLevel`

```lua
--- @param index integer
--- @return CampaignLevel
function CampaignEpisode:getNormalLevel(index)
```

- **Static:** No
- #### Parameters:
  - **index:** `integer`
- **Returns:** `CampaignLevel`

___

### `getBonusLevel`

```lua
--- @param index integer
--- @return CampaignLevel
function CampaignEpisode:getBonusLevel(index)
```

- **Static:** No
- #### Parameters:
  - **index:** `integer`
- **Returns:** `CampaignLevel`

___

### `getSecretLevel`

```lua
--- @param name string
--- @return CampaignLevel
function CampaignEpisode:getSecretLevel(name)
```

- **Static:** No
- #### Parameters:
  - **name:** `string`
- **Returns:** `CampaignLevel`

___

### `hasSecretLevel`

```lua
--- @param name string
--- @return boolean
function CampaignEpisode:hasSecretLevel(name)
```

- **Static:** No
- #### Parameters:
  - **name:** `string`
- **Returns:** `boolean`

___

### `getBonusLevelByNormalLevelIndex`

```lua
--- @param normalLevelIndex integer
--- @return CampaignLevel
function CampaignEpisode:getBonusLevelByNormalLevelIndex(normalLevelIndex)
```

- **Static:** No
- #### Parameters:
  - **normalLevelIndex:** `integer`
- **Returns:** `CampaignLevel`
