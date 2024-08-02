# kubejs6-more-recipe-types
Basically a fork of https://github.com/gcatkjspkgs/kubejs-more-recipe-types by gcatkjspkg - all credits go to them!
I just made It work with KubeJS 6

# QUICK START
All new types are functions inside of the `global` object. They should be called inside of the `recipes` event like so: `global.mrt.<mod>.<type>(event, {args}, <id>)`.

- the recipe id and almost all number and boolean parameters are optional
- to use nbt in items use Item.of(`<Item>`, `<Nbt>`)
- to use chance in items use Item.of(`<Item>`).withChance(`<Chance>`)
For more info look at the section below.


The docs for all mods supported by this script are here, in the docs - [docs](https://github.com/Dangrainage/kubejs6-more-recipe-types/tree/a834a0c1afddad46e4330b9faa96fd8cf9ce6dcb/docs)
Find the mod, and that's It!


