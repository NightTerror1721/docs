# Class `Log`

Represents a log message with customizable text and colors.

## Properties

### `text`

```lua
---@type string
Log.text
```

The text of the log message.

- **Type:** `string`
- **Read\-only:** No
- **Static:** No

___

### `foregroundColor`

```lua
---@type Color
Log.foregroundColor
```

The color of the log message text. Defaults to white if not set.

- **Type:** `Color`
- **Read\-only:** No
- **Static:** No

___

### `backgroundColor`

```lua
---@type Color
Log.backgroundColor
```

The background color of the log message. Defaults to black if not set.

- **Type:** `Color`
- **Read\-only:** No
- **Static:** No

## Methods

### `append`

```lua
--- @param text string
--- @return Log
function Log:append(text)
```

Appends text to the log message.

- **Static:** No
- #### Parameters:
  - **text:** `string`
- **Returns:** `Log`

___

### `appendLine`

```lua
--- @param text string
--- @return Log
function Log:appendLine(text)
```

Appends text followed by a new line to the log message.

- **Static:** No
- #### Parameters:
  - **text:** `string`
- **Returns:** `Log`

___
```lua
--- @return Log
function Log:appendLine()
```

Appends a new line to the log message.

- **Static:** No
- **Returns:** `Log`

___

### `appendColored`

```lua
--- @param text string
--- @param color Color
--- @return Log
function Log:appendColored(text, color)
```

Appends colored text to the log message.

- **Static:** No
- #### Parameters:
  - **text:** `string`
  - **color:** `Color`
- **Returns:** `Log`

___

### `appendLineColored`

```lua
--- @param text string
--- @param color Color
--- @return Log
function Log:appendLineColored(text, color)
```

Appends colored text followed by a new line to the log message.

- **Static:** No
- #### Parameters:
  - **text:** `string`
  - **color:** `Color`
- **Returns:** `Log`

___

### `clearText`

```lua
--- @return Log
function Log:clearText()
```

Clears the log message text.

- **Static:** No
- **Returns:** `Log`

___

### `clearBackgroundColor`

```lua
--- @return Log
function Log:clearBackgroundColor()
```

Resets the background color to default (black).

- **Static:** No
- **Returns:** `Log`

___

### `clearForegroundColor`

```lua
--- @return Log
function Log:clearForegroundColor()
```

Resets the foreground color to default (white).

- **Static:** No
- **Returns:** `Log`

## Static Methods

### `new`

```lua
--- @param text string
--- @param backgroundColor Color
--- @param foregroundColor Color
--- @return Log
function Log.new(text, backgroundColor, foregroundColor)
```

Creates a new LuaLog instance with the specified text and optional colors.

- **Static:** Yes
- #### Parameters:
  - **text:** `string`
  - **backgroundColor:** `Color`
  - **foregroundColor:** `Color`
- **Returns:** `Log`

___
```lua
--- @param text string
--- @param backgroundColor Color
--- @return Log
function Log.new(text, backgroundColor)
```

Creates a new LuaLog instance with the specified text and optional colors.

- **Static:** Yes
- #### Parameters:
  - **text:** `string`
  - **backgroundColor:** `Color`
- **Returns:** `Log`

___
```lua
--- @param text string
--- @return Log
function Log.new(text)
```

Creates a new LuaLog instance with the specified text and optional colors.

- **Static:** Yes
- #### Parameters:
  - **text:** `string`
- **Returns:** `Log`

___
```lua
--- @return Log
function Log.new()
```

Creates a new LuaLog instance with the specified text and optional colors.

- **Static:** Yes
- **Returns:** `Log`
