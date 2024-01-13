# Module and functions
- PaskalCase for modules
- snake_case preferred for variable / functions name

## Modules
- Functional programming language
- Requires all named functions to be defined in a _module_
- Use `defmodule` to define module
```elixir
defmodule TestModule do
    # ...
end
```

## Named functions
```elixir
defmodule TestModule do
    def add(a, b) do
        a + b
    end
end

sum = TestModule.add(1,2) # => 3
```
- `defp` can be used to define private function
- Arity refers to the argument. E.g.: `add/2` for the above code
