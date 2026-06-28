# Class `Quaternion`

Represents a quaternion.

## Properties

### `x`

```lua
---@type number
Quaternion.x
```

- **Type:** `number`
- **Read\-only:** No
- **Static:** No

___

### `y`

```lua
---@type number
Quaternion.y
```

- **Type:** `number`
- **Read\-only:** No
- **Static:** No

___

### `z`

```lua
---@type number
Quaternion.z
```

- **Type:** `number`
- **Read\-only:** No
- **Static:** No

___

### `w`

```lua
---@type number
Quaternion.w
```

- **Type:** `number`
- **Read\-only:** No
- **Static:** No

___

### `[][integer]: number`

```lua
---@param index integer
---@return number
function Quaternion.__index(index)

---@param index integer
---@param value number
function Quaternion.__newindex(index, value)
```

- **Type:** `number`
- **Read\-only:** No

___

### `eulerAngles`

```lua
---@type Vector3
Quaternion.eulerAngles
```

- **Type:** `Vector3`
- **Read\-only:** No
- **Static:** No

___

### `normalized`

```lua
---@type Quaternion
Quaternion.normalized
```

- **Type:** `Quaternion`
- **Read\-only:** Yes
- **Static:** No

___

### `inverse`

```lua
---@type Quaternion
Quaternion.inverse
```

- **Type:** `Quaternion`
- **Read\-only:** Yes
- **Static:** No

## Methods

### `copy`

```lua
--- @return Quaternion
function Quaternion:copy()
```

- **Static:** No
- **Returns:** `Quaternion`

___

### `set`

```lua
--- @param x number
--- @param y number
--- @param z number
--- @param w number
--- @return any
function Quaternion:set(x, y, z, w)
```

- **Static:** No
- #### Parameters:
  - **x:** `number`
  - **y:** `number`
  - **z:** `number`
  - **w:** `number`
- **Returns:** `any`

___

### `normalize`

```lua
--- @return any
function Quaternion:normalize()
```

- **Static:** No
- **Returns:** `any`

___

### `setLookRotation`

```lua
--- @param view Vector3
--- @return any
function Quaternion:setLookRotation(view)
```

- **Static:** No
- #### Parameters:
  - **view:** `Vector3`
- **Returns:** `any`

___
```lua
--- @param view Vector3
--- @param up Vector3
--- @return any
function Quaternion:setLookRotation(view, up)
```

- **Static:** No
- #### Parameters:
  - **view:** `Vector3`
  - **up:** `Vector3`
- **Returns:** `any`

___

### `setFromToRotation`

```lua
--- @param fromDirection Vector3
--- @param toDirection Vector3
--- @return any
function Quaternion:setFromToRotation(fromDirection, toDirection)
```

- **Static:** No
- #### Parameters:
  - **fromDirection:** `Vector3`
  - **toDirection:** `Vector3`
- **Returns:** `any`

## Static Properties

### `identity`

```lua
--- static
---@type Quaternion
Quaternion.identity
```

- **Type:** `Quaternion`
- **Read\-only:** Yes
- **Static:** Yes

## Static Methods

### `new`

```lua
--- @param x number
--- @param y number
--- @param z number
--- @param w number
--- @return Quaternion
function Quaternion.new(x, y, z, w)
```

- **Static:** Yes
- #### Parameters:
  - **x:** `number`
  - **y:** `number`
  - **z:** `number`
  - **w:** `number`
- **Returns:** `Quaternion`

___
```lua
--- @return Quaternion
function Quaternion.new()
```

- **Static:** Yes
- **Returns:** `Quaternion`

___

### `fromToRotation`

```lua
--- @param fromDirection Vector3
--- @param toDirection Vector3
--- @return Quaternion
function Quaternion.fromToRotation(fromDirection, toDirection)
```

- **Static:** Yes
- #### Parameters:
  - **fromDirection:** `Vector3`
  - **toDirection:** `Vector3`
- **Returns:** `Quaternion`

