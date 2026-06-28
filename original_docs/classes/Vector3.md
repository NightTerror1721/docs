# Class `Vector3`

## Properties

### `x`

```lua
---@type number
Vector3.x
```

- **Type:** `number`
- **Read\-only:** No
- **Static:** No

___

### `y`

```lua
---@type number
Vector3.y
```

- **Type:** `number`
- **Read\-only:** No
- **Static:** No

___

### `z`

```lua
---@type number
Vector3.z
```

- **Type:** `number`
- **Read\-only:** No
- **Static:** No

___

### `[][integer]: number`

```lua
---@param index integer
---@return number
function Vector3.__index(index)

---@param index integer
---@param value number
function Vector3.__newindex(index, value)
```

- **Type:** `number`
- **Read\-only:** No

___

### `normalized`

```lua
---@type Vector3
Vector3.normalized
```

- **Type:** `Vector3`
- **Read\-only:** Yes
- **Static:** No

___

### `magnitude`

```lua
---@type number
Vector3.magnitude
```

- **Type:** `number`
- **Read\-only:** Yes
- **Static:** No

___

### `sqrMagnitude`

```lua
---@type number
Vector3.sqrMagnitude
```

- **Type:** `number`
- **Read\-only:** Yes
- **Static:** No

## Methods

### `copy`

```lua
--- @return Vector3
function Vector3:copy()
```

- **Static:** No
- **Returns:** `Vector3`

___

### `set`

```lua
--- @param x number
--- @param y number
--- @param z number
--- @return any
function Vector3:set(x, y, z)
```

- **Static:** No
- #### Parameters:
  - **x:** `number`
  - **y:** `number`
  - **z:** `number`
- **Returns:** `any`

___

### `normalize`

```lua
--- @return any
function Vector3:normalize()
```

- **Static:** No
- **Returns:** `any`

## Static Properties

### `zero`

```lua
--- static
---@type Vector3
Vector3.zero
```

- **Type:** `Vector3`
- **Read\-only:** Yes
- **Static:** Yes

___

### `one`

```lua
--- static
---@type Vector3
Vector3.one
```

- **Type:** `Vector3`
- **Read\-only:** Yes
- **Static:** Yes

___

### `forward`

```lua
--- static
---@type Vector3
Vector3.forward
```

- **Type:** `Vector3`
- **Read\-only:** Yes
- **Static:** Yes

___

### `back`

```lua
--- static
---@type Vector3
Vector3.back
```

- **Type:** `Vector3`
- **Read\-only:** Yes
- **Static:** Yes

___

### `up`

```lua
--- static
---@type Vector3
Vector3.up
```

- **Type:** `Vector3`
- **Read\-only:** Yes
- **Static:** Yes

___

### `down`

```lua
--- static
---@type Vector3
Vector3.down
```

- **Type:** `Vector3`
- **Read\-only:** Yes
- **Static:** Yes

___

### `left`

```lua
--- static
---@type Vector3
Vector3.left
```

- **Type:** `Vector3`
- **Read\-only:** Yes
- **Static:** Yes

___

### `right`

```lua
--- static
---@type Vector3
Vector3.right
```

- **Type:** `Vector3`
- **Read\-only:** Yes
- **Static:** Yes

___

### `positiveInfinity`

```lua
--- static
---@type Vector3
Vector3.positiveInfinity
```

- **Type:** `Vector3`
- **Read\-only:** Yes
- **Static:** Yes

___

### `negativeInfinity`

```lua
--- static
---@type Vector3
Vector3.negativeInfinity
```

- **Type:** `Vector3`
- **Read\-only:** Yes
- **Static:** Yes

## Static Methods

### `new`

```lua
--- @param x number
--- @param y number
--- @param z number
--- @return Vector3
function Vector3.new(x, y, z)
```

- **Static:** Yes
- #### Parameters:
  - **x:** `number`
  - **y:** `number`
  - **z:** `number`
- **Returns:** `Vector3`

___
```lua
--- @return Vector3
function Vector3.new()
```

- **Static:** Yes
- **Returns:** `Vector3`

___

### `scale`

```lua
--- @param scale Vector3
--- @return any
function Vector3.scale(scale)
```

- **Static:** No
- #### Parameters:
  - **scale:** `Vector3`
- **Returns:** `any`

