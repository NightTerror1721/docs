# Class `MessageData`

## Properties

### `name`

```lua
---@type string
MessageData.name
```

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** No

## Methods

### `setText`

```lua
--- @param language string
--- @param text string
--- @return any
function MessageData:setText(language, text)
```

- **Static:** No
- #### Parameters:
  - **language:** `string`
  - **text:** `string`
- **Returns:** `any`

___

### `getText`

```lua
--- @param language string
--- @return string
function MessageData:getText(language)
```

- **Static:** No
- #### Parameters:
  - **language:** `string`
- **Returns:** `string`

___

### `removeText`

```lua
--- @param language string
--- @return any
function MessageData:removeText(language)
```

- **Static:** No
- #### Parameters:
  - **language:** `string`
- **Returns:** `any`

___

### `getAvailableLanguages`

```lua
--- @return string[]
function MessageData:getAvailableLanguages()
```

- **Static:** No
- **Returns:** `string[]`

___

### `clear`

```lua
--- @return any
function MessageData:clear()
```

- **Static:** No
- **Returns:** `any`
