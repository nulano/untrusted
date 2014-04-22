#The drones are leaving!
##Nulano

    if( me.getY()!=13) me.move('down');else me.move('right'); //attack drone
    
    me.move('up'); //reinforcement drone
    
    if ( me.getY()!=11) me.move('up');else me.move('right'); //defense drone
