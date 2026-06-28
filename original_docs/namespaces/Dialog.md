# Namespace `Dialog`

Provides methods to create and manage dialog messages in the game. Dialog messages can be closeable, temporary, or manual, each with customizable text, duration, and background color.

## Functions

### `createCloseable`

```lua
--- @param message string
--- @param backgroundColor Color
--- @return any
function Dialog.createCloseable(message, backgroundColor)
```

Creates a closeable message with the specified text and background color.

- **Static:** No
- #### Parameters:
  - **message:** `string`
  - **backgroundColor:** `Color`
- **Returns:** `any`

___
```lua
--- @param message string
--- @return any
function Dialog.createCloseable(message)
```

Creates a closeable message with the specified text and a default background color (black).

- **Static:** No
- #### Parameters:
  - **message:** `string`
- **Returns:** `any`

___

### `openCloseable`

```lua
--- @param messageId string
--- @param backgroundColor Color
--- @return any
function Dialog.openCloseable(messageId, backgroundColor)
```

Opens a closeable message with the specified message ID and background color.

- **Static:** No
- #### Parameters:
  - **messageId:** `string`
  - **backgroundColor:** `Color`
- **Returns:** `any`

___
```lua
--- @param messageId string
--- @return any
function Dialog.openCloseable(messageId)
```

Opens a closeable message with the specified message ID and a default background color (black).

- **Static:** No
- #### Parameters:
  - **messageId:** `string`
- **Returns:** `any`

___

### `createTemporary`

```lua
--- @param message string
--- @param duration number
--- @param backgroundColor Color
--- @return any
function Dialog.createTemporary(message, duration, backgroundColor)
```

Creates a temporary message with the specified text, duration, and background color.

- **Static:** No
- #### Parameters:
  - **message:** `string`
  - **duration:** `number`
  - **backgroundColor:** `Color`
- **Returns:** `any`

___
```lua
--- @param message string
--- @param duration number
--- @return any
function Dialog.createTemporary(message, duration)
```

Creates a temporary message with the specified text and duration, using a default background color (black).

- **Static:** No
- #### Parameters:
  - **message:** `string`
  - **duration:** `number`
- **Returns:** `any`

___

### `openTemporary`

```lua
--- @param messageId string
--- @param duration number
--- @param backgroundColor Color
--- @return any
function Dialog.openTemporary(messageId, duration, backgroundColor)
```

Opens a temporary message with the specified message ID, duration, and background color.

- **Static:** No
- #### Parameters:
  - **messageId:** `string`
  - **duration:** `number`
  - **backgroundColor:** `Color`
- **Returns:** `any`

___
```lua
--- @param messageId string
--- @param duration number
--- @return any
function Dialog.openTemporary(messageId, duration)
```

Opens a temporary message with the specified message ID and duration, using a default background color (black).

- **Static:** No
- #### Parameters:
  - **messageId:** `string`
  - **duration:** `number`
- **Returns:** `any`

___

### `createManual`

```lua
--- @param dialogId string
--- @param message string
--- @param backgroundColor Color
--- @return any
function Dialog.createManual(dialogId, message, backgroundColor)
```

Creates a manual message with the specified dialog ID, text, and background color.

- **Static:** No
- #### Parameters:
  - **dialogId:** `string`
  - **message:** `string`
  - **backgroundColor:** `Color`
- **Returns:** `any`

___
```lua
--- @param dialogId string
--- @param message string
--- @return any
function Dialog.createManual(dialogId, message)
```

Creates a manual message with the specified dialog ID and text, using a default background color (black).

- **Static:** No
- #### Parameters:
  - **dialogId:** `string`
  - **message:** `string`
- **Returns:** `any`

___

### `openManual`

```lua
--- @param dialogId string
--- @param messageId string
--- @param backgroundColor Color
--- @return any
function Dialog.openManual(dialogId, messageId, backgroundColor)
```

Opens a manual message with the specified dialog ID, message ID, and background color.

- **Static:** No
- #### Parameters:
  - **dialogId:** `string`
  - **messageId:** `string`
  - **backgroundColor:** `Color`
- **Returns:** `any`

___
```lua
--- @param dialogId string
--- @param messageId string
--- @return any
function Dialog.openManual(dialogId, messageId)
```

Opens a manual message with the specified dialog ID and message ID, using a default background color (black).

- **Static:** No
- #### Parameters:
  - **dialogId:** `string`
  - **messageId:** `string`
- **Returns:** `any`

___

### `existsManual`

```lua
--- @param dialogId string
--- @return boolean
function Dialog.existsManual(dialogId)
```

Checks if a manual message with the specified dialog ID exists.

- **Static:** No
- #### Parameters:
  - **dialogId:** `string`
- **Returns:** `boolean`

___

### `destroyManual`

```lua
--- @param dialogId string
--- @return any
function Dialog.destroyManual(dialogId)
```

Destroys a manual message with the specified dialog ID.

- **Static:** No
- #### Parameters:
  - **dialogId:** `string`
- **Returns:** `any`
