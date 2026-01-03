# App

This directory is where code that is related to the state machine and not
board-specific goes.

For example, arming the timeout is not board-specific, so it doesn't make
sense to put it in the BSP. I still want to do the editing of this code in
my IDE instead of QM though, so putting it here accomplishes this.