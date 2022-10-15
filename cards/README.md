# Cards


mix new cards
iex -S mix
recompile
# Generate Docs
mix deps.get
mix docs
# Run Tests
mix test

## Notes:
No concept of classes or instances
arity: number of arguments a function accepts
All Data structures are immutable
Method name with a question mark returns True/False
List comprehension


## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed
by adding `cards` to your list of dependencies in `mix.exs`:

```elixir
def deps do
  [
    {:cards, "~> 0.1.0"}
  ]
end
```

Documentation can be generated with [ExDoc](https://github.com/elixir-lang/ex_doc)
and published on [HexDocs](https://hexdocs.pm). Once published, the docs can
be found at <https://hexdocs.pm/cards>.

