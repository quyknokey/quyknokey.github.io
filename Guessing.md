```mermaid
flowchart TD
A([Start]) -> B[Initialize Game]
B--﻿﻿﻿> C[Player Makes a Guess]
C-﻿-> D{Is the Guess Correct?}
D-﻿﻿﻿- Yes -> E[Display 'You Win!']
D -- No -> F{Attempts Left?}
F - Yes --> C
F -- No —> G[Display 'Game Over']
E -> H([End])
G -→> H 
```
