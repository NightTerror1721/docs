# Class `EnemyData`

## Properties

### `interactions`

```lua
---@type EnemyInteraction[]
EnemyData.interactions
```

- **Type:** `EnemyInteraction[]`
- **Read\-only:** Yes
- **Static:** No

___

### `initialPosition`

```lua
---@type BlockLocation
EnemyData.initialPosition
```

- **Type:** `BlockLocation`
- **Read\-only:** Yes
- **Static:** No

___

### `template`

```lua
---@type string
EnemyData.template
```

- **Type:** `string`
- **Read\-only:** No
- **Static:** No

___

### `scriptRef`

```lua
---@type string
EnemyData.scriptRef
```

- **Type:** `string`
- **Read\-only:** No
- **Static:** No

___

### `scriptTag`

```lua
---@type string
EnemyData.scriptTag
```

- **Type:** `string`
- **Read\-only:** No
- **Static:** No

___

### `scriptVars`

```lua
---@type ScriptVariables
EnemyData.scriptVars
```

- **Type:** `ScriptVariables`
- **Read\-only:** Yes
- **Static:** No

___

### `properties`

```lua
---@type ElementPropertiesData
EnemyData.properties
```

- **Type:** `ElementPropertiesData`
- **Read\-only:** Yes
- **Static:** No

## Methods

### `enableInteraction`

```lua
--- @param interaction EnemyInteraction
--- @return any
function EnemyData:enableInteraction(interaction)
```

- **Static:** No
- #### Parameters:
  - **interaction:** `EnemyInteraction`
- **Returns:** `any`

___

### `disableInteraction`

```lua
--- @param interaction EnemyInteraction
--- @return any
function EnemyData:disableInteraction(interaction)
```

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
function EnemyData:setInteractionEnabled(interaction, enabled)
```

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
function EnemyData:isInteractionEnabled(interaction)
```

- **Static:** No
- #### Parameters:
  - **interaction:** `EnemyInteraction`
- **Returns:** `boolean`

___

### `clear`

```lua
--- @return any
function EnemyData:clear()
```

- **Static:** No
- **Returns:** `any`
