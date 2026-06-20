# Recipes

Azor Plugin supports editable custom weapon recipes.

## View Recipes

```text
/recipes
```

## Edit Recipes

```text
/recipes edit
```

Admins can click a weapon, edit its 3x3 recipe, then save it.

## Runtime Recipe Files

Each weapon has its own recipe file generated on the server:

```text
plugins/AzorPlugin/weapons/<weapon_id>/recipe.yml
```

Do not manually edit files while the server is running unless you know what you are doing.


## Delayed Crafting

Custom Azor weapons use a delayed crafting ritual. When a player crafts a plugin weapon, the server announces the item and crafting table location, shows a boss bar, plays effects, then gives the completed item after its configured time.

Admins can limit crafting with:

```text
/az limit <weapon> <number|-1>
```
