# kubejs6-more-recipe-types
Fork of https://github.com/gcatkjspkgs/kubejs-more-recipe-types by gcatkjspkg - all credits go to them!

# QUICK START
All new types are functions inside of the `global` object. They should be called inside of the `recipes` event like so: `global.mrt.<mod>.<type>(event, {args}, <id>)`.

- the recipe id and almost all number and boolean parameters are optional
- to use nbt in items use Item.of(`<Item>`, `<Nbt>`)
- to use chance in items use Item.of(`<Item>`).withChance(`<Chance>`)
For more info look at the section below.


The docs for all mods supported by this script are here, on the original github - [docs](https://github.com/gcatkjspkgs/kubejs-more-recipe-types/tree/ad42069a450cd74d42159950bd5e290eb576959f/docs)


