

## Usage Example

```ts

import { moment } from "https://deno.land/x/deno_moment/mod.ts";
import { sleep } from "https://x.nest.land/sleep@1.0.0/mod.ts";

let now = moment();
await sleep(1)
let now2 = moment();

console.log(`\n${now} is before \n${now2} - \nis that true? --> ${now.isBefore(now2)} `)

```

## Trigger Usage Example

```sh

deno run https://deno.land/x/deno_moment/usage-example.ts

```

# Details 
see [original docs](https://momentjs.com/docs/)
