# Class `ElementProperty`

Represents an element property, allowing access to its information and current value.

## Properties

### `info`

```lua
---@type ElementPropertyInfo
ElementProperty.info
```

The information about the element property.

- **Type:** `ElementPropertyInfo`
- **Read\-only:** Yes
- **Static:** No

___

### `isHidden`

```lua
---@type boolean
ElementProperty.isHidden
```

Indicates whether the property is hidden or deprecated.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `type`

```lua
---@type string
ElementProperty.type
```

The type of the property, represented as a string (e.g., 'integer', 'float', 'boolean', 'string', or 'enum').

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** No

___

### `value`

```lua
---@type any
ElementProperty.value
```

The current value of the property, represented as a Lua value.

- **Type:** `any`
- **Read\-only:** Yes
- **Static:** No

## Static Properties

### `luaClassName`

```lua
--- static
---@type string
ElementProperty.luaClassName
```

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** Yes
