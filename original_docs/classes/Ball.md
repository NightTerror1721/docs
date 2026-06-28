# Class `Ball`

Represents a controllable ball entity in the game. Provides access to ball properties, movement, state, and gameplay interactions for Lua scripting.

## Properties

### `type`

```lua
---@type EntityType
Ball.type
```

- **Type:** `EntityType`
- **Read\-only:** Yes
- **Static:** No

___

### `name`

```lua
---@type string
Ball.name
```

The unique identifier of the ball.

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** No

___

### `tag`

```lua
---@type string
Ball.tag
```

The tag associated with the ball.

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** No

___

### `position`

```lua
---@type Vector3
Ball.position
```

The current position of the ball in the game world.

- **Type:** `Vector3`
- **Read\-only:** Yes
- **Static:** No

___

### `rotation`

```lua
---@type Quaternion
Ball.rotation
```

The current rotation of the ball in the game world.

- **Type:** `Quaternion`
- **Read\-only:** Yes
- **Static:** No

___

### `basis`

```lua
---@type Basis
Ball.basis
```

The current basis of the ball.

- **Type:** `Basis`
- **Read\-only:** Yes
- **Static:** No

___

### `blockSlot`

```lua
---@type BlockSlot
Ball.blockSlot
```

The block slot where the ball is currently located.

- **Type:** `BlockSlot`
- **Read\-only:** Yes
- **Static:** No

___

### `section`

```lua
---@type string
Ball.section
```

The ID of the section where the ball is located

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** No

___

### `isAlive`

```lua
---@type boolean
Ball.isAlive
```

Indicates whether the ball is currently alive and active in the game.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `currentMove`

```lua
---@type EntityMoveType
Ball.currentMove
```

The current ball movement.

- **Type:** `EntityMoveType`
- **Read\-only:** Yes
- **Static:** No

___

### `currentGroundSide`

```lua
---@type Side
Ball.currentGroundSide
```

The side the ball is currently on. Returns nil if the ball is in the air.

- **Type:** `Side`
- **Read\-only:** Yes
- **Static:** No

___

### `isOnAir`

```lua
---@type boolean
Ball.isOnAir
```

Indicates whether the ball is currently on the ground.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `jumpMode`

```lua
---@type BallJumpMode
Ball.jumpMode
```

The current jump mode of the ball.

- **Type:** `BallJumpMode`
- **Read\-only:** Yes
- **Static:** No

___

### `slowMode`

```lua
---@type boolean
Ball.slowMode
```

Enable or disable ball slow mode.

- **Type:** `boolean`
- **Read\-only:** No
- **Static:** No

___

### `mirrorMode`

```lua
---@type boolean
Ball.mirrorMode
```

Enable or disable ball mirror mode.

- **Type:** `boolean`
- **Read\-only:** No
- **Static:** No

___

### `isBurning`

```lua
---@type boolean
Ball.isBurning
```

Indicates whether the ball is burning

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `burningAmount`

```lua
---@type number
Ball.burningAmount
```

The current amount of burning affecting the ball.

- **Type:** `number`
- **Read\-only:** Yes
- **Static:** No

___

### `isIcy`

```lua
---@type boolean
Ball.isIcy
```

Indicates whether the ball is icy or not

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `hasShield`

```lua
---@type boolean
Ball.hasShield
```

Indicates whether the ball currently has an active shield.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `skin`

```lua
---@type integer
Ball.skin
```

The skin ID of the ball.

- **Type:** `integer`
- **Read\-only:** Yes
- **Static:** No

___

### `respawnSide`

```lua
---@type Side
Ball.respawnSide
```

- **Type:** `Side`
- **Read\-only:** Yes
- **Static:** No

___

### `respawnOrientation`

```lua
---@type Orientation
Ball.respawnOrientation
```

- **Type:** `Orientation`
- **Read\-only:** Yes
- **Static:** No

___

### `properties`

```lua
---@type ElementPropertyPool
Ball.properties
```

Gets the properties of the ball.

- **Type:** `ElementPropertyPool`
- **Read\-only:** Yes
- **Static:** No

___

### `localData`

```lua
---@type RawLocalData
Ball.localData
```

