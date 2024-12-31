# Go nil map panic
This repository demonstrates a common error in Go: panics caused by accessing nil maps.  The `bug.go` file contains code that will panic. `bugSolution.go` provides the corrected version.

The problem stems from attempting to assign a value to a map that hasn't been initialized.  Go will panic in this situation.  Always check for nil maps before accessing them to prevent unexpected crashes.
