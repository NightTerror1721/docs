# Class `ElementPropertyInfo`

Provides information about an element property, including its type, name, description, and default value.

## Properties

### `type`

```lua
---@type string
ElementPropertyInfo.type
```

The type of the property, represented as a string (e.g., 'integer', 'float', 'boolean', 'string', or 'enum').

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** No

___

### `isHidden`

```lua
---@type boolean
ElementPropertyInfo.isHidden
```

Indicates whether the property is hidden or deprecated.

- **Type:** `boolean`
- **Read\-only:** Yes
- **Static:** No

___

### `name`

```lua
---@type string
ElementPropertyInfo.name
```

The name of the property.

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** No

___

### `description`

```lua
---@type string
ElementPropertyInfo.description
```

The description of the property.

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** No

___

### `defaultValue`

```lua
---@type any
ElementPropertyInfo.defaultValue
```

The default value of the property, represented as a Lua value.

- **Type:** `any`
- **Read\-only:** Yes
- **Static:** No

___

### `enumValues`

```lua
---@type any[]
ElementPropertyInfo.enumValues
```

The possible enum values for the property, if it is of type 'enum'.

- **Type:** `any[]`
- **Read\-only:** Yes
- **Static:** No
