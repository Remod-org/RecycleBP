# RecycleBP for Rust
Recycle items into blueprints if not already learned

Every time a player recycles an item they have not yet learned, a blueprint for that item should appear in the recycler output.  Once learned, blueprints for this particular item should no longer appear.  This is a more casual way for the players to gain blueprints which requires less scrap and which hearkens back to days gone by when blueprints were discovered in the wild.

The player will still get the usual recycling output from the item as well.

Note that if they find 5 AKs in a row they can learn the AK 5 times and hand them out to their friends and/or sell them in a shop, etc.  You get the idea.  It's not for everyone, certainly.

## Permissions
This plugin uses the Oxide/umod permissions system.  The sole permission is recyclebp.use.  If the configuration variable usePermission is set to true, this permission is required for the player to get blueprints from recycling.

## Configuration
```js
{
  "usePermission: false,
  "Version": {
    "Major": 1,
    "Minor": 0,
    "Patch": 1
  }
}
```

