# imageboard

Practice project


## System's context

1. Actors:
   * Anonymous
1. Use cases:
   * Check the thread of interest
   * Post to the thread of interest
   * Start new thread


### Use case specification

__Use case name__: Check the thread of interest
__Use case purpose__: Boards and threads constitute the imageboard. The usecase provides ability for an Actor to navigate hierarchy and view the contents of particular element.

__Optimistic flow__:
1. Check the board
1. Determine the thread of interest
1. Check the contents of a thread

__Pragmatic flow__:
  __Conditions trigerring alternate flow__:
    __Condition 1__: There is no threads of interest on the board.
      2. Provide ability to navigate to another board
