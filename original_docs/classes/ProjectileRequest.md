# Class `ProjectileRequest`

Represents a request to create or configure a projectile. This class allows you to specify various properties of the projectile, such as its origin, rotation, speed, and behavior upon collision.

## Properties

### `skin`

```lua
---@type string
ProjectileRequest.skin
```

Gets or sets the skin ID of the projectile.

- **Type:** `string`
- **Read\-only:** No
- **Static:** No

___

### `origin`

```lua
---@type Vector3
ProjectileRequest.origin
```

Gets or sets the origin of the projectile.

- **Type:** `Vector3`
- **Read\-only:** No
- **Static:** No

___

### `rotation`

```lua
---@type Quaternion
ProjectileRequest.rotation
```

Gets or sets the rotation of the projectile.

- **Type:** `Quaternion`
- **Read\-only:** No
- **Static:** No

___

### `tag`

```lua
---@type string
ProjectileRequest.tag
```

Gets or sets the tag of the projectile.

- **Type:** `string`
- **Read\-only:** No
- **Static:** No

___

### `power`

```lua
---@type integer
ProjectileRequest.power
```

Gets or sets the power of the projectile.

- **Type:** `integer`
- **Read\-only:** No
- **Static:** No

___

### `lifetime`

```lua
---@type number
ProjectileRequest.lifetime
```

Gets or sets the lifetime of the projectile.

- **Type:** `number`
- **Read\-only:** No
- **Static:** No

___

### `speed`

```lua
---@type number
ProjectileRequest.speed
```

Gets or sets the speed of the projectile.

- **Type:** `number`
- **Read\-only:** No
- **Static:** No

___

### `acceleration`

```lua
---@type number
ProjectileRequest.acceleration
```

Gets or sets the acceleration of the projectile.

- **Type:** `number`
- **Read\-only:** No
- **Static:** No

___

### `homingStrength`

```lua
---@type number
ProjectileRequest.homingStrength
```

Gets or sets the homing strength of the projectile.

- **Type:** `number`
- **Read\-only:** No
- **Static:** No

___

### `maxHomingRange`

```lua
---@type number
ProjectileRequest.maxHomingRange
```

Gets or sets the maximum homing range of the projectile.

- **Type:** `number`
- **Read\-only:** No
- **Static:** No

___

### `autoFire`

```lua
---@type boolean
ProjectileRequest.autoFire
```

Gets or sets whether the projectile should automatically fire.

- **Type:** `boolean`
- **Read\-only:** No
- **Static:** No

___

### `explodeOnCollideWithBlocks`

```lua
---@type boolean
ProjectileRequest.explodeOnCollideWithBlocks
```

Gets or sets whether the projectile should explode on collision with blocks.

- **Type:** `boolean`
- **Read\-only:** No
- **Static:** No

___

### `explodeOnCollideWithItems`

```lua
---@type boolean
ProjectileRequest.explodeOnCollideWithItems
```

Gets or sets whether the projectile should explode on collision with items.

- **Type:** `boolean`
- **Read\-only:** No
- **Static:** No

___

### `explodeOnCollideWithEnemies`

```lua
---@type boolean
ProjectileRequest.explodeOnCollideWithEnemies
```

Gets or sets whether the projectile should explode on collision with enemies.

- **Type:** `boolean`
- **Read\-only:** No
- **Static:** No

___

### `explodeOnCollideWithBalls`

```lua
---@type boolean
ProjectileRequest.explodeOnCollideWithBalls
```

Gets or sets whether the projectile should explode on collision with balls.

- **Type:** `boolean`
- **Read\-only:** No
- **Static:** No

___

### `explodeOnCollideWithDecorations`

```lua
---@type boolean
ProjectileRequest.explodeOnCollideWithDecorations
```

Gets or sets whether the projectile should explode on collision with decorations.

- **Type:** `boolean`
- **Read\-only:** No
- **Static:** No

___

### `explodeOnCollideWithProjectiles`

```lua
---@type boolean
ProjectileRequest.explodeOnCollideWithProjectiles
```

Gets or sets whether the projectile should explode on collision with projectiles.

- **Type:** `boolean`
- **Read\-only:** No
- **Static:** No

___

### `onFire`

```lua
---@type fun(projectile: LuaProjectile): void
ProjectileRequest.onFire
```

Gets or sets the callback function to be invoked when the projectile is fired.

- **Type:** `fun(projectile: LuaProjectile): void`
- **Read\-only:** No
- **Static:** No

___

### `onExplode`

```lua
---@type fun(projectile: LuaProjectile): void
ProjectileRequest.onExplode
```

Gets or sets the callback function to be invoked when the projectile explodes.

- **Type:** `fun(projectile: LuaProjectile): void`
- **Read\-only:** No
- **Static:** No

___

### `onUpdate`

```lua
---@type fun(projectile: LuaProjectile, deltaTime: number): void
ProjectileRequest.onUpdate
```

Gets or sets the callback function to be invoked when the projectile is updated.

- **Type:** `fun(projectile: LuaProjectile, deltaTime: number): void`
- **Read\-only:** No
- **Static:** No

## Static Methods

### `new`

```lua
--- @param skin string
--- @param origin Vector3
--- @param rotation Quaternion
--- @return ProjectileRequest
function ProjectileRequest.new(skin, origin, rotation)
```

Creates a new instance of LuaProjectileRequest with the specified skin, origin, and rotation.

- **Static:** Yes
- #### Parameters:
  - **skin:** `string`
  - **origin:** `Vector3`
  - **rotation:** `Quaternion`
- **Returns:** `ProjectileRequest`

___
```lua
--- @param skin string
--- @return ProjectileRequest
function ProjectileRequest.new(skin)
```

Creates a new instance of LuaProjectileRequest with the specified skin.

- **Static:** Yes
- #### Parameters:
  - **skin:** `string`
- **Returns:** `ProjectileRequest`

___
```lua
--- @return ProjectileRequest
function ProjectileRequest.new()
```

Creates a new instance of LuaProjectileRequest with default values.

- **Static:** Yes
- **Returns:** `ProjectileRequest`
