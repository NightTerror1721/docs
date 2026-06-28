# Hooks

A hook is a global function defined in your script that the game automatically calls when a specific event occurs. Each hook’s name corresponds to an event exposed by the game (for example, when a player enters an area, defeats an enemy, or starts a quest). By writing code inside the hook, you can customize how the game responds to that event — such as triggering messages, modifying player stats, or launching new gameplay actions.  
In short, hooks let you “plug into” the game’s event system and extend its behavior without modifying the game’s core code.

## `Balls` Hooks

Hooks related to ball events, such as spawning, updating, rolling, colliding with projectiles, exiting the level, dying, and being destroyed.

### OnSpawn

```lua
---@param self Ball
function OnSpawn(self)
```

- #### Parameters:
  - **self:** `Ball`

### OnUpdate

```lua
---@param self Ball
---@param deltaTime number
function OnUpdate(self, deltaTime)
```

- #### Parameters:
  - **self:** `Ball`
  - **deltaTime:** `number`

### OnBallRoll

```lua
---@param self Ball
---@param rollIn boolean
---@param side Side
function OnBallRoll(self, rollIn, side)
```

- #### Parameters:
  - **self:** `Ball`
  - **rollIn:** `boolean`
  - **side:** `Side`

### OnProjectileCollide

```lua
---@param self Ball
---@param projectile Projectile
function OnProjectileCollide(self, projectile)
```

- #### Parameters:
  - **self:** `Ball`
  - **projectile:** `Projectile`

### OnExit

```lua
---@param self Ball
function OnExit(self)
```

- #### Parameters:
  - **self:** `Ball`

### OnDeath

```lua
---@param self Ball
function OnDeath(self)
```

- #### Parameters:
  - **self:** `Ball`

### OnSignal

```lua
---@param self Ball
---@param signal Signal
function OnSignal(self, signal)
```

- #### Parameters:
  - **self:** `Ball`
  - **signal:** `Signal`

### OnDestroy

```lua
---@param self Ball
function OnDestroy(self)
```

- #### Parameters:
  - **self:** `Ball`

## `Blocks` Hooks

Hooks related to block events, such as spawning, updating, ball rolling, colliding with projectiles, being destroyed, and custom events.

### SpawnCondition

```lua
---@param self Block
---@return boolean
function SpawnCondition(self)
```

- #### Parameters:
  - **self:** `Block`
- #### Returns:

  `boolean`

### OnSpawn

```lua
---@param self Block
function OnSpawn(self)
```

- #### Parameters:
  - **self:** `Block`

### OnUpdate

```lua
---@param self Block
---@param deltaTime number
function OnUpdate(self, deltaTime)
```

- #### Parameters:
  - **self:** `Block`
  - **deltaTime:** `number`

### OnBallRoll

```lua
---@param self Block
---@param rollIn boolean
---@param side Side
---@param ball Ball
function OnBallRoll(self, rollIn, side, ball)
```

- #### Parameters:
  - **self:** `Block`
  - **rollIn:** `boolean`
  - **side:** `Side`
  - **ball:** `Ball`

### OnProjectileCollide

```lua
---@param self Block
---@param projectile Projectile
function OnProjectileCollide(self, projectile)
```

- #### Parameters:
  - **self:** `Block`
  - **projectile:** `Projectile`

### OnDestroy

```lua
---@param self Block
function OnDestroy(self)
```

- #### Parameters:
  - **self:** `Block`

### OnSignal

```lua
---@param self Block
---@param signal Signal
function OnSignal(self, signal)
```

- #### Parameters:
  - **self:** `Block`
  - **signal:** `Signal`

### OnCustomEvent

```lua
---@param self Block
---@param event CustomEvent
function OnCustomEvent(self, event)
```

- #### Parameters:
  - **self:** `Block`
  - **event:** `CustomEvent`

## `Enemies` Hooks

Hooks related to enemy events, such as spawning, updating, colliding with projectiles, dying, being destroyed, and custom events.

### SpawnCondition

```lua
---@param self Enemy
---@return boolean
function SpawnCondition(self)
```

- #### Parameters:
  - **self:** `Enemy`
- #### Returns:

  `boolean`

### OnSpawn

```lua
---@param self Enemy
function OnSpawn(self)
```

- #### Parameters:
  - **self:** `Enemy`

### OnUpdate

```lua
---@param self Enemy
---@param deltaTime number
function OnUpdate(self, deltaTime)
```

- #### Parameters:
  - **self:** `Enemy`
  - **deltaTime:** `number`

### OnProjectileCollide

```lua
---@param self Enemy
---@param projectile Projectile
function OnProjectileCollide(self, projectile)
```

