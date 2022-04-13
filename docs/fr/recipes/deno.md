# Usage with Deno

[Deno](https://deno.land/) est un environnement d'exécution TypeScript/JavaScript alternatif, similaire à NodeJS, mais prend en charge TypeScript sintégré et n'est pas immédiatement compatible avec la plupart des packages npm.

Donc, pour exécuter XState sur Deno, vous devez l'importer différemment, via [Skypack](https://www.skypack.dev/). Les packages sont "installés" au moment de l'exécution ; plus de `/node_modules`!

```js
import { createMachine } from 'https://cdn.skypack.dev/xstate';
```

Vous pouvez le voir [en action ici](https://www.mycompiler.io/view/B8EgR64).