___
```lua
--- @param a Vector3
--- @param b Vector3
--- @return Vector3
function Vector3.scale(a, b)
```

- **Static:** Yes
- #### Parameters:
  - **a:** `Vector3`
  - **b:** `Vector3`
- **Returns:** `Vector3`

___

### `slerp`

```lua
--- @param a Vector3
--- @param b Vector3
--- @param t number
--- @return Vector3
function Vector3.slerp(a, b, t)
```

- **Static:** Yes
- #### Parameters:
  - **a:** `Vector3`
  - **b:** `Vector3`
  - **t:** `number`
- **Returns:** `Vector3`

___

### `slerpUnclamped`

```lua
--- @param a Vector3
--- @param b Vector3
--- @param t number
--- @return Vector3
function Vector3.slerpUnclamped(a, b, t)
```

- **Static:** Yes
- #### Parameters:
  - **a:** `Vector3`
  - **b:** `Vector3`
  - **t:** `number`
- **Returns:** `Vector3`

___

### `orthoNormalize`

```lua
--- @param normal Vector3
--- @param tangent Vector3
--- @return any
function Vector3.orthoNormalize(normal, tangent)
```

- **Static:** Yes
- #### Parameters:
  - **normal:** `Vector3`
  - **tangent:** `Vector3`
- **Returns:** `any`

___
```lua
--- @param normal Vector3
--- @param tangent Vector3
--- @param binormal Vector3
--- @return any
function Vector3.orthoNormalize(normal, tangent, binormal)
```

- **Static:** Yes
- #### Parameters:
  - **normal:** `Vector3`
  - **tangent:** `Vector3`
  - **binormal:** `Vector3`
- **Returns:** `any`

___

### `rotateTowards`

```lua
--- @param current Vector3
--- @param target Vector3
--- @param maxRadiansDelta number
--- @param maxMagnitudeDelta number
--- @return Vector3
function Vector3.rotateTowards(current, target, maxRadiansDelta, maxMagnitudeDelta)
```

- **Static:** Yes
- #### Parameters:
  - **current:** `Vector3`
  - **target:** `Vector3`
  - **maxRadiansDelta:** `number`
  - **maxMagnitudeDelta:** `number`
- **Returns:** `Vector3`

___

### `lerp`

```lua
--- @param a Vector3
--- @param b Vector3
--- @param t number
--- @return Vector3
function Vector3.lerp(a, b, t)
```

- **Static:** Yes
- #### Parameters:
  - **a:** `Vector3`
  - **b:** `Vector3`
  - **t:** `number`
- **Returns:** `Vector3`

___

### `lerpUnclamped`

```lua
--- @param a Vector3
--- @param b Vector3
--- @param t number
--- @return Vector3
function Vector3.lerpUnclamped(a, b, t)
```

- **Static:** Yes
- #### Parameters:
  - **a:** `Vector3`
  - **b:** `Vector3`
  - **t:** `number`
- **Returns:** `Vector3`

___

### `moveTowards`

```lua
--- @param current Vector3
--- @param target Vector3
--- @param maxDistanceDelta number
--- @return Vector3
function Vector3.moveTowards(current, target, maxDistanceDelta)
```

- **Static:** Yes
- #### Parameters:
  - **current:** `Vector3`
  - **target:** `Vector3`
  - **maxDistanceDelta:** `number`
- **Returns:** `Vector3`

___

### `smoothDamp`

```lua
--- @param current Vector3
--- @param target Vector3
--- @param currentVelocity Vector3
--- @param smoothTime number
--- @param maxSpeed number
--- @param deltaTime number
--- @return Vector3
function Vector3.smoothDamp(current, target, currentVelocity, smoothTime, maxSpeed, deltaTime)
```

- **Static:** Yes
- #### Parameters:
  - **current:** `Vector3`
  - **target:** `Vector3`
  - **currentVelocity:** `Vector3`
  - **smoothTime:** `number`
  - **maxSpeed:** `number`
  - **deltaTime:** `number`
- **Returns:** `Vector3`

___
```lua
--- @param current Vector3
--- @param target Vector3
--- @param currentVelocity Vector3
--- @param smoothTime number
--- @param maxSpeed number
--- @return Vector3
function Vector3.smoothDamp(current, target, currentVelocity, smoothTime, maxSpeed)
```

