# Class `Timer`

Represents a timer in the game. Provides methods to start, stop, and manipulate timers.

## Properties

### `isRunning`

```lua
---@type boolean
Timer.isRunning
```

Indicates if the timer is currently running.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `isStopped`

```lua
---@type boolean
Timer.isStopped
```

Indicates if the timer is currently stopped.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `maxTime`

```lua
---@type number
Timer.maxTime
```

The maximum time allowed for the timer.

- **Type:** `number`
- **Read\-only:** Yes
- **Static:** No

___

### `remainingTime`

```lua
---@type number
Timer.remainingTime
```

The remaining time on the timer.

- **Type:** `number`
- **Read\-only:** Yes
- **Static:** No

## Methods

### `start`

```lua
--- @param time number
--- @return any
function Timer:start(time)
```

Starts the timer with the specified time.

- **Static:** No
- #### Parameters:
  - **time:** `number`
- **Returns:** `any`

___
```lua
--- @param time number
--- @param onFinish fun(): void
--- @return any
function Timer:start(time, onFinish)
```

Starts the timer with the specified time and a callback function to be called when the timer finishes.

- **Static:** No
- #### Parameters:
  - **time:** `number`
  - **onFinish:** `fun(): void`
- **Returns:** `any`

___
```lua
--- @param time number
--- @param onFinish fun(): void
--- @param onTick fun(): void
--- @return any
function Timer:start(time, onFinish, onTick)
```

Starts the timer with the specified time, a callback function to be called when the timer finishes, and a callback function to be called on each tick.

- **Static:** No
- #### Parameters:
  - **time:** `number`
  - **onFinish:** `fun(): void`
  - **onTick:** `fun(): void`
- **Returns:** `any`

___
```lua
--- @param time number
--- @param onFinish fun(): void
--- @param onTick fun(): void
--- @param initialTime number
--- @return any
function Timer:start(time, onFinish, onTick, initialTime)
```

Starts the timer with the specified time, a callback function to be called when the timer finishes, a callback function to be called on each tick, and an initial time.

- **Static:** No
- #### Parameters:
  - **time:** `number`
  - **onFinish:** `fun(): void`
  - **onTick:** `fun(): void`
  - **initialTime:** `number`
- **Returns:** `any`

___

### `stop`

```lua
--- @return any
function Timer:stop()
```

Stops the timer.

- **Static:** No
- **Returns:** `any`

___
```lua
--- @param callOnFinishCallback boolean
--- @return any
function Timer:stop(callOnFinishCallback)
```

Stops the timer and optionally calls the onFinish callback.

- **Static:** No
- #### Parameters:
  - **callOnFinishCallback:** `boolean`
- **Returns:** `any`

___

### `addTime`

```lua
--- @param time number
--- @return any
function Timer:addTime(time)
```

Adds time to the timer.

- **Static:** No
- #### Parameters:
  - **time:** `number`
- **Returns:** `any`

___
```lua
--- @param time number
--- @param updateMaxTimeIfItIsNeeded boolean
--- @return any
function Timer:addTime(time, updateMaxTimeIfItIsNeeded)
```

Adds time to the timer and optionally updates the maximum time if needed.

- **Static:** No
- #### Parameters:
  - **time:** `number`
  - **updateMaxTimeIfItIsNeeded:** `boolean`
- **Returns:** `any`

___

### `subtractTime`

```lua
--- @param time number
--- @return any
function Timer:subtractTime(time)
```

Subtracts time from the timer.

- **Static:** No
- #### Parameters:
  - **time:** `number`
- **Returns:** `any`
