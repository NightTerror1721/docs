# Class `FlybyEvent`

Represents a flyby event in the game. Provides methods to create different types of flyby events.

## Properties

### `type`

```lua
---@type integer
FlybyEvent.type
```

Gets the type of the flyby event.

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** No

___

### `isFinished`

```lua
---@type boolean
FlybyEvent.isFinished
```

Checks if the flyby event is finished.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

## Methods

### `toFlybyEvent`

```lua
--- @return FlybyEvent
function FlybyEvent:toFlybyEvent()
```

Converts the LuaFlybyEvent to a FlybyEvent.

- **Static:** No
- **Returns:** `FlybyEvent`

## Static Methods

### `rawMoveTo`

```lua
--- @param position Vector3
--- @param rotation Quaternion
--- @param look CameraLookPosition
--- @param duration number
--- @return FlybyEvent
function FlybyEvent.rawMoveTo(position, rotation, look, duration)
```

Creates a raw move\-to flyby event.

- **Static:** Yes
- #### Parameters:
  - **position:** `Vector3`
  - **rotation:** `Quaternion`
  - **look:** `CameraLookPosition`
  - **duration:** `number`
- **Returns:** `FlybyEvent`

___

### `moveTo`

```lua
--- @param slot BlockSlot
--- @param face Face
--- @param orientation Orientation
--- @param look CameraLookPosition
--- @param duration number
--- @return FlybyEvent
function FlybyEvent.moveTo(slot, face, orientation, look, duration)
```

Creates a move\-to flyby event to a specific block slot.

- **Static:** Yes
- #### Parameters:
  - **slot:** `BlockSlot`
  - **face:** `Face`
  - **orientation:** `Orientation`
  - **look:** `CameraLookPosition`
  - **duration:** `number`
- **Returns:** `FlybyEvent`

___
```lua
--- @param x integer
--- @param y integer
--- @param z integer
--- @param face Face
--- @param orientation Orientation
--- @param look CameraLookPosition
--- @param duration number
--- @return FlybyEvent
function FlybyEvent.moveTo(x, y, z, face, orientation, look, duration)
```

Creates a move\-to flyby event to specific coordinates.

- **Static:** Yes
- #### Parameters:
  - **x:** `integer`
  - **y:** `integer`
  - **z:** `integer`
  - **face:** `Face`
  - **orientation:** `Orientation`
  - **look:** `CameraLookPosition`
  - **duration:** `number`
- **Returns:** `FlybyEvent`

___

### `moveToBall`

```lua
--- @param look CameraLookPosition
--- @param duration number
--- @return FlybyEvent
function FlybyEvent.moveToBall(look, duration)
```

Creates a move\-to\-ball flyby event.

- **Static:** Yes
- #### Parameters:
  - **look:** `CameraLookPosition`
  - **duration:** `number`
- **Returns:** `FlybyEvent`

___

### `wait`

```lua
--- @param duration number
--- @return FlybyEvent
function FlybyEvent.wait(duration)
```

Creates a wait flyby event for a specified duration.

- **Static:** Yes
- #### Parameters:
  - **duration:** `number`
- **Returns:** `FlybyEvent`

___

### `message`

```lua
--- @param message string
--- @param backgroundColor Color
--- @return FlybyEvent
function FlybyEvent.message(message, backgroundColor)
```

Creates a message flyby event with a specified message and background color.

- **Static:** Yes
- #### Parameters:
  - **message:** `string`
  - **backgroundColor:** `Color`
- **Returns:** `FlybyEvent`

___
```lua
--- @param message string
--- @return FlybyEvent
function FlybyEvent.message(message)
```

Creates a message flyby event with a specified message.

- **Static:** Yes
- #### Parameters:
  - **message:** `string`
- **Returns:** `FlybyEvent`

___

### `script`

```lua
--- @param closure function
--- @return FlybyEvent
function FlybyEvent.script(closure)
```

Creates a script flyby event with a specified Lua closure.

- **Static:** Yes
- #### Parameters:
  - **closure:** `function`
- **Returns:** `FlybyEvent`
