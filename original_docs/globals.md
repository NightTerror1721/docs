# Global Variables and Functions

## Global Variables

### `_G`

```lua
--- static
---@type table<string, any>
_G
```

- **Type:** `table<string, any>`
- **Read\-only:** Yes
- **Static:** Yes

### `_VERSION`

```lua
--- static
---@type string
_VERSION
```

- **Type:** `string`
- **Read\-only:** Yes
- **Static:** Yes

## Global Functions

### `baseclass`

```lua
--- @param class table
--- @return table|nil
function baseclass(class)
```

Returns the base class from which the class passed in the "class" argument is derived. The result will be nil if that class has no base class.

- **Static:** Yes
- #### Parameters:
  - **class:** `table`
- **Returns:** `table|nil`

### `class`

```lua
--- @param className string
--- @param baseClass table|nil
--- @return table
function class(className, baseClass)
```

Creates a new table and prepares it to simulate a class. Methods can be added to it after it's created. Its base class can be specified in the second argument.

- **Static:** Yes
- #### Parameters:
  - **className:** `string`
  - **baseClass:** `table|nil`
- **Returns:** `table`

### `classof`

```lua
--- @param value any
--- @return any
function classof(value)
```

Returns the class of the parameter "value". If "value" is a primitive type, returns a string with the type name.

- **Static:** Yes
- #### Parameters:
  - **value:** `any`
- **Returns:** `any`

### `error`

```lua
--- @param message any
--- @param level number?
--- @return void
function error(message, level)
```

Raises an error with the message "message" and the level "level"

- **Static:** Yes
- #### Parameters:
  - **message:** `any`
  - **level:** `number?`

### `getmetatable`

```lua
--- @param obj any
--- @return table<string, any>?
function getmetatable(obj)
```

- **Static:** Yes
- #### Parameters:
  - **obj:** `any`
- **Returns:** `table<string, any>?`

### `import`

```lua
--- @param scriptName string
--- @return table<string, any>
function import(scriptName)
```

Loads the contents of the script "scriptName" into a table and returns it

- **Static:** Yes
- #### Parameters:
  - **scriptName:** `string`
- **Returns:** `table<string, any>`

### `include`

```lua
--- @param scriptName string
--- @return void
function include(scriptName)
```

Loads the contents of the script "scriptName" into the current script

- **Static:** Yes
- #### Parameters:
  - **scriptName:** `string`

### `instanceof`

```lua
--- @param value any
--- @param type any
--- @return boolean
function instanceof(value, type)
```

Checks whether the "value" is of the "type" class or a child class.You can check the primitive type if a string of that type is passed in the "type" parameter.

- **Static:** Yes
- #### Parameters:
  - **value:** `any`
  - **type:** `any`
- **Returns:** `boolean`

### `ipairs`

```lua
--- @param table table<any, any>|any[]
--- @return Iterator<[number, any]>
function ipairs(table)
```

- **Static:** Yes
- #### Parameters:
  - **table:** `table<any, any>|any[]`
- **Returns:** `Iterator<[number, any]>`

### `new`

```lua
--- @param class table
--- @param args any
--- @return table
function new(class, args)
```

Creates a table and prepares it to become an instance of "class", invoking its constructor, if it has one.

- **Static:** Yes
- #### Parameters:
  - **class:** `table`
  - **args:** `any`
- **Returns:** `table`

### `next`

```lua
--- @param table table<any, any>
--- @param index? any
--- @return any?
function next(table, index?)
```

- **Static:** Yes
- #### Parameters:
  - **table:** `table<any, any>`
  - **index?:** `any`
- **Returns:** `any?`

### `pairs`

```lua
--- @param table table<any, any>
--- @return Iterator<[any, any]>
function pairs(table)
```

- **Static:** Yes
- #### Parameters:
  - **table:** `table<any, any>`
- **Returns:** `Iterator<[any, any]>`

### `print`

```lua
--- @param value any
--- @return void
function print(value)
```

Prints the value of the argument to the console

- **Static:** Yes
- #### Parameters:
  - **value:** `any`

### `print`

```lua
--- @param value any?
--- @return void
function print(value)
```

- **Static:** Yes
- #### Parameters:
  - **value:** `any?`

### `rawequal`

```lua
--- @param v1 any?
--- @param v2 any?
--- @return boolean
function rawequal(v1, v2)
```

- **Static:** Yes
- #### Parameters:
  - **v1:** `any?`
  - **v2:** `any?`
- **Returns:** `boolean`

### `rawget`

```lua
--- @param table table<any, any>
--- @param index any
--- @return any?
function rawget(table, index)
```

- **Static:** Yes
- #### Parameters:
  - **table:** `table<any, any>`
  - **index:** `any`
- **Returns:** `any?`

### `rawnew`

```lua
--- @param class table
--- @return table
function rawnew(class)
```

Creates a table and prepares it to become a "class" instance ready to be used in a constructor.

- **Static:** Yes
- #### Parameters:
  - **class:** `table`
- **Returns:** `table`

### `rawset`

```lua
--- @param table table<any, any>
--- @param index any
--- @param value any?
--- @return table<any, any>
function rawset(table, index, value)
```

- **Static:** Yes
- #### Parameters:
  - **table:** `table<any, any>`
  - **index:** `any`
  - **value:** `any?`
- **Returns:** `table<any, any>`

### `require`

```lua
--- @param scriptName string
--- @return any
function require(scriptName)
```

Loads the module contained in the script "scriptName" into the current script. If the script "scriptName" returns anything, the require function will return the same.

- **Static:** Yes
- #### Parameters:
  - **scriptName:** `string`
- **Returns:** `any`

### `setmetatable`

```lua
--- @param obj any
--- @param metatable table<string, any>
--- @return table<string, any>?
function setmetatable(obj, metatable)
```

- **Static:** Yes
- #### Parameters:
  - **obj:** `any`
  - **metatable:** `table<string, any>`
- **Returns:** `table<string, any>?`

### `tonumber`

```lua
--- @param num any?
--- @param base? number
--- @return number?
function tonumber(num, base?)
```

- **Static:** Yes
- #### Parameters:
  - **num:** `any?`
  - **base?:** `number`
- **Returns:** `number?`

### `tostring`

```lua
--- @param value any?
--- @return string
function tostring(value)
```

- **Static:** Yes
- #### Parameters:
  - **value:** `any?`
- **Returns:** `string`

### `type`

```lua
--- @param value any?
--- @return string
function type(value)
```

- **Static:** Yes
- #### Parameters:
  - **value:** `any?`
- **Returns:** `string`
