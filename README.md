# base-terrain-feature-buffalo

The `Buffalo` terrain feature: a special resource a square can hold.

For example: Civ2's Buffalo, found on Plains.

This package only declares the class: it has no `main` and registers nothing, so installing it changes no game.
A game's rules register it and give it its yields.

```ts
import Buffalo from '@civ-clone/base-terrain-feature-buffalo/Buffalo';
import { instance as availableTerrainFeatureRegistryInstance } from '@civ-clone/core-terrain-feature/AvailableTerrainFeatureRegistry';

availableTerrainFeatureRegistryInstance.register(Buffalo);
```

Part of the Civ2 work (civ-clone/web-renderer#1008).