The local data associated with this element.

- **Type:** `RawLocalData`
- **Read\-only:** Yes
- **Static:** No

## Methods

### `kill`

```lua
--- @param cause LostLevelCause
--- @param timeToDie number
--- @return any
function Ball:kill(cause, timeToDie)
```

Kills the ball after a specified delay with a given cause.

- **Static:** No
- #### Parameters:
  - **cause:** `LostLevelCause`
  - **timeToDie:** `number`
- **Returns:** `any`

___
```lua
--- @param cause string
--- @param timeToDie number
--- @return any
function Ball:kill(cause, timeToDie)
```

Kills the ball after a specified delay with a custom cause.

- **Static:** No
- #### Parameters:
  - **cause:** `string`
  - **timeToDie:** `number`
- **Returns:** `any`

___
```lua
--- @param cause string
--- @param causeIcon LostLevelCause
--- @param timeToDie number
--- @return any
function Ball:kill(cause, causeIcon, timeToDie)
```

Kills the ball after a specified delay with a custom cause and icon.

- **Static:** No
- #### Parameters:
  - **cause:** `string`
  - **causeIcon:** `LostLevelCause`
  - **timeToDie:** `number`
- **Returns:** `any`

___

### `instaKill`

```lua
--- @param cause LostLevelCause
--- @return any
function Ball:instaKill(cause)
```

Instantly kills the ball with a given cause.

- **Static:** No
- #### Parameters:
  - **cause:** `LostLevelCause`
- **Returns:** `any`

___
```lua
--- @param cause string
--- @return any
function Ball:instaKill(cause)
```

Instantly kills the ball with a custom cause.

- **Static:** No
- #### Parameters:
  - **cause:** `string`
- **Returns:** `any`

___
```lua
--- @param cause string
--- @param causeIcon LostLevelCause
--- @return any
function Ball:instaKill(cause, causeIcon)
```

Instantly kills the ball with a custom cause and icon.

- **Static:** No
- #### Parameters:
  - **cause:** `string`
  - **causeIcon:** `LostLevelCause`
- **Returns:** `any`

___

### `teleportToSide`

```lua
--- @param side Side
--- @param orientation Orientation
--- @return boolean
function Ball:teleportToSide(side, orientation)
```

Teleports the ball to a specified side and orientation.

- **Static:** No
- #### Parameters:
  - **side:** `Side`
  - **orientation:** `Orientation`
- **Returns:** `boolean`

___

### `increaseJumpMode`

```lua
--- @return any
function Ball:increaseJumpMode()
```

Increases the jump mode of the ball.

- **Static:** No
- **Returns:** `any`

___

### `decreaseJumpMode`

```lua
--- @return any
function Ball:decreaseJumpMode()
```

Decreases the jump mode of the ball.

- **Static:** No
- **Returns:** `any`

___

### `doMove`

```lua
--- @param move EntityMoveType
--- @return any
function Ball:doMove(move)
```

Performs a move action for the ball.

- **Static:** No
- #### Parameters:
  - **move:** `EntityMoveType`
- **Returns:** `any`

___

### `linkBall`

```lua
--- @param ball Ball
--- @return any
function Ball:linkBall(ball)
```

Links the ball to another ball.

- **Static:** No
- #### Parameters:
  - **ball:** `Ball`
- **Returns:** `any`

___

### `unlinkBall`

```lua
--- @param ball Ball
--- @return any
function Ball:unlinkBall(ball)
```

Unlinks the ball from another ball.

- **Static:** No
- #### Parameters:
  - **ball:** `Ball`
- **Returns:** `any`

___

### `unlinkAllBalls`

```lua
--- @return any
function Ball:unlinkAllBalls()
```

Unlinks the ball from all linked balls.

- **Static:** No
- **Returns:** `any`

___

### `isBallLinked`

```lua
--- @param ball Ball
--- @return boolean
function Ball:isBallLinked(ball)
```

Checks if the ball is linked to another ball.

- **Static:** No
- #### Parameters:
  - **ball:** `Ball`
- **Returns:** `boolean`

___

### `getLinkedBalls`

