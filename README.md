[v5code-project-Autonomous.zip](https://github.com/ManukMan/Code/files/10936189/v5code-project-Autonomous.zip)
/*----------------------------------------------------------------------------*/
/*                                                                            */
/*    Module:       main.cpp                                                  */
/*    Author:       C:\Users\99747190                                         */
/*    Created:      Wed Jan 18 2023                                           */
/*    Description:  V5 project                                                */
/*                                                                            */
/*----------------------------------------------------------------------------*/


// ---- START VEXCODE CONFIGURED DEVICES ----
// Robot Configuration:
// [Name]               [Type]        [Port(s)]
// Controller1          controller                   
// Drivetrain           drivetrain    2, 1           
// MotorGroup3          motor_group   3, 8           
// ---- END VEXCODE CONFIGURED DEVICES ----


#include "vex.h"


using namespace vex;
competition Competition;


void autonomous(void) {
 Drivetrain.driveFor(forward, 300,mm);
 MotorGroup3.spin(forward, 90, velocityUnits::pct);
}


void usercontrol(void) {
 while (1) {
   wait(20, msec);
 }
}


int main()  {


 // Initializing Robot Configuration. DO NOT REMOVE!
 Competition.autonomous(autonomous);
 Competition.drivercontrol(usercontrol);


 while (true) {
   wait(100, msec);
 }
}


Competition day 
https://drive.google.com/file/d/1NunNGTTHxQUx7h_371SZRcMe-dRlmj4S/view?usp=share_link 

