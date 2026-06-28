# Namespace `Campaign`

## Variables

### `isArcadeMode`

```lua
--- static
---@type boolean
Campaign.isArcadeMode
```

- **Type:** `boolean`
- **Read-only:** Yes
- **Static:** Yes

---

### `isExplorationMode`

```lua
--- static
---@type boolean
Campaign.isExplorationMode
```

- **Type:** `boolean`
- **Read-only:** Yes
- **Static:** Yes

---

### `name`

```lua
--- static
---@type string
Campaign.name
```

- **Type:** `string`
- **Read-only:** Yes
- **Static:** Yes

---

### `requiredFruitsToBonus`

```lua
--- static
---@type integer
Campaign.requiredFruitsToBonus
```

- **Type:** `integer`
- **Read-only:** Yes
- **Static:** Yes

---

### `levelsUntilSaveGame`

```lua
--- static
---@type integer
Campaign.levelsUntilSaveGame
```

- **Type:** `integer`
- **Read-only:** Yes
- **Static:** Yes

---

### `normalLevelsCount`

```lua
--- static
---@type integer
Campaign.normalLevelsCount
```

- **Type:** `integer`
- **Read-only:** Yes
- **Static:** Yes

---

### `firstNormalLevel`

```lua
--- static
---@type CampaignLevel
Campaign.firstNormalLevel
```

- **Type:** `CampaignLevel`
- **Read-only:** Yes
- **Static:** Yes

---

### `episodeCount`

```lua
--- static
---@type integer
Campaign.episodeCount
```

- **Type:** `integer`
- **Read-only:** Yes
- **Static:** Yes

---

### `episodes`

```lua
--- static
---@type CampaignEpisode[]
Campaign.episodes
```

- **Type:** `CampaignEpisode[]`
- **Read-only:** Yes
- **Static:** Yes

---

### `randomBonusMusicCount`

```lua
--- static
---@type integer
Campaign.randomBonusMusicCount
```

- **Type:** `integer`
- **Read-only:** Yes
- **Static:** Yes

---

### `randomBonusMusic`

```lua
--- static
---@type string[]
Campaign.randomBonusMusic
```

- **Type:** `string[]`
- **Read-only:** Yes
- **Static:** Yes

---

### `randomBonusBallsCount`

```lua
--- static
---@type integer
Campaign.randomBonusBallsCount
```

- **Type:** `integer`
- **Read-only:** Yes
- **Static:** Yes

---

### `globalData`

```lua
--- static
---@type LocalData
Campaign.globalData
```

- **Type:** `LocalData`
- **Read-only:** Yes
- **Static:** Yes

---

### `isNormalSaveGameEnabled`

```lua
--- static
---@type boolean
Campaign.isNormalSaveGameEnabled
```

- **Type:** `boolean`
- **Read-only:** Yes
- **Static:** Yes

---

### `isLoopModeEnabled`

```lua
--- static
---@type boolean
Campaign.isLoopModeEnabled
```

- **Type:** `boolean`
- **Read-only:** Yes
- **Static:** Yes

---

### `completionState`

```lua
--- static
---@type CampaignCompletionState
Campaign.completionState
```

- **Type:** `CampaignCompletionState`
- **Read-only:** Yes
- **Static:** Yes

## Functions

### `getNormalLevelByNumber`

```lua
--- @param number integer
--- @return CampaignLevel
function Campaign.getNormalLevelByNumber(number)
```

- **Static:** No
- **Returns:** `CampaignLevel`

---

### `getEpisode`

```lua
--- @param index integer
--- @return CampaignEpisode
function Campaign.getEpisode(index)
```

- **Static:** No
- **Returns:** `CampaignEpisode`

---

```lua
--- @param name string
--- @return CampaignEpisode
function Campaign.getEpisode(name)
```

- **Static:** No
- **Returns:** `CampaignEpisode`

---

### `hasEpisode`

```lua
--- @param name string
--- @return boolean
function Campaign.hasEpisode(name)
```

- **Static:** No
- **Returns:** `boolean`