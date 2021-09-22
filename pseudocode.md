    Instructions:  Passenger should be able to input whether to go up or down the elevator.

    Elevator should go to their floor, open its doors, and allow them on.  The passenger can input which floor they would like to go onto.  Elevator should take them to their destination while also picking up and dropping off other passengers, efficently along the way up.


First line of pseudocode starts now.

Start the program

INIT : INITIALIZE VARIBLES - these are my varibles, here is what i need to get started

set value to 0 

objects: Elevator, doors, display, buttons inside, buttons outside. 

increment: increase value of varible - something like i ++ (elevator going up)

decrement: decrease value of varible - something like i -- (elevator going down)

print, display, show, - print , show, or display your outcome of your code (console.log) (return) 

functions have to be broken down 

// what do we want?

// want the elevator to go down and up

// want the elevator to open and close doors

// want the elevator to have buttons, inside and out

// want to check if elevator is at current floor of passenger
// want to check if other passengers have called the elevator while on the way to original passenger

// we want seperate buttons to go up or down

// want elevator buttons to go up when pressed up

// want elevator buttons to go down when pressed down

// if up button is pressed {
    go up
}
if down button is pressed {
    go down 
}

// 
    function:  elevatorFloor
0; if elevator < elevatorFloor display currentFloor level 
    else if elevator > elevatorFloor display nothing

    function to check current floor:

1; Passenger presses outside elevator button

2; if elevator on passenger floor, open

3; else go to passenger floor

    function to check if more passengers want to get in the elevator while going to passenge: 

4; while elevator is going down to passenger floor (while)

5; check to see if another passenger has pressed a outside elevator button

6; if another passenger pressed a outside elevator button, stop at the floor

7; else continue going to passenger floor

    function that will check if elevator at passenger floor

8; if elevator = passenger floor 

9; open doors 

10; else keep doors closed 

function to open door at passenger floor

11: Elevator arrives at passenger floor

12: Open doors 

    function to go to move floor to floor going up or down

13; passenger presses desired floor by using a button on the inside.

14; if disired floor is up, then press inside up botton  (++)

15; else if disired floor is down, then press inside down button (--)

// in conclusion, elevators are rough. 