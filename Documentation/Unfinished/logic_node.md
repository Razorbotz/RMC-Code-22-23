# File: logic_node.cpp
## Authors: Andrew Burroughs, Bill Johnson
## Documentation Author: Andrew Burroughs
## Detailed Description: 
This file implements the logic needed to create the logic node.  It receives information published by the communication node, then wraps that information into topics, and publishes the topics.  The node listens for the information sent by the user and received by the communication node, then translates this information into instructions that are then implemented by the motors.

## Issues:


# Software Documentation
## Global Variables
### **rclcpp::Node::SharedPtr nodeHandle**
Description of variable

### **float joystick1Roll**
Description of variable

### **float joystick1Pitch**
Description of variable

### **float joystick1Yaw**
Description of variable

### **float joystick1Throttle**
Description of variable

### **bool automationGo**
Description of variable

### **bool invertDrum**
Description of variable

### **bool excavationGo**
Description of variable

### **Automation* automation**
Description of variable

### **driveLeftSpeedPublisher**
Description of variable

### **driveRightSpeedPublisher**
Description of variable

### **dumpBinSpeedPublisher**
Description of variable

### **shoulderSpeedPublisher**
Description of variable

### **excavationArmPublisher**
Description of variable

### **excavationDrumPublisher**
Description of variable

### **servoStatePublisher**
Description of variable

## #Function Documentation
### **void initSetSpeed**():
Description of function
#### Expected Input, Range(s) of Input

#### Expected Outputs / Results, Range

### **void updateSpeed**():
Description of function
#### Expected Input, Range(s) of Input

#### Expected Outputs / Results, Range


### **void stopSpeed**():
Description of function
#### Expected Input, Range(s) of Input

#### Expected Outputs / Results, Range


### **void updateExcavation**():
Description of function
#### Expected Input, Range(s) of Input

#### Expected Outputs / Results, Range


### **void stopExcavation**():
Description of function
#### Expected Input, Range(s) of Input

#### Expected Outputs / Results, Range


### **void joystickAxisCallback**(const messages::msg::AxisState::SharedPtr axisState):
Description of function
#### Expected Input, Range(s) of Input

#### Expected Outputs / Results, Range


### **void joystickButtonCallback**(const messages::msg::ButtonState::SharedPtr buttonState):
Description of function
#### Expected Input, Range(s) of Input

#### Expected Outputs / Results, Range


### **void joystickHatCallback**(const messages::msg::HatState::SharedPtr hatState):
Description of function
#### Expected Input, Range(s) of Input

#### Expected Outputs / Results, Range


### **void keyCallback**(const messages::msg::KeyState::SharedPtr keyState):
Description of function
#### Expected Input, Range(s) of Input

#### Expected Outputs / Results, Range


### **void zedPositionCallback**(const messages::msg::ZedPosition::SharedPtr zedPosition): 
Description of function
#### Expected Input, Range(s) of Input

#### Expected Outputs / Results, Range


# Change Log:
7/3/2022: Documentation was created
10/3/2022: Descriptions and issues were added by Andrew Burroughs