- **Static:** Yes
- #### Parameters:
  - **current:** `Vector3`
  - **target:** `Vector3`
  - **currentVelocity:** `Vector3`
  - **smoothTime:** `number`
  - **maxSpeed:** `number`
- **Returns:** `Vector3`

___
```lua
--- @param current Vector3
--- @param target Vector3
--- @param currentVelocity Vector3
--- @param smoothTime number
--- @return Vector3
function Vector3.smoothDamp(current, target, currentVelocity, smoothTime)
```

- **Static:** Yes
- #### Parameters:
  - **current:** `Vector3`
  - **target:** `Vector3`
  - **currentVelocity:** `Vector3`
  - **smoothTime:** `number`
- **Returns:** `Vector3`

___

### `cross`

```lua
--- @param lhs Vector3
--- @param rhs Vector3
--- @return Vector3
function Vector3.cross(lhs, rhs)
```

- **Static:** Yes
- #### Parameters:
  - **lhs:** `Vector3`
  - **rhs:** `Vector3`
- **Returns:** `Vector3`

___

### `reflect`

```lua
--- @param inDirection Vector3
--- @param inNormal Vector3
--- @return Vector3
function Vector3.reflect(inDirection, inNormal)
```

- **Static:** Yes
- #### Parameters:
  - **inDirection:** `Vector3`
  - **inNormal:** `Vector3`
- **Returns:** `Vector3`

___

### `dot`

```lua
--- @param lhs Vector3
--- @param rhs Vector3
--- @return number
function Vector3.dot(lhs, rhs)
```

- **Static:** Yes
- #### Parameters:
  - **lhs:** `Vector3`
  - **rhs:** `Vector3`
- **Returns:** `number`

___

### `project`

```lua
--- @param vector Vector3
--- @param onNormal Vector3
--- @return Vector3
function Vector3.project(vector, onNormal)
```

- **Static:** Yes
- #### Parameters:
  - **vector:** `Vector3`
  - **onNormal:** `Vector3`
- **Returns:** `Vector3`

___

### `projectOnPlane`

```lua
--- @param vector Vector3
--- @param planeNormal Vector3
--- @return Vector3
function Vector3.projectOnPlane(vector, planeNormal)
```

- **Static:** Yes
- #### Parameters:
  - **vector:** `Vector3`
  - **planeNormal:** `Vector3`
- **Returns:** `Vector3`

___

### `angle`

```lua
--- @param from Vector3
--- @param to Vector3
--- @return number
function Vector3.angle(from, to)
```

- **Static:** Yes
- #### Parameters:
  - **from:** `Vector3`
  - **to:** `Vector3`
- **Returns:** `number`

___

### `signedAngle`

```lua
--- @param from Vector3
--- @param to Vector3
--- @param axis Vector3
--- @return number
function Vector3.signedAngle(from, to, axis)
```

- **Static:** Yes
- #### Parameters:
  - **from:** `Vector3`
  - **to:** `Vector3`
  - **axis:** `Vector3`
- **Returns:** `number`

___

### `distance`

```lua
--- @param a Vector3
--- @param b Vector3
--- @return number
function Vector3.distance(a, b)
```

- **Static:** Yes
- #### Parameters:
  - **a:** `Vector3`
  - **b:** `Vector3`
- **Returns:** `number`

___

### `clampMagnitude`

```lua
--- @param vector Vector3
--- @param maxLength number
--- @return Vector3
function Vector3.clampMagnitude(vector, maxLength)
```

- **Static:** Yes
- #### Parameters:
  - **vector:** `Vector3`
  - **maxLength:** `number`
- **Returns:** `Vector3`

___

### `min`

```lua
--- @param lhs Vector3
--- @param rhs Vector3
--- @return Vector3
function Vector3.min(lhs, rhs)
```

- **Static:** Yes
- #### Parameters:
  - **lhs:** `Vector3`
  - **rhs:** `Vector3`
- **Returns:** `Vector3`

___

### `max`

```lua
--- @param lhs Vector3
--- @param rhs Vector3
--- @return Vector3
function Vector3.max(lhs, rhs)
```

- **Static:** Yes
- #### Parameters:
  - **lhs:** `Vector3`
  - **rhs:** `Vector3`
- **Returns:** `Vector3`
