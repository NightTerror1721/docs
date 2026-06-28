# Class `LevelData`

## Properties

### `mainSection`

```lua
---@type LevelSectionData
LevelData.mainSection
```

- **Type:** `LevelSectionData`
- **Read\-only:** Yes
- **Static:** No

___

### `initialTime`

```lua
---@type integer
LevelData.initialTime
```

- **Type:** `integer`
- **Read\-only:** No
- **Static:** No

___

### `maxTime`

```lua
---@type integer
LevelData.maxTime
```

- **Type:** `integer`
- **Read\-only:** No
- **Static:** No

___

### `lives`

```lua
---@type integer
LevelData.lives
```

- **Type:** `integer`
- **Read\-only:** No
- **Static:** No

___

### `hourglass`

```lua
---@type boolean
LevelData.hourglass
```

- **Type:** `boolean`
- **Read\-only:** No
- **Static:** No

___

### `infiniteLives`

```lua
---@type boolean
LevelData.infiniteLives
```

- **Type:** `boolean`
- **Read\-only:** No
- **Static:** No

___

### `scriptRef`

```lua
---@type string
LevelData.scriptRef
```

- **Type:** `string`
- **Read\-only:** No
- **Static:** No

___

### `scriptTag`

```lua
---@type string
LevelData.scriptTag
```

- **Type:** `string`
- **Read\-only:** No
- **Static:** No

___

### `scriptVars`

```lua
---@type ScriptVariables
LevelData.scriptVars
```

- **Type:** `ScriptVariables`
- **Read\-only:** Yes
- **Static:** No

___

### `messagesCount`

```lua
---@type integer
LevelData.messagesCount
```

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** No

___

### `scriptsCount`

```lua
---@type integer
LevelData.scriptsCount
```

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** No

## Methods

### `createNewSection`

```lua
--- @param sectionId string
--- @return LevelSectionData
function LevelData:createNewSection(sectionId)
```

- **Static:** No
- #### Parameters:
  - **sectionId:** `string`
- **Returns:** `LevelSectionData`

___

### `hasSection`

```lua
--- @param sectionId string
--- @return boolean
function LevelData:hasSection(sectionId)
```

- **Static:** No
- #### Parameters:
  - **sectionId:** `string`
- **Returns:** `boolean`

___

### `getSection`

```lua
--- @param sectionId string
--- @return LevelSectionData
function LevelData:getSection(sectionId)
```

- **Static:** No
- #### Parameters:
  - **sectionId:** `string`
- **Returns:** `LevelSectionData`

___

### `getAdditionalSectionsIterator`

```lua
--- @return LevelSectionData[]
function LevelData:getAdditionalSectionsIterator()
```

- **Static:** No
- **Returns:** `LevelSectionData[]`

___

### `getAllSectionsIterator`

```lua
--- @return LevelSectionData[]
function LevelData:getAllSectionsIterator()
```

- **Static:** No
- **Returns:** `LevelSectionData[]`

___

### `getAdditionalSections`

```lua
--- @return LevelSectionData[]
function LevelData:getAdditionalSections()
```

- **Static:** No
- **Returns:** `LevelSectionData[]`

___

### `getAllSections`

```lua
--- @return LevelSectionData[]
function LevelData:getAllSections()
```

- **Static:** No
- **Returns:** `LevelSectionData[]`

___

### `createNewMessage`

```lua
--- @param message string
--- @return MessageData
function LevelData:createNewMessage(message)
```

- **Static:** No
- #### Parameters:
  - **message:** `string`
- **Returns:** `MessageData`

___

### `hasMessage`

```lua
--- @param name string
--- @return boolean
function LevelData:hasMessage(name)
```

- **Static:** No
- #### Parameters:
  - **name:** `string`
- **Returns:** `boolean`

___

### `getMessage`

```lua
--- @param name string
--- @return MessageData
function LevelData:getMessage(name)
```

- **Static:** No
- #### Parameters:
  - **name:** `string`
- **Returns:** `MessageData`

___

### `getAllMessagesIterator`

```lua
--- @return MessageData[]
function LevelData:getAllMessagesIterator()
```

- **Static:** No
- **Returns:** `MessageData[]`

___

### `getAllMessages`

```lua
--- @return MessageData[]
function LevelData:getAllMessages()
```

- **Static:** No
- **Returns:** `MessageData[]`

___

### `removeMessage`

```lua
--- @param name string
--- @return boolean
function LevelData:removeMessage(name)
```

- **Static:** No
- #### Parameters:
  - **name:** `string`
- **Returns:** `boolean`

___

### `createNewScript`

```lua
--- @param name string
--- @return ScriptData
function LevelData:createNewScript(name)
```

- **Static:** No
- #### Parameters:
  - **name:** `string`
- **Returns:** `ScriptData`

___

### `hasScript`

```lua
--- @param name string
--- @return boolean
function LevelData:hasScript(name)
```

- **Static:** No
- #### Parameters:
  - **name:** `string`
- **Returns:** `boolean`

___

### `getScript`

```lua
--- @param name string
--- @return ScriptData
function LevelData:getScript(name)
```

- **Static:** No
- #### Parameters:
  - **name:** `string`
- **Returns:** `ScriptData`

___

### `getAllScriptsIterator`

```lua
--- @return ScriptData[]
function LevelData:getAllScriptsIterator()
```

- **Static:** No
- **Returns:** `ScriptData[]`

___

### `getAllScripts`

```lua
--- @return ScriptData[]
function LevelData:getAllScripts()
```

- **Static:** No
- **Returns:** `ScriptData[]`

___

### `removeScript`

```lua
--- @param name string
--- @return boolean
function LevelData:removeScript(name)
```

- **Static:** No
- #### Parameters:
  - **name:** `string`
- **Returns:** `boolean`