___

### `slerp`

```lua
--- @param a Quaternion
--- @param b Quaternion
--- @param t number
--- @return Quaternion
function Quaternion.slerp(a, b, t)
```

- **Static:** Yes
- #### Parameters:
  - **a:** `Quaternion`
  - **b:** `Quaternion`
  - **t:** `number`
- **Returns:** `Quaternion`

___

### `slerpUnclamped`

```lua
--- @param a Quaternion
--- @param b Quaternion
--- @param t number
--- @return Quaternion
function Quaternion.slerpUnclamped(a, b, t)
```

- **Static:** Yes
- #### Parameters:
  - **a:** `Quaternion`
  - **b:** `Quaternion`
  - **t:** `number`
- **Returns:** `Quaternion`

___

### `lerp`

```lua
--- @param a Quaternion
--- @param b Quaternion
--- @param t number
--- @return Quaternion
function Quaternion.lerp(a, b, t)
```

- **Static:** Yes
- #### Parameters:
  - **a:** `Quaternion`
  - **b:** `Quaternion`
  - **t:** `number`
- **Returns:** `Quaternion`

___

### `lerpUnclamped`

```lua
--- @param a Quaternion
--- @param b Quaternion
--- @param t number
--- @return Quaternion
function Quaternion.lerpUnclamped(a, b, t)
```

- **Static:** Yes
- #### Parameters:
  - **a:** `Quaternion`
  - **b:** `Quaternion`
  - **t:** `number`
- **Returns:** `Quaternion`

___

### `angleAxis`

```lua
--- @param angle number
--- @param axis Vector3
--- @return Quaternion
function Quaternion.angleAxis(angle, axis)
```

- **Static:** Yes
- #### Parameters:
  - **angle:** `number`
  - **axis:** `Vector3`
- **Returns:** `Quaternion`

___

### `lookRotation`

```lua
--- @param forward Vector3
--- @param upwards Vector3
--- @return Quaternion
function Quaternion.lookRotation(forward, upwards)
```

- **Static:** Yes
- #### Parameters:
  - **forward:** `Vector3`
  - **upwards:** `Vector3`
- **Returns:** `Quaternion`

___
```lua
--- @param forward Vector3
--- @return Quaternion
function Quaternion.lookRotation(forward)
```

- **Static:** Yes
- #### Parameters:
  - **forward:** `Vector3`
- **Returns:** `Quaternion`

___

### `dot`

```lua
--- @param a Quaternion
--- @param b Quaternion
--- @return number
function Quaternion.dot(a, b)
```

- **Static:** Yes
- #### Parameters:
  - **a:** `Quaternion`
  - **b:** `Quaternion`
- **Returns:** `number`

___

### `angle`

```lua
--- @param a Quaternion
--- @param b Quaternion
--- @return number
function Quaternion.angle(a, b)
```

- **Static:** Yes
- #### Parameters:
  - **a:** `Quaternion`
  - **b:** `Quaternion`
- **Returns:** `number`

___

### `euler`

```lua
--- @param x number
--- @param y number
--- @param z number
--- @return Quaternion
function Quaternion.euler(x, y, z)
```

- **Static:** Yes
- #### Parameters:
  - **x:** `number`
  - **y:** `number`
  - **z:** `number`
- **Returns:** `Quaternion`

___
```lua
--- @param euler Vector3
--- @return Quaternion
function Quaternion.euler(euler)
```

- **Static:** Yes
- #### Parameters:
  - **euler:** `Vector3`
- **Returns:** `Quaternion`

___

### `rotateTowards`

```lua
--- @param from Quaternion
--- @param to Quaternion
--- @param maxDegreesDelta number
--- @return Quaternion
function Quaternion.rotateTowards(from, to, maxDegreesDelta)
```

- **Static:** Yes
- #### Parameters:
  - **from:** `Quaternion`
  - **to:** `Quaternion`
  - **maxDegreesDelta:** `number`
- **Returns:** `Quaternion`
