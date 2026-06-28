# Class `Basis`

Represents a basis in 3D space. A basis defines the orientation of a face in 3D space.

## Properties

### `face`

```lua
---@type Face
Basis.face
```

Gets the face of the basis.

- **Type:** `Face`
- **Read\-only:** Yes
- **Static:** No

___

### `faceName`

```lua
---@type string
Basis.faceName
```

Gets the name of the face of the basis.

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** No

___

### `orientation`

```lua
---@type Orientation
Basis.orientation
```

Gets the orientation of the basis.

- **Type:** `Orientation`
- **Read\-only:** Yes
- **Static:** No

___

### `orientationName`

```lua
---@type string
Basis.orientationName
```

Gets the name of the orientation of the basis.

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** No

___

### `turnUp`

```lua
---@type Basis
Basis.turnUp
```

Gets the basis after turning up.

- **Type:** `Basis`
- **Read\-only:** Yes
- **Static:** No

___

### `turnDown`

```lua
---@type Basis
Basis.turnDown
```

Gets the basis after turning down.

- **Type:** `Basis`
- **Read\-only:** Yes
- **Static:** No

___

### `turnLeft`

```lua
---@type Basis
Basis.turnLeft
```

Gets the basis after turning left.

- **Type:** `Basis`
- **Read\-only:** Yes
- **Static:** No

___

### `turnRight`

```lua
---@type Basis
Basis.turnRight
```

Gets the basis after turning right.

- **Type:** `Basis`
- **Read\-only:** Yes
- **Static:** No

___

### `turnBack`

```lua
---@type Basis
Basis.turnBack
```

Gets the basis after turning back.

- **Type:** `Basis`
- **Read\-only:** Yes
- **Static:** No

___

### `front`

```lua
---@type Vector3
Basis.front
```

Gets the front vector of the basis.

- **Type:** `Vector3`
- **Read\-only:** Yes
- **Static:** No

___

### `back`

```lua
---@type Vector3
Basis.back
```

Gets the back vector of the basis.

- **Type:** `Vector3`
- **Read\-only:** Yes
- **Static:** No

___

### `right`

```lua
---@type Vector3
Basis.right
```

Gets the right vector of the basis.

- **Type:** `Vector3`
- **Read\-only:** Yes
- **Static:** No

___

### `left`

```lua
---@type Vector3
Basis.left
```

Gets the left vector of the basis.

- **Type:** `Vector3`
- **Read\-only:** Yes
- **Static:** No

___

### `up`

```lua
---@type Vector3
Basis.up
```

Gets the up vector of the basis.

- **Type:** `Vector3`
- **Read\-only:** Yes
- **Static:** No

___

### `down`

```lua
---@type Vector3
Basis.down
```

Gets the down vector of the basis.

- **Type:** `Vector3`
- **Read\-only:** Yes
- **Static:** No

## Methods

### `withFace`

```lua
--- @param face Face
--- @return Basis
function Basis:withFace(face)
```

Creates a new basis with the specified face.

- **Static:** No
- #### Parameters:
  - **face:** `Face`
- **Returns:** `Basis`

___

### `withOrientation`

```lua
--- @param orientation Orientation
--- @return Basis
function Basis:withOrientation(orientation)
```

Creates a new basis with the specified orientation.

- **Static:** No
- #### Parameters:
  - **orientation:** `Orientation`
- **Returns:** `Basis`

## Static Methods

### `new`

```lua
--- @return Basis
function Basis.new()
```

Creates a new basis with the default face and orientation.

- **Static:** Yes
- **Returns:** `Basis`

___
```lua
--- @param face Face
--- @return Basis
function Basis.new(face)
```

Creates a new basis with the specified face and default orientation.

- **Static:** Yes
- #### Parameters:
  - **face:** `Face`
- **Returns:** `Basis`

___
```lua
--- @param face Face
--- @param orientation Orientation
--- @return Basis
function Basis.new(face, orientation)
```

Creates a new basis with the specified face and orientation.

- **Static:** Yes
- #### Parameters:
  - **face:** `Face`
  - **orientation:** `Orientation`
- **Returns:** `Basis`
