# Namespace `Logger`

Provides methods to log messages to the in\-game logs console with customizable text and colors.

## Variables

### `isEnabled`

```lua
--- static
---@type boolean
Logger.isEnabled
```

Indicates whether the logger is enabled. The logger is enabled only in editor mode.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** Yes

## Functions

### `log`

```lua
--- @param log Log
--- @return any
function Logger.log(log)
```

Logs a message to the in\-game logs console with optional colors.

- **Static:** No
- #### Parameters:
  - **log:** `Log`
- **Returns:** `any`

___
```lua
--- @param message string
--- @param backgroundColor Color
--- @param foregroundColor Color
--- @return any
function Logger.log(message, backgroundColor, foregroundColor)
```

Logs a message to the in\-game logs console with optional colors.

- **Static:** No
- #### Parameters:
  - **message:** `string`
  - **backgroundColor:** `Color`
  - **foregroundColor:** `Color`
- **Returns:** `any`

___
```lua
--- @param message string
--- @param backgroundColor Color
--- @return any
function Logger.log(message, backgroundColor)
```

Logs a message to the in\-game logs console with optional colors.

- **Static:** No
- #### Parameters:
  - **message:** `string`
  - **backgroundColor:** `Color`
- **Returns:** `any`

___
```lua
--- @param message string
--- @return any
function Logger.log(message)
```

Logs a message to the in\-game logs console with optional colors.

- **Static:** No
- #### Parameters:
  - **message:** `string`
- **Returns:** `any`

___

### `info`

```lua
--- @param log Log
--- @return any
function Logger.info(log)
```

Logs an informational message to the in\-game logs console.

- **Static:** No
- #### Parameters:
  - **log:** `Log`
- **Returns:** `any`

___
```lua
--- @param message string
--- @return any
function Logger.info(message)
```

Logs an informational message to the in\-game logs console.

- **Static:** No
- #### Parameters:
  - **message:** `string`
- **Returns:** `any`

___

### `warning`

```lua
--- @param log Log
--- @return any
function Logger.warning(log)
```

Logs a warning message to the in\-game logs console with a yellow background.

- **Static:** No
- #### Parameters:
  - **log:** `Log`
- **Returns:** `any`

___
```lua
--- @param message string
--- @return any
function Logger.warning(message)
```

Logs a warning message to the in\-game logs console with a yellow background.

- **Static:** No
- #### Parameters:
  - **message:** `string`
- **Returns:** `any`

___

### `error`

```lua
--- @param log Log
--- @return any
function Logger.error(log)
```

Logs an error message to the in\-game logs console with a red background.

- **Static:** No
- #### Parameters:
  - **log:** `Log`
- **Returns:** `any`

___
```lua
--- @param message string
--- @return any
function Logger.error(message)
```

Logs an error message to the in\-game logs console with a red background.

- **Static:** No
- #### Parameters:
  - **message:** `string`
- **Returns:** `any`
