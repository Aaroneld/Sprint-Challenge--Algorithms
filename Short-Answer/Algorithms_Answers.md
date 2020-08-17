#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a)
Constant

b)
As the input grows large the number of operations required inside of the while loop approaches zero for each cycle of the outer loop

O(n)

c)
O(n)
## Exercise II


def findFloorF(floors){

    if floors.length === 1:
        if floors[0].drop() === notBroken"
            return "floor f is floor[0]"
        else
            return "no floor f"

    middle = floors.length // 2

    if floors[middle].drop === notBroken:
        findFloor([floors[middle +1: len(floors)]])
    else 
        findFloor([0: middle -1])
}

O(log n)

adapted basic recursive binary search to find the uppermost floor where the eggs wont break by split the number of choices in half for each iteration 