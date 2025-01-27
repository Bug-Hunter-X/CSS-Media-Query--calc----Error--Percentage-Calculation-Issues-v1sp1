This repository demonstrates a subtle bug related to the CSS `calc()` function within media queries, specifically when dealing with percentage calculations. The bug occurs when the percentage calculation depends on a parent element's width that's not yet defined or when the calculation results in an invalid value.  The solution offers a workaround to resolve these inconsistencies.

**Bug:** The `bug.css` file contains the erroneous code.  Observe the unexpected behavior when resizing the browser window.

**Solution:** The `bugSolution.css` file provides a corrected version using a more robust approach to handle percentage calculations within media queries.  This may involve using a different calculation or adding fallbacks to ensure consistent layout.