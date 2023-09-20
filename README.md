# ItemLib

> :warning: ItemLib is missing a lot a features and is still in active development! :warning:

ItemLib is a datapack library that allows items to have code be ran for special actions.

## Documentation

### Ticking Items

You can create a item that ticks whenever it is held by a player.

```mcfunction
give @s diamond{itemlib:{item_ticks:true, tick:"namespace:function"}}
```

"item_ticks" has to be set to true in order for the "tick" function to be called.

### Custom Durability

WIP
