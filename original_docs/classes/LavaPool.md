# Class `LavaPool`

Represents a pool of lava in the level environment.

## Properties

### `isActive`

```lua
---@type boolean
LavaPool.isActive
```

Indicates whether the lava pool is currently active.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `mode`

```lua
---@type PoolMode
LavaPool.mode
```

Gets or sets the mode of the lava pool.

- **Type:** `PoolMode`
- **Read\-only:** No
- **Static:** No

___

### `velocity`

```lua
---@type number
LavaPool.velocity
```

Gets or sets the velocity of the lava pool (only for AutoAdjust mode).

- **Type:** `number`
- **Read\-only:** No
- **Static:** No

___

### `maxVelocity`

```lua
---@type number
LavaPool.maxVelocity
```

Gets or sets the maximum velocity of the lava pool (only for AutoAdjust mode).

- **Type:** `number`
- **Read\-only:** No
- **Static:** No

___

### `acceleration`

```lua
---@type number
LavaPool.acceleration
```

Gets or sets the acceleration of the lava pool (only for AutoAdjust mode).

- **Type:** `number`
- **Read\-only:** No
- **Static:** No

___

### `amplitude`

```lua
---@type number
LavaPool.amplitude
```

Gets or sets the amplitude of the lava pool's wave effect (only for Tide mode).

- **Type:** `number`
- **Read\-only:** No
- **Static:** No

___

### `frequency`

```lua
---@type number
LavaPool.frequency
```

Gets or sets the frequency of the lava pool's wave effect (only for Tide mode).

- **Type:** `number`
- **Read\-only:** No
- **Static:** No

___

### `targetHeight`

```lua
---@type number
LavaPool.targetHeight
```

Gets or sets the target height of the lava pool (only for AutoAdjust or Tide mode).

- **Type:** `number`
- **Read\-only:** No
- **Static:** No

___

### `currentHeight`

```lua
---@type number
LavaPool.currentHeight
```

Gets or sets the current height of the lava pool.

- **Type:** `number`
- **Read\-only:** No
- **Static:** No
