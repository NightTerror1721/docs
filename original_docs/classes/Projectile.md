# Class `Projectile`

Represents a projectile in the game. Provides access to its properties and behaviors.

## Properties

### `skin`

```lua
---@type string
Projectile.skin
```

Gets the skin ID of the projectile.

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** No

___

### `isActive`

```lua
---@type boolean
Projectile.isActive
```

Indicates whether the projectile is currently active.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `section`

```lua
---@type string
Projectile.section
```

Gets the section ID of the projectile's pool.

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** No

___

### `lifetime`

```lua
---@type number
Projectile.lifetime
```

Gets or sets the lifetime of the projectile.

- **Type:** `number`
- **Read\-only:** No
- **Static:** No

___

### `speed`

```lua
---@type number
Projectile.speed
```

Gets or sets the speed of the projectile.

- **Type:** `number`
- **Read\-only:** No
- **Static:** No

___

### `acceleration`

```lua
---@type number
Projectile.acceleration
```

Gets or sets the acceleration of the projectile.

- **Type:** `number`
- **Read\-only:** No
- **Static:** No

___

### `angularSpeed`

```lua
---@type number
Projectile.angularSpeed
```

Gets or sets the angular speed of the projectile.

- **Type:** `number`
- **Read\-only:** No
- **Static:** No

___

### `angularAcceleration`

```lua
---@type number
Projectile.angularAcceleration
```

Gets or sets the angular acceleration of the projectile.

- **Type:** `number`
- **Read\-only:** No
- **Static:** No

___

### `angularLocalAxisRotation`

```lua
---@type Vector3
Projectile.angularLocalAxisRotation
```

Gets or sets the angular local axis rotation of the projectile.

- **Type:** `Vector3`
- **Read\-only:** No
- **Static:** No

___

### `homingStrength`

```lua
---@type number
Projectile.homingStrength
```

Gets or sets the homing strength of the projectile.

- **Type:** `number`
- **Read\-only:** No
- **Static:** No

___

### `maxHomingRange`

```lua
---@type number
Projectile.maxHomingRange
```

Gets or sets the maximum homing range of the projectile.

- **Type:** `number`
- **Read\-only:** No
- **Static:** No

___

### `isHoming`

```lua
---@type boolean
Projectile.isHoming
```

Indicates whether the projectile is homing.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `position`

```lua
---@type Vector3
Projectile.position
```

Gets or sets the position of the projectile.

- **Type:** `Vector3`
- **Read\-only:** No
- **Static:** No

___

### `rotation`

```lua
---@type Quaternion
Projectile.rotation
```

Gets or sets the rotation of the projectile.

- **Type:** `Quaternion`
- **Read\-only:** No
- **Static:** No

___

### `forward`

```lua
---@type Vector3
Projectile.forward
```

Gets the forward direction of the projectile.

- **Type:** `Vector3`
- **Read\-only:** Yes
- **Static:** No

___

### `velocity`

```lua
---@type Vector3
Projectile.velocity
```

Gets the velocity of the projectile.

- **Type:** `Vector3`
- **Read\-only:** Yes
- **Static:** No

___

### `angularVelocity`

```lua
---@type number
Projectile.angularVelocity
```

Gets the angular velocity of the projectile.

- **Type:** `number`
- **Read\-only:** Yes
- **Static:** No

___

### `explodeOnCollideWithBlocks`

```lua
---@type boolean
Projectile.explodeOnCollideWithBlocks
```

Gets or sets whether the projectile explodes on collision with blocks.

- **Type:** `boolean`
- **Read\-only:** No
- **Static:** No

___

### `explodeOnCollideWithItems`

```lua
---@type boolean
Projectile.explodeOnCollideWithItems
```

Gets or sets whether the projectile explodes on collision with items.

- **Type:** `boolean`
- **Read\-only:** No
- **Static:** No

___

### `explodeOnCollideWithEnemies`

```lua
---@type boolean
Projectile.explodeOnCollideWithEnemies
```

Gets or sets whether the projectile explodes on collision with enemies.

- **Type:** `boolean`
- **Read\-only:** No
- **Static:** No

___

### `explodeOnCollideWithBalls`

```lua
---@type boolean
Projectile.explodeOnCollideWithBalls
```

Gets or sets whether the projectile explodes on collision with balls.

- **Type:** `boolean`
- **Read\-only:** No
- **Static:** No

___

### `explodeOnCollideWithDecorations`

```lua
---@type boolean
Projectile.explodeOnCollideWithDecorations
```

Gets or sets whether the projectile explodes on collision with decorations.

- **Type:** `boolean`
- **Read\-only:** No
- **Static:** No

## Methods

### `fire`

```lua
--- @return any
function Projectile:fire()
```

Fires the projectile.

- **Static:** No
- **Returns:** `any`

___
```lua
--- @param initialSpeed number
--- @return any
function Projectile:fire(initialSpeed)
```

Fires the projectile with an initial speed.

- **Static:** No
- #### Parameters:
  - **initialSpeed:** `number`
- **Returns:** `any`

___
```lua
--- @param position Vector3
--- @return any
function Projectile:fire(position)
```

Fires the projectile from a specific position.

- **Static:** No
- #### Parameters:
  - **position:** `Vector3`
- **Returns:** `any`

___
```lua
--- @param rotation Quaternion
--- @return any
function Projectile:fire(rotation)
```

Fires the projectile with a specific rotation.

- **Static:** No
- #### Parameters:
  - **rotation:** `Quaternion`
- **Returns:** `any`

___
```lua
--- @param position Vector3
--- @param rotation Quaternion
--- @return any
function Projectile:fire(position, rotation)
```

Fires the projectile from a specific position with a specific rotation.

- **Static:** No
- #### Parameters:
  - **position:** `Vector3`
  - **rotation:** `Quaternion`
- **Returns:** `any`

___
```lua
--- @param position Vector3
--- @param rotation Quaternion
--- @param initialSpeed number
--- @return any
function Projectile:fire(position, rotation, initialSpeed)
```

Fires the projectile from a specific position with a specific rotation and initial speed.

- **Static:** No
- #### Parameters:
  - **position:** `Vector3`
  - **rotation:** `Quaternion`
  - **initialSpeed:** `number`
- **Returns:** `any`

___

### `explode`

```lua
--- @return any
function Projectile:explode()
```

Explodes the projectile.

- **Static:** No
- **Returns:** `any`

___
```lua
--- @param rotation Quaternion
--- @return any
function Projectile:explode(rotation)
```

Explodes the projectile with a specific rotation.

- **Static:** No
- #### Parameters:
  - **rotation:** `Quaternion`
- **Returns:** `any`

___

### `setOnFireEvent`

```lua
--- @param event function
--- @return any
function Projectile:setOnFireEvent(event)
```

Sets the event that is called when the projectile is fired.

- **Static:** No
- #### Parameters:
  - **event:** `function`
- **Returns:** `any`

___

### `setOnExplodeEvent`

```lua
--- @param event function
--- @return any
function Projectile:setOnExplodeEvent(event)
```

Sets the event that is called when the projectile explodes.

- **Static:** No
- #### Parameters:
  - **event:** `function`
- **Returns:** `any`

___

### `setOnUpdateEvent`

```lua
--- @param event function
--- @return any
function Projectile:setOnUpdateEvent(event)
```

Sets the event that is called when the projectile is updated.

- **Static:** No
- #### Parameters:
  - **event:** `function`
- **Returns:** `any`
