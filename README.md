# CSS :hover Issue within Flex Container

This repository demonstrates a common issue encountered when using the `:hover` pseudo-class within a flex container.  The expected change in style on hover does not occur.

The `bug.css` file contains the problematic CSS code.  The solution is provided in `bugSolution.css`.

This issue arises due to the interaction between the flex container and the event propagation of the hover event. The solution provides a workaround that addresses the problem effectively.