```lua
--- @return Ball[]
function Ball:getLinkedBalls()
```

Gets a list of all balls linked to this ball.

- **Static:** No
- **Returns:** `Ball[]`

___

### `getLinkedBallsIterator`

```lua
--- @return Ball[]
function Ball:getLinkedBallsIterator()
```

Gets an iterator for all balls linked to this ball.

- **Static:** No
- **Returns:** `Ball[]`

___

### `addBurningAmount`

```lua
--- @param amount number
--- @return any
function Ball:addBurningAmount(amount)
```

Adds a specified amount of burning to the ball.

- **Static:** No
- #### Parameters:
  - **amount:** `number`
- **Returns:** `any`

___

### `increaseJumpAheadDistance`

```lua
--- @return any
function Ball:increaseJumpAheadDistance()
```

Increases the jump ahead distance of the ball.

- **Static:** No
- **Returns:** `any`

___

### `decreaseJumpAheadDistance`

```lua
--- @return any
function Ball:decreaseJumpAheadDistance()
```

Decreases the jump ahead distance of the ball.

- **Static:** No
- **Returns:** `any`

___

### `increaseJumpUpDistance`

```lua
--- @return any
function Ball:increaseJumpUpDistance()
```

Increases the jump up distance of the ball.

- **Static:** No
- **Returns:** `any`

___

### `decreaseJumpUpDistance`

```lua
--- @return any
function Ball:decreaseJumpUpDistance()
```

Decreases the jump up distance of the ball.

- **Static:** No
- **Returns:** `any`

___

### `changeGravity`

```lua
--- @param newFace Face
--- @return boolean
function Ball:changeGravity(newFace)
```

Changes the gravity of the ball to a specified face.

- **Static:** No
- #### Parameters:
  - **newFace:** `Face`
- **Returns:** `boolean`

___

### `enableShield`

```lua
--- @param seconds number
--- @return any
function Ball:enableShield(seconds)
```

Enables a shield for the ball for a specified duration.

- **Static:** No
- #### Parameters:
  - **seconds:** `number`
- **Returns:** `any`

___

### `increaseShieldTime`

```lua
--- @param seconds number
--- @return any
function Ball:increaseShieldTime(seconds)
```

Increases the shield time of the ball by a specified duration.

- **Static:** No
- #### Parameters:
  - **seconds:** `number`
- **Returns:** `any`

___

### `setRespawnLocation`

```lua
--- @param side Side
--- @param orientation Orientation
--- @return any
function Ball:setRespawnLocation(side, orientation)
```

Sets the respawn location of the ball to a specified side and orientation.

- **Static:** No
- #### Parameters:
  - **side:** `Side`
  - **orientation:** `Orientation`
- **Returns:** `any`

___
```lua
--- @param slot BlockSlot
--- @param face Face
--- @param orientation Orientation
--- @return any
function Ball:setRespawnLocation(slot, face, orientation)
```

Sets the respawn location of the ball to a specified block slot, face, and orientation.

- **Static:** No
- #### Parameters:
  - **slot:** `BlockSlot`
  - **face:** `Face`
  - **orientation:** `Orientation`
- **Returns:** `any`

___

### `collectItem`

```lua
--- @param item Item
--- @return any
function Ball:collectItem(item)
```

Collects a specified item for the ball.

- **Static:** No
- #### Parameters:
  - **item:** `Item`
- **Returns:** `any`

___

### `asLevel`

```lua
--- @return Level
function Ball:asLevel()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Level`

___

### `asBlock`

```lua
--- @return Block
function Ball:asBlock()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Block`

___

### `asSide`

```lua
--- @return Side
function Ball:asSide()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Side`

___

### `asItem`

```lua
--- @return Item
function Ball:asItem()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Item`

___

### `asEnemy`

```lua
--- @return Enemy
function Ball:asEnemy()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Enemy`

___

### `asBall`

```lua
--- @return Ball
function Ball:asBall()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Ball`

___

### `asDecoration`

```lua
--- @return Decoration
function Ball:asDecoration()
```

Casts the current element to a specific type if possible. Throws an error if the cast is invalid.

- **Static:** No
- **Returns:** `Decoration`
