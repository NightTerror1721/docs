# Namespace `Flyby`

Represents a flyby in the game. Provides methods to start flyby events and zoom actions.

## Functions

### `start`

```lua
--- @param events FlybyEvent[]
--- @return any
function Flyby.start(events)
```

Starts a flyby sequence with the specified events. Each event defines a specific action or movement for the flyby.

- **Static:** No
- #### Parameters:
  - **events:** `FlybyEvent[]`
- **Returns:** `any`

___

### `startZoomAt`

```lua
--- @param slot BlockSlot
--- @param face Face
--- @param orientation Orientation
--- @param look CameraLookPosition
--- @param goingDuration number
--- @param waitDuration number
--- @param returnDuration number
--- @return any
function Flyby.startZoomAt(slot, face, orientation, look, goingDuration, waitDuration, returnDuration)
```

Starts a zoom\-in sequence at the specified block slot, face, orientation, and camera look position.

- **Static:** No
- #### Parameters:
  - **slot:** `BlockSlot`
  - **face:** `Face`
  - **orientation:** `Orientation`
  - **look:** `CameraLookPosition`
  - **goingDuration:** `number`
  - **waitDuration:** `number`
  - **returnDuration:** `number`
- **Returns:** `any`

___
```lua
--- @param x integer
--- @param y integer
--- @param z integer
--- @param face Face
--- @param orientation Orientation
--- @param look CameraLookPosition
--- @param goingDuration number
--- @param waitDuration number
--- @param returnDuration number
--- @return any
function Flyby.startZoomAt(x, y, z, face, orientation, look, goingDuration, waitDuration, returnDuration)
```

Starts a zoom\-in sequence at the specified coordinates, face, orientation, and camera look position.

- **Static:** No
- #### Parameters:
  - **x:** `integer`
  - **y:** `integer`
  - **z:** `integer`
  - **face:** `Face`
  - **orientation:** `Orientation`
  - **look:** `CameraLookPosition`
  - **goingDuration:** `number`
  - **waitDuration:** `number`
  - **returnDuration:** `number`
- **Returns:** `any`
