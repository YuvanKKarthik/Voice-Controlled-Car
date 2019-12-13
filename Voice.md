Voice-Controlled-Car:

    INTRODUCTION:
        The Voice controlled car is a car which will be working based on the voice commands given by the user.
        
    COMPONENTS USED:
        1.Arduino UNO
        2.Blutooth Module
        3.LC Motor Driver
        4.Wheels
        5.9V Battery
        
    WORKING:
        The car will be controlled by the commands which will be given in an android application which is available in the play store.The commands like forward, backward, left, right can be used to controll the car.
    The commands are transferred from the app to the car will be via a blutooth connection which will be establisted using the blutooth module. Here the commands from the app will be received b the blutooth module and 
    the commands will be converted into voltage signals such that the arduino can underststand the command. After understanding of command by the arduino the arduino sends the command to the LC driver and the LC driver 
    makes the wheel rotates as per the command. Hence the car moves by the voice command given by the user.
     