- #### Parameters:
  - **self:** `Enemy`
  - **projectile:** `Projectile`

### OnDeath

```lua
---@param self Enemy
function OnDeath(self)
```

- #### Parameters:
  - **self:** `Enemy`

### OnDestroy

```lua
---@param self Enemy
function OnDestroy(self)
```

- #### Parameters:
  - **self:** `Enemy`

### OnSignal

```lua
---@param self Enemy
---@param signal Signal
function OnSignal(self, signal)
```

- #### Parameters:
  - **self:** `Enemy`
  - **signal:** `Signal`

### OnCustomEvent

```lua
---@param self Enemy
---@param event CustomEvent
function OnCustomEvent(self, event)
```

- #### Parameters:
  - **self:** `Enemy`
  - **event:** `CustomEvent`

## `Items` Hooks

Hooks related to item events, such as spawning, updating, being collected by a ball, colliding with projectiles, being destroyed, and custom events.

### SpawnCondition

```lua
---@param self Item
---@return boolean
function SpawnCondition(self)
```

- #### Parameters:
  - **self:** `Item`
- #### Returns:

  `boolean`

### OnSpawn

```lua
---@param self Item
function OnSpawn(self)
```

- #### Parameters:
  - **self:** `Item`

### OnUpdate

```lua
---@param self Item
---@param deltaTime number
function OnUpdate(self, deltaTime)
```

- #### Parameters:
  - **self:** `Item`
  - **deltaTime:** `number`

### OnCollect

```lua
---@param self Item
---@param ball Ball
function OnCollect(self, ball)
```

- #### Parameters:
  - **self:** `Item`
  - **ball:** `Ball`

### OnProjectileCollide

```lua
---@param self Item
---@param projectile Projectile
function OnProjectileCollide(self, projectile)
```

- #### Parameters:
  - **self:** `Item`
  - **projectile:** `Projectile`

### OnDestroy

```lua
---@param self Item
function OnDestroy(self)
```

- #### Parameters:
  - **self:** `Item`

### OnSignal

```lua
---@param self Item
---@param signal Signal
function OnSignal(self, signal)
```

- #### Parameters:
  - **self:** `Item`
  - **signal:** `Signal`

### OnCustomEvent

```lua
---@param self Item
---@param event CustomEvent
function OnCustomEvent(self, event)
```

- #### Parameters:
  - **self:** `Item`
  - **event:** `CustomEvent`

## `Level` Hooks

Hooks related to level events, such as starting the level, updating the level state, winning the level, and losing the level.

### OnStart

```lua
---@param self Level
function OnStart(self)
```

- #### Parameters:
  - **self:** `Level`

### OnUpdate

```lua
---@param self Level
---@param deltaTime number
function OnUpdate(self, deltaTime)
```

- #### Parameters:
  - **self:** `Level`
  - **deltaTime:** `number`

### OnWon

```lua
---@param self Level
function OnWon(self)
```

- #### Parameters:
  - **self:** `Level`

### OnLost

```lua
---@param self Level
function OnLost(self)
```

- #### Parameters:
  - **self:** `Level`

### OnSignal

```lua
---@param self Level
function OnSignal(self)
```

- #### Parameters:
  - **self:** `Level`

## `Sides` Hooks

Hooks related to side events, such as spawning, updating, ball rolling, colliding with projectiles, being destroyed, and custom events.

### OnSpawn

```lua
---@param self Side
function OnSpawn(self)
```

- #### Parameters:
  - **self:** `Side`

### OnUpdate

```lua
---@param self Side
---@param deltaTime number
function OnUpdate(self, deltaTime)
```

- #### Parameters:
  - **self:** `Side`
  - **deltaTime:** `number`

### OnBallRoll

```lua
---@param self Side
---@param rollIn boolean
---@param ball Ball
function OnBallRoll(self, rollIn, ball)
```

- #### Parameters:
  - **self:** `Side`
  - **rollIn:** `boolean`
  - **ball:** `Ball`

### OnProjectileCollide

```lua
---@param self Side
---@param projectile Projectile
function OnProjectileCollide(self, projectile)
```

- #### Parameters:
  - **self:** `Side`
  - **projectile:** `Projectile`

### OnDestroy

```lua
---@param self Side
function OnDestroy(self)
```

- #### Parameters:
  - **self:** `Side`

### OnSignal

```lua
---@param self Side
---@param signal Signal
function OnSignal(self, signal)
```

- #### Parameters:
  - **self:** `Side`
  - **signal:** `Signal`

### OnCustomEvent

```lua
---@param self Side
---@param event CustomEvent
function OnCustomEvent(self, event)
```

- #### Parameters:
  - **self:** `Side`
  - **event:** `CustomEvent`
