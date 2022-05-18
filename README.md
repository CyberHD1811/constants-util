# CONSTANTS-UTIL (WIP)

---

**_NOTE_: THIS NODE MODULE IS UNDER HEAVY DEVELOPMENT AND NOT READY FOR USAGE YET!!**

---

## Usage:

> _Javascript:_
>
> ```js
> const mathConstants = require("constants-util/math");
>
> console.log(mathConstants.SQRT3); // Will output 1.7320508075688772
> ```

<br />
<br />

> _Typescript:_
>
> ```ts
> import mathConstants from "constants-util/math";
>
> console.log(mathConstants.SQRT3); // Will output 1.7320508075688772
> ```

### Note:

-   You can only import the specific parts (e.g. math, chemistry, physics, etc.) from the module.
-   It is **_highly_** recommended to **_NOT_** destructure the constants object, _if_ you use more than one part. This is because some constants of different fields have the same name, so there would be potential issues.

---

## Documentation:

> Although i try to keep the documentation always up to date, i cannot guarantee the 100% coverage.

### Mathmatical constants:

**All irrational numbers have 16 digits (or 15 digits, if the 16th was a 0).**

-   PHI - The golden ratio
-   SQRT3 - Square root of 3
-   SQRT3 - Square root of 5
-   SQRT3 - Square root of 6
-   SQRT3 - Square root of 7
-   ZETA3 - Approximate value of 3 plugged into the "Riemann zeta function"
