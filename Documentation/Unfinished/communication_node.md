# File: communication_node.cpp
## Author: Bill Johnson
## Documentation Author: Andrew Burroughs
## Detailed Description: 

## Issues:


# Software Documentation
## Global Variables
### **std_msgs::msg::Empty empty
Description of variable

### **bool silentRunning**
Description of variable

### **int new_socket**
Description of variable

### **rclcpp::Node::SharedPtr nodeHandle**
Description of variable

### **std::string robotName**
Description of variable

### **bool broadcast**
Description of variable

## Function Documentation
### **void insert**(float value, uint8_t* array):
Description of function
#### Expected Input, Range(s) of Input

#### Expected Outputs / Results, Range


### **void insert**(int value, uint8_t* array):
Description of function
#### Expected Input, Range(s) of Input

#### Expected Outputs / Results, Range


### **float parseFloat**(uint8_t* array):
Description of function
#### Expected Input, Range(s) of Input

#### Expected Outputs / Results, Range


### **int parseInt**(uint8_t* array):
Description of function
#### Expected Input, Range(s) of Input

#### Expected Outputs / Results, Range


### **void send**(BinaryMessage message):
Description of function
#### Expected Input, Range(s) of Input

#### Expected Outputs / Results, Range


### **void send**(std::string messageLabel, const messages::msg::VictorOut::SharedPtr victorOut):
Description of function
#### Expected Input, Range(s) of Input

#### Expected Outputs / Results, Range


### **void send**(std::string messageLabel, const messages::msg::TalonOut::SharedPtr talonOut):
Description of function
#### Expected Input, Range(s) of Input

#### Expected Outputs / Results, Range


### **void send**(std::string messageLabel, const messages::msg::Power::SharedPtr power):
Description of function
#### Expected Input, Range(s) of Input

#### Expected Outputs / Results, Range


### **void zedPositionCallback**(const messages::msg::ZedPosition::SharedPtr zedPosition):
Description of function
#### Expected Input, Range(s) of Input

#### Expected Outputs / Results, Range


### **void powerCallback**(const messages::msg::Power::SharedPtr power):
Description of function
#### Expected Input, Range(s) of Input

#### Expected Outputs / Results, Range


### **void talon1Callback**(const messages::msg::TalonOut::SharedPtr talonOut):
Description of function
#### Expected Input, Range(s) of Input

#### Expected Outputs / Results, Range


### **void talon2Callback**(const messages::msg::TalonOut::SharedPtr talonOut):
Description of function
#### Expected Input, Range(s) of Input

#### Expected Outputs / Results, Range


### **void talon3Callback**(const messages::msg::TalonOut::SharedPtr talonOut):
Description of function
#### Expected Input, Range(s) of Input

#### Expected Outputs / Results, Range


### **void talon4Callback**(const messages::msg::TalonOut::SharedPtr talonOut):
Description of function
#### Expected Input, Range(s) of Input

#### Expected Outputs / Results, Range


### **void zedImageCallback**(const sensor_msgs::msg::Image::SharedPtr inputImage):
Description of function
#### Expected Input, Range(s) of Input

#### Expected Outputs / Results, Range


### **std::string getAddressString**(int family, std::string interfaceName):
Description of function
#### Expected Input, Range(s) of Input

#### Expected Outputs / Results, Range


### **void printAddresses**():
Description of function
#### Expected Input, Range(s) of Input

#### Expected Outputs / Results, Range


### **void reboot**():
Description of function
#### Expected Input, Range(s) of Input

#### Expected Outputs / Results, Range


### **void broadcastIP**():
Description of function
#### Expected Input, Range(s) of Input

#### Expected Outputs / Results, Range


Change Log:
7/3/2022: Documentation was created
