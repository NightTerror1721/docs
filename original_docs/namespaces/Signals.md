# Namespace `Signals`

Namespace that contains constants and utilities related to signal handling within the Lua scripting environment.

## Functions

### `emit`

```lua
--- @param signal Signal
--- @return any
function Signals.emit(signal)
```

Emits a signal to be handled by entities in the level.

- **Static:** No
- #### Parameters:
  - **signal:** `Signal`
- **Returns:** `any`

___
```lua
--- @param signalProperties table
--- @return any
function Signals.emit(signalProperties)
```

Emits a signal to be handled by entities in the level. Example: Signals.Emit{ id \= 'MySignal', data \= { damage \= 1 } }

- **Static:** No
- #### Parameters:
  - **signalProperties:** `table`
- **Returns:** `any`

___

### `emitToAll`

```lua
--- @param signalId string
--- @param data any
--- @return any
function Signals.emitToAll(signalId, data)
```

Emits a signal to all entities in the level.

- **Static:** No
- #### Parameters:
  - **signalId:** `string`
  - **data:** `any`
- **Returns:** `any`

___
```lua
--- @param signalId string
--- @return any
function Signals.emitToAll(signalId)
```

Emits a signal to all entities in the level.

- **Static:** No
- #### Parameters:
  - **signalId:** `string`
- **Returns:** `any`

___

### `emitTo`

```lua
--- @param signalId string
--- @param target Element
--- @param data any
--- @return any
function Signals.emitTo(signalId, target, data)
```

Emits a signal to a specific target entity.

- **Static:** No
- #### Parameters:
  - **signalId:** `string`
  - **target:** `Element`
  - **data:** `any`
- **Returns:** `any`

___
```lua
--- @param signalId string
--- @param target Element
--- @return any
function Signals.emitTo(signalId, target)
```

Emits a signal to a specific target entity.

- **Static:** No
- #### Parameters:
  - **signalId:** `string`
  - **target:** `Element`
- **Returns:** `any`

___

### `emitToTag`

```lua
--- @param signalId string
--- @param tag string
--- @param data any
--- @return any
function Signals.emitToTag(signalId, tag, data)
```

Emits a signal to all entities with a specific tag.

- **Static:** No
- #### Parameters:
  - **signalId:** `string`
  - **tag:** `string`
  - **data:** `any`
- **Returns:** `any`

___
```lua
--- @param signalId string
--- @param tag string
--- @return any
function Signals.emitToTag(signalId, tag)
```

Emits a signal to all entities with a specific tag.

- **Static:** No
- #### Parameters:
  - **signalId:** `string`
  - **tag:** `string`
- **Returns:** `any`

___

### `emitToType`

```lua
--- @param signalId string
--- @param type EntityType
--- @param data any
--- @return any
function Signals.emitToType(signalId, type, data)
```

Emits a signal to all entities of a specific type.

- **Static:** No
- #### Parameters:
  - **signalId:** `string`
  - **type:** `EntityType`
  - **data:** `any`
- **Returns:** `any`

___
```lua
--- @param signalId string
--- @param type EntityType
--- @return any
function Signals.emitToType(signalId, type)
```

Emits a signal to all entities of a specific type.

- **Static:** No
- #### Parameters:
  - **signalId:** `string`
  - **type:** `EntityType`
- **Returns:** `any`

___

### `emitToTypeAndTag`

```lua
--- @param signalId string
--- @param type EntityType
--- @param tag string
--- @param data any
--- @return any
function Signals.emitToTypeAndTag(signalId, type, tag, data)
```

Emits a signal to all entities of a specific type and tag.

- **Static:** No
- #### Parameters:
  - **signalId:** `string`
  - **type:** `EntityType`
  - **tag:** `string`
  - **data:** `any`
- **Returns:** `any`

___
```lua
--- @param signalId string
--- @param type EntityType
--- @param tag string
--- @return any
function Signals.emitToTypeAndTag(signalId, type, tag)
```

Emits a signal to all entities of a specific type and tag.

- **Static:** No
- #### Parameters:
  - **signalId:** `string`
  - **type:** `EntityType`
  - **tag:** `string`
- **Returns:** `any`

___

### `emitToCustom`

```lua
--- @param signalId string
--- @param customFilter function
--- @param data any
--- @return any
function Signals.emitToCustom(signalId, customFilter, data)
```

Emits a signal to entities that pass a custom filter function.

- **Static:** No
- #### Parameters:
  - **signalId:** `string`
  - **customFilter:** `function`
  - **data:** `any`
- **Returns:** `any`

___
```lua
--- @param signalId string
--- @param customFilter function
--- @return any
function Signals.emitToCustom(signalId, customFilter)
```

Emits a signal to entities that pass a custom filter function.

- **Static:** No
- #### Parameters:
  - **signalId:** `string`
  - **customFilter:** `function`
- **Returns:** `any`
