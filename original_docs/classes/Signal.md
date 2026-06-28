# Class `Signal`

Represents a signal that can be emitted and handled by entities within the level. Signals can carry data and can be filtered based on target entity, tag, type, or a custom filter function.

## Properties

### `id`

```lua
---@type string
Signal.id
```

The unique identifier for the signal.

- **Type:** `string`
- **Read\-only:** No
- **Static:** No

___

### `data`

```lua
---@type any
Signal.data
```

Optional data payload associated with the signal.

- **Type:** `any`
- **Read\-only:** No
- **Static:** No

___

### `target`

```lua
---@type Element
Signal.target
```

Optional target entity for the signal. If set, only this entity will receive the signal.

- **Type:** `Element`
- **Read\-only:** No
- **Static:** No

___

### `tagFilter`

```lua
---@type string
Signal.tagFilter
```

Optional tag filter. If set, only entities with this tag will receive the signal.

- **Type:** `string`
- **Read\-only:** No
- **Static:** No

___

### `typeFilter`

```lua
---@type EntityType
Signal.typeFilter
```

Type filter for the signal. Only entities of this type will receive the signal. Default is 'Any'.

- **Type:** `EntityType`
- **Read\-only:** No
- **Static:** No

___

### `customFilter`

```lua
---@type function
Signal.customFilter
```

Optional custom filter function. If set, this function will be called for each entity to determine if it should receive the signal. The function should accept two parameters: the entity and the signal, and return true to receive the signal or false to ignore it.

- **Type:** `function`
- **Read\-only:** No
- **Static:** No

## Static Methods

### `new`

```lua
--- @param id string
--- @param data any
--- @param target Element
--- @param tagFilter string
--- @param typeFilter EntityType
--- @param customFilter function
--- @return Signal
function Signal.new(id, data, target, tagFilter, typeFilter, customFilter)
```

Creates a new LuaSignal instance with the specified parameters.

- **Static:** Yes
- #### Parameters:
  - **id:** `string`
  - **data:** `any`
  - **target:** `Element`
  - **tagFilter:** `string`
  - **typeFilter:** `EntityType`
  - **customFilter:** `function`
- **Returns:** `Signal`

___
```lua
--- @param properties table
--- @return Signal
function Signal.new(properties)
```

Creates a new Signal instance from a table of properties. The table can contain the following fields:  
\- id (string, mandatory): The unique identifier for the signal.  
\- data (any, optional): Optional data payload associated with the signal.  
\- target (Element, optional): Optional target entity for the signal. If set, only this entity will receive the signal.  
\- tagFilter (string, optional): Optional tag filter. If set, only entities with this tag will receive the signal.  
\- typeFilter (EntityType, optional): Type filter for the signal. Only entities of this type will receive the signal. Default is 'Any'.  
\- customFilter (function, optional): Optional custom filter function. If set, this function will be called for each entity to determine if it should receive the signal. The function should accept two parameters: the entity and the signal, and return true to receive the signal or false to ignore it.

- #### Example usage in Lua:

  ```lua
  local mySignal = Signal.New{
      id = 'MySignal',
      data = { activate = true },
      tagFilter = 'secret-switches',
      typeFilter = EntityType.Side,
  }
  Signals.Emit(mySignal)
  ```
- **Static:** Yes
- #### Parameters:
  - **properties:** `table`
- **Returns:** `Signal`
