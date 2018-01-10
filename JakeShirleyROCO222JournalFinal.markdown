# **Jake Shirley ROCO 222 Lab Journal**

 28/09/2017
 **student no. 10522755**
## __*LAB 1 Introduction to GIT and hack a robot*__
### PART I First Markdown File
Markdown- Markdown is a markup language with plain ntext formatting syntax. It can therefore convert between text and HTML.
## Main Heading
### Sub Heading
#### Third indented sub-heading
## Bullet Points
* Use a multiplication sign to do this

### Numbered points
1. Simply just type 1.-n. to do this
2. etc
3. 

### Embedded Image
![alt text](https://camo.githubusercontent.com/5215e6fe0e2fc740eb8d91fe380287294fcacca5/68747470733a2f2f6f63746f6465782e6769746875622e636f6d2f696d616765732f79616b746f6361742e706e67)

### Emphasis
*Italics* Use a single * casing or _casing **Bold** Use a double ** casing or __casing

### Embedding Code

use three " ` " e.g.

```
#ifndef Full_step_h
#define Full_step_h
#include "Arduino.h" //Includes standard Arduino header files
```


### Links
[https://www.google.com] - use square brackets
[Google Search Engine](https://www.google.com) -for Masked Link use square brackets for name then regular brackets for link.
### Tables
| **Main** | **Second** | **Sum**  |
| -------- |:----------:| --------:|
|1         | 3          |   4      |
|2         | 2          |   4      |
|3         | 1          |   4      |

```
| **Main** | **Second** | **Sum**  |
| -------- |:----------:| --------:|
|1         | 3          |   4      |
|2         | 2          |   4      |
|3         | 1          |   4      |
```

### Terminal Commands
* ls - This function Lists all doucments and itmes conatined within the directory
* cd /tmp - This function places a document called "tmp" within the directory
* cd /$HOME - This comes back to the first file directory
* mkdir - This creates a directory
* echo "Hello" > hello.md - This creates a file called Hello.md and places it within the directory
* cat hello.md - This prints the text contained within the hello.md file within a newline
* cp hello.md hello-again.md - This creates a duplicate file for hello.md and renames it hello-again.md
* mv hello-again.md hello-hello.md - This renames hello-again.md to hello-hello.md
* rm hello.md - This deletes the file called hello.md
* rm -rf - This deletes all files
* cat/proc/cpuinfo - This indicates all CPU stats 


### __*PART II Hack into a Robot*__

___

## __*LAB 2 Build a DC Motor*__

### __*PART I Basic DC Motor*__

#### **What is a Brushed DC Motor?**
A brushed DC motor is a type of electric 	 motor designed to be ran by current 	 going through brushes. The DC motor 	 can only run in one direction due to the 	 motor only having two commutators. 	 Brushed DC motors are still used today 	 in cranes and rolling machines. 	 However, they are being replaced by 	 brushless motors as over time the 	 brushes wear down and require 	 replacement. The motor we are making 	 is a two-pole dc motor however if you 	 were to add more poles and make a 	 more complex motor you could easily 	 increase the speed and torque of the 	 motor. The no. coils can also determine 	 the motors efficiency, speed and torque. 	
![](https://github.com/JakeShirley170/Jake-Shirley-ROCO222-Journal/blob/master/images/motor.jpg?raw=true)
#### **How does the Motor Work?**

Our motor is two pole and therefore 	 has only two commutators. The first 	 brush will be placed onto one of the 	 commutators and the other brush on 	 the other commutator. We then connect the brushes to our power supply which is set at +12V.  When we turn on the power supply it sends current through the coils. This then generates a magnetic field around the armature. At this point the left side of the armature is pushed away from the left magnet and drawn to the right. This causes the rotation of the shaft. When the armature and magnetic field become horizontally aligned, the magnets repel and the commutator reverses the current flow and direction. Reversing the magnetic field. The shaft continues to rotate and will go back to its first position. The process will repeat 	 
until the power supply is turned off and when there is no current flowing. 	 ![](https://github.com/JakeShirley170/Jake-Shirley-ROCO222-Journal/blob/master/images/motor4.jpg?raw=true)
#### **Initial Construction and Testing**
We firstly set out by drawing a cross on the wooden
base to show where the centre of the base is. We the
screw down four paperclips to the base using the
washers and screws. We then bent the Paperclips at
90º angles. This created a stand for our shaft to sit
in and meant the magnets could be easily placed
next to the motor. We then took the cork and placed
the two thin nails into it creating the main body of
the shaft. We then took two small strips of copper
tape and stuck them onto the cork with a small
overlay sticking out. At this point we soldered one
end of the copper wire to the copper tape. We then
wrapped the copper wire around the cork 110 times
The remaining end of the wire was then soldered to the other piece of copper tape. We then creating the coil.
placed the shaft in between the gaps in the stand we made earlier. This meant the shaft
could rest self-supported and spin freely. Lastly, we got some thick wire and stripped the
ends off and spread out the ends of the wire, these were the brushes required to connect to the commutators.  Once these wires were connected to the power supply, we have fully built the two pole DC motor. 
#### **Alterations**
As you can see from the second video we were unable to identify mean frequency
points from our encoder. Therefore, I would make alterations from this current
design in order to test and calculate speed and rpm. If we were to have had multiple
coils in our design I believe that the signal would be stronger as the motor would
be turning off less due to the brushes going through more commutators making
the speed more even and steady. I would Also consider mounting the brushes so we
didn’t have to hold them. As we were making minor movements with our hands this
could have also affected our signal.
#### **Working project video links**
[Basic DC Motor Video Demonstration](https://www.youtube.com/watch?v=6xnyiSUlZJg)

[Basic DC Motor with encoder Video Link](https://www.youtube.com/watch?v=-jCI-Ce9XAk)
#### **Conclusion**
To conclude I found this assignment very interesting and I really enjoyed the
hands-on practicality to it. I felt that at times throughout the build we were
restricted by the components we had as they were very basic and simple. Although 
the task was to make a basic DC motor, I feel like the motor could have been
massively improved if we were given more copper wire, tape or a bigger cork.
However, because we were able to easily make a self-starting motor with relatively
few changes I can justify that the components given were suitable. If I was doing
this task again I would definitely make the brushes mounted so that we didn’t have
to hold them.

### __*PART II Improved DC Motor*__

#### **How deos our improved Motor Work?**
Our motor is four pole and has eight 	 commutators. The first brush will be 	 placed onto one of the commutators 	 and the other brush on the other 	 commutator. We then connect the 	 brushes to our power supply which is 	 set at +12V.  When we turn on the 	 power supply it sends current through 	 the coils. This then generates a 	 magnetic field around the armature.   	 At this point the left side of the 	 armature is pushed away from the left 	 magnet and drawn to the right. This 	 causes the rotation of the shaft. When 	 the armature and magnetic field 	 become horizontally aligned, the 	 magnets repel and the commutator 	 reverses the current flow and direction. 	 Reversing the magnetic field. The shaft 	 continues to rotate and will go back to 	 its first position. The process will repeat 	 
until the power supply is turned off and there is no current flowing. 	 
 
#### **Mount Design**

The diagram to the right represents all the parts we 3D printed for our mount for our motor. We set out  with the idea of creating a simple design that require  few components as possible. We also used a square ridged edge on all the parts so that they would initially  fit together without needing any glue. The two larger  holes represent where the main axle will sit. And the  two smaller holes show where we are going to add  the magnet. We also scaled the design to a certain size that gave the main shaft a good clearance  from the ground and sides of the mount. 

#### **Shaft and Coil design**
The image to the right is our final and complete design for the shaft including the coils and commutators. Our design included 4 coils so therefore we had to splits the commutator wheel into eight segments so that each coil had a +/- commutator. We also had to place each commutator opposite each other. Therefore, there was a break of two commutators between each pairing. We also attempted to make the coil casing as thin as possible so that the magnetic field could be close as possible to the magnets placed around the shaft. 

#### **Working project video links**
[Improved DC Motor]()
___

## __*LAB 3 Build an Incremental Encoder*__

19/10/2017

The task for our third assignment was to design and build a basic working incremental
encoder. We then had to use our results to calculate the rotational speed of the dc motor. 
#### **What is an Incremental Encoder?**
An incremental encoder converts rotational
motion to electrical signals. When the wheel
or disc spins, the encoder can emit data
through the infrared led into the
corresponding photo transistor. This can only
happen when the light travels though the slit.
The signals can alternate and be moulded to
your needs by changing your disc or wheel
with the addition of slits in certain places.
Our incremental encoder only has one
emitter and receiver however many encoder
use multiple LEDs to emit more complex
signals and data. 

#### **How does the circuit work?**
![Circuit design](https://github.com/JakeShirley170/Jake-Shirley-ROCO222-Journal/blob/master/images/14627805_1290431600996715_1259850235_n.jpg?raw=true)

Firstly, the circuit uses two channels one
requiring the infrared led and the other
requiring the phototransistor. We then use a 1k
resistor to drive the Infrared LED this then
follows up to the second channel and ends up at
ground. For the second channel, we use a 10k
resistor to drive the phototransistor which
receives the infrared signal from the infrared led
this also goes to ground. The circuit is powered
by 5V from the power supply. The Infrared Led
will constantly emit light but when the light
reaches the phototransistor this will pulse high
on the scope. whilst we were only using a single
slot disc the wave would not go low till the slit
met the LED and phototransistor. However, as
we increased the no. slits to 2 slits on the disc
the number of square waves that appeared on
the oscilloscope were doubled and the length of
each wave were halved. Therefore, the
frequency of pulses doubled as shown on the
waves below. 
#### **Disc designs**
![circuit](https://github.com/JakeShirley170/Jake-Shirley-ROCO222-Journal/blob/master/images/disc2.jpg?raw=true)

Shown above are the design we used for the discs on our assignment. We decided to use
large slots to ensure that the light would get through. When we added our second slot we
placed it directly opposite the first slot so that the length of the pulses would be identical, as
shown below. For our third slot, we added a smaller slot at the top of the disc just to test
measure the frequency and see if there was a difference in rotational speed.
#### **Wave Results** 
![circuit](https://github.com/JakeShirley170/Jake-Shirley-ROCO222-Journal/blob/master/images/scope2.jpg?raw=true)
#### **Speed Calculations**
To calculate the rotational speed of the dc motor we used the formula for Speed = distance/time=(frequency of pulses)/(no.slits) We ran the dc motor off the power supply at 1.5v exactly. Our units for speed were rps (rotations per second) this was due to us wanting to work out how many rotations the disc was doing off the dc motor we used the no. pulses on the oscilloscope and how many slits were in the disc. We used the measurement function on the oscilloscope to read the frequency of pulses.

| **No. slits on Disc** | **Frequency of Pulses** | **Calculation**  | **RPS** |
| --------------------- |:-----------------------:| ----------------:|---------|
|1                      |  66hz                   |   66/1           | 66rps   |
|2                      |  139hz                  |   139/2          | 69rps   |
|3                      |  206hz                  |   206/3          | 68rps   |

#### **Results**

We found that as we increased the no. slits on the disc the frequency of pulses on the
oscilloscope increased in proportionally. This ultimately lead to the dc motor speed (rps)
being stable and coming to similar and conclusive results as there was only a mere
difference of 3rps between our highest and lowest results. These minor discrepancies are
expected when turning the power supply back on as the supply will never be identical to its
previous level. 

#### **Working project video links**

[Basic DC Motor Video Link](https://www.youtube.com/watch?v=-jCI-Ce9XAk)

[Improved DC Motor Video Link]()
#### **Summary and Alterations**

To conclude the incremental encoder was a fairly-simple task and did not require too much
alterations to our design once the initial construction was complete. Our results also were as
roughly predicted and our rps stayed stable as we increased the no. of slots on the disc.
However, if I was going to carry out the same task again I would consider using an acrylic
based disc that’s was either laser cut or 3D printed to increase the accuracy of distance
between the slots on the disc. Also the size of the slots on the disc could be identical this
would mean that length of time the wave pulses off would be identical and accurate
throughout. 
___

## __*LAB 4 Motor Control With the Arduino*__

___

## __*LAB 5 Stepper Motors*__

23/11/2017

For our fifth assignment, we had to programme and code a Stepper Motor. We had
to programme it to run in 4 modes; Full-step, Double-step, Half-step and Microstep.
We used the Arduino and Arduino shield as the microcontroller required to do
this.

#### **What is a Stepper Motor?**
A Stepper Motor is a synchronous
electric motor that converts mechanical
rotations and positions from digital
pulses. A stepper motor is also a
variant of a brushless dc motor,
stepper motors can also be very
accurate in their positioning and are
often used in high precision equipment
such as laser cutters and 3D printers.
Stepper motors can come in different
sizes depending on the torque and
speed required by their application. For
example, a small stepper motor may be
required in a standard desk printer
however a larger more powerful motor
may be required on a factory
production line. Although in that case however a larger more powerful motor
may be required on a factory
production line.
![](https://github.com/JakeShirley170/Jake-Shirley-ROCO222-Journal/blob/master/images/stepper.gif?raw=true)
#### **How does a Stepper Motor work?** 
 
In order for the stepper motor to
turn the first coil facing the magnet
needs to have current running
through it in order to generate the
magnetic field for the magnet to
attract to. The top magnet therefore
is facing that electromagnet. At this
the second coil to the right (if going
clockwise) is turned on the and the
original coil is turned off the magnet
(rotor) is then attracted to the
second coil and will therefore turn
towards it. The A’ coil as shown in
the picture to the right shows an
inverted coil so that the south pole
magnet will attracted towards it. If 
the motor were to have more coils
and the magnetic rotor to have more
points the motor will run a lot
smoother than the basis one shown
to the right. More coils also enable
better and more accurate
positioning.
#### **Full Step Code**
Full Step Header Code:
```
#ifndef Full_step_h
#define Full_step_h
#include "Arduino.h" //Includes standard Arduino header files
class Full_step //Defines a class called “full_step”
{
Public: //accessible to the user
//declares and allows the user to input all of the variables we need for the system
Full_step(int DIR_A, int BRAKE_A, int PWM_A, int DIR_B, int BRAKE_B, int PWM_B);
void A_FORWARDS();
void A_BACKWARDS();
void A_DISABLE();
//declaring functions for system
void B_FORWARDS();
void B_BACKWARDS();
void B_DISABLE();
private:
int _DIR_A;
int _DIR_B;
_PWM_A; 
int _PWM_B; //declaring all the variables needed in the code 
int _BRAKE_A; //private means that the variables aren’t accessible to the user int _BRAKE_B; 
}; 
 
#endif 


```
Full Step Main Code:
```
#include "Full_step.h" //includes created header file
Full_step Full_step(12,9,3,13,8,11); //assigns pins to their respective variables
void setup() {
}
void loop() {
Full_step.A_FORWARDS(); Full_step.A_DISABLE();
Full_step.B_BACKWARDS(); Full_step.B_DISABLE();
Full_step.A_BACKWARDS(); Full_step.A_DISABLE()
Full_step.B_FORWARDS(); Full_step.B_DISABLE()
}

```
Full step source file:
```

#include "Arduino.h" //standard header files for arduino #include "Full_step.h" //includes our own header file 
 
Full_step::Full_step(int DIR_A, int BRAKE_A, int PWM_A, int DIR_B, int BRAKE_B, int PWM_B) 
 { 
pinMode(DIR_A, OUTPUT); //Sets pin as an output 
_DIR_A = DIR_A; 
pinMode(DIR_B, OUTPUT); //Sets pin as an output 
_DIR_B = DIR_B; 
pinMode(PWM_A, OUTPUT); //Sets pin as an output 
_PWM_A = PWM_A; 
pinMode(PWM_B, OUTPUT); //Sets pin as an output 
_PWM_B = PWM_B; 
pinMode(BRAKE_A, OUTPUT); //Sets pin as an output 
_BRAKE_A = BRAKE_A; 
pinMode(BRAKE_B, OUTPUT); //Sets pin as an output 
_BRAKE_B = BRAKE_B; 
} 
 
void Full_step::A_FORWARDS() 
{ 
digitalWrite(_BRAKE_A,LOW); //Lowers the breaks on A digitalWrite(_DIR_A, HIGH); //Set direction to clockwise analogWrite(_PWM_A, 255); //Sets maximum speed delay(10); //short delay 
} 
 
void Full_step::B_FORWARDS() 
{ 
digitalWrite(_BRAKE_B,LOW); //Lowers the breaks on B digitalWrite(_DIR_B, LOW); //Set direction to clockwise analogWrite(_PWM_B, 255); //Sets maximum speed delay(10); //short delay 
 } 
void Full_step::A_BACKWARDS() 
 { 
digitalWrite(_BRAKE_A,LOW); //Lowers the breaks on A digitalWrite(_DIR_A, LOW); //Set direction to anti_clockwise analogWrite(_PWM_A, 255); //Sets maximum speed delay(10); //short delay 
} 
 
void Full_step::B_BACKWARDS() 
{ 
digitalWrite(_BRAKE_B,LOW); //Lowers the breaks on B digitalWrite(_DIR_B, HIGH); //Set direction to anti_clockwise analogWrite(_PWM_B, 255); //Sets maximum speed delay(10); //short delay 
} 
 
void Full_step::A_DISABLE() 
 { 
digitalWrite(_BRAKE_A,HIGH); //Engages the breaks on A analogWrite(_PWM_A, 0); //Sets minimum speed delay(1); //short delay 
 } 
void Full_step::B_DISABLE() 
 
{ 
digitalWrite(_BRAKE_B,HIGH); //Engages the breaks on B analogWrite(_PWM_B, 0); //Sets minimum speed delay(1); //short delay 

```
#### **Double Step Code**
Double Step Header File
```
#ifndef Double_step_h 
#define Double_step_h 
 
#include "Arduino.h"    //Includes standard Arduino header files 
 
class Double_step     //Defines a class called “Double_step” 
{ 
   public:        //accessible to the user 
    //declares and allows the user to input all of the variables we need for the system  
    Double_step(int DIR_A, int BRAKE_A, int PWM_A, int DIR_B, int BRAKE_B, int PWM_B, int wait); 
     
    void AB_FWDS();      
    void AB_BWDS();     
    void B_FWDS_A_BWDS();     
    void B_BWDS_A_FWDS(); 
                            //declaring functions for system     
    void A_DISABLE(); 
    void B_DISABLE(); 
   
   private: 
   int _DIR_A;     
   int _DIR_B;    
   int _PWM_A; 
   int _PWM_B;      //declaring all the variables needed in the code    
   int _BRAKE_A;    //private means that the variables aren’t accessible to the user    
   int _BRAKE_B;    
   int _wait; 
  }; 
 

```
Double Step Main Code
```
#include "Double_step.h" //includes created header file 
 
Double_step Double_step(12,9,3,13,8,11,10); //assigns pins to their respective variables 
 
void setup() { 
} 
 
void loop() { 
Double_step.B_FWDS_A_BWDS(); Double_step.B_DISABLE(); 
Double_step.AB_FWDS(); Double_step.A_DISABLE(); 
Double_step.B_BWDS_A_FWDS(); Double_step.B_DISABLE(); 
Double_step.AB_BWDS(); Double_step.A_DISABLE(); 
} 

```
Double Step Source Code
```
   #include "Arduino.h"    //standard header files for arduino 
	   #include "Double_step.h"   //includes our own header file 	 
    	 
  Double_step::Double_step(int DIR_A, int BRAKE_A, int PWM_A, int DIR_B, int BRAKE_B, int PWM_B, int wait) 
	  { 	 
	    pinMode(DIR_A, OUTPUT);   //Sets pin as an output  	 
    _DIR_A = DIR_A;    
    pinMode(DIR_B, OUTPUT);    //Sets pin as an output 
	    _DIR_B = DIR_B; 	 
	    pinMode(PWM_A, OUTPUT);    //S 	ets pin as an output 
    _PWM_A = PWM_A;     
	    pinMode(PWM_B, OUTPUT);     //Sets pin as an output 	 
	    _PWM_B = PWM_B 	    
	    pinMode(BRAKE_A, OUTPUT);  //Sets pin as an output 	 
    _BRAKE_A = BRAKE_A; 
	    pinMode(BRAKE_B, OUTPUT);   //Sets pin as an outpu 	t 
	    _BRAKE_B = BRAKE_B; 	 
   _wait = wait;  
 
  } 
  	 
	 void Double_step::AB_FWDS() 	 
   {                      
    digitalWrite(_BRAKE_A,LOW);  //Lowers the breaks on A   	     digitalWrite(_DIR_A, HIGH);  //Set direction to clockwise 	     analogWrite(_PWM_A, 255); 	    //Sets maximum speed 
     
    digitalWrite(_BRAKE_B,LOW);  //Lowers the breaks on B  	     digitalWrite(_DIR_B, LOW);   //Set direction to clockwise 	     analogWrite(_PWM_B, 255);    //Sets maximum speed 	 
     
	    delay(_wait);   //short delay 	 
	   } 	 
    
 
   void Double_step::B_FWDS_A_BWDS() 
	  { 	 
    digitalWrite(_BRAKE_A,LOW);   //Lowers the breaks on A 	     digitalWrite(_DIR_A, LOW);    //Set direction to anti_clockwise     analogWrite(_PWM_A, 255);     //Sets maximum speed     	 
                             	 
    digitalWrite(_BRAKE_B,LOW);  //Lowers the breaks on B  	     digitalWrite(_DIR_B, LOW);   //Set direction to clockwise     analogWrite(_PWM_B, 255);    //Sets maximum speed 	     delay(_wait);    //short delay 	   }  
 
   
	    void Double_step::AB_BWDS() 	 
	  { 	 
    digitalWrite(_BRAKE_A,LOW);   //Lowers the breaks on A     digitalWrite(_DIR_A, LOW);    //Set direction to anti_clockwise 	     analogWrite(_PWM_A, 255);     //Sets maximum speed 	 
 	 
    digitalWrite(_BRAKE_B,LOW);  //Lowers the breaks on B      digitalWrite(_ 	DIR_B, HIGH);   //Set direction to anti_clockwise     analogWrite(_PWM_B, 255);    //Sets maximum speed 	 
     
 
    delay(_wait);   //short delay 
     	   } 	 
  void Double_step::B_BWDS_A_FWDS() 
	  { 	 
    digitalWrite(_BRAKE_A,LOW);  //Lowers the breaks on A   	     digitalWrite(_DIR_A, HIGH);  //Set direction to clockwise 	     analogWrite(_PWM_A, 255);    //Sets maximum speed   
                                  
    digitalWrite(_BRAKE_B,LOW);  //Lowers the breaks on B 	     digitalWrite(_DIR_B, HIGH);  //Set direction to 	 anti_clockwise 
    analogWrite(_PWM_B, 255);    //Sets maximum speed     delay(_wait);   //short delay 	     delay(1);  //short delay  

```
#### **Half Step Code**
Half Step Header
```
#ifndef Half_step_h 
#define Half_step_h 
#include "Arduino.h"    //Includes standard Arduino header files 
 
class Half_step     //Defines a class called “Double_step” 
{ 
   public:        //accessible to the user 
    //declares and allows the user to input all of the variables we need for the system  
    Half_step(int DIR_A, int BRAKE_A, int PWM_A, int DIR_B, int BRAKE_B, int PWM_B, int wait); 
     
    void AB_FWDS();      void AB_BWDS();     void B_FWDS_A_BWDS();     void B_BWDS_A_FWDS(); 
                            //declaring functions for system     void A_FORWARDS();  
    void A_BACKWARDS(); 
     
    void B_FORWARDS();     void B_BACKWARDS();         void A_DISABLE(); 
    void B_DISABLE(); 
   
   private: 
   int _DIR_A;     int _DIR_B;    int _PWM_A; 
   int _PWM_B;      //declaring all the variables needed in the code    int _BRAKE_A;    //private means that the variables aren’t accessible to the user    int _BRAKE_B;    int _wait; 
  }; 
 #endif 

```
Half Step Main
```
#include "Half_step.h"  //includes created header file 
Half_step Half_step(12,9,3,13,8,11,10); //assigns pins to their respective variables  void setup() { 
} 
void loop() { 
  Half_step.A_FORWARDS();      Half_step.A_DISABLE(); //Briefly enable a single coil 
  Half_step.B_BWDS_A_FWDS();   Half_step.B_DISABLE(); //Briefly enable two adjacent coils   Half_step.B_BACKWARDS();     Half_step.B_DISABLE(); //repeated with all coils... 
  Half_step.AB_BWDS();         Half_step.A_DISABLE(); 
  Half_step.A_BACKWARDS();     Half_step.A_DISABLE();  
  Half_step.B_FWDS_A_BWDS();   Half_step.B_DISABLE(); 
  Half_step.B_FORWARDS();      Half_step.B_DISABLE(); 
  Half_step.AB_FWDS();         Half_step.A_DISABLE(); } 
```
Half Step Source
```
  #include "Arduino.h"    //standard header files for arduino 	 
	   #include "Half_step.h"   //includes our own header file 	 
    
 
  Half_step::Half_step(int DIR_A, int BRAKE_A, int PWM_A, int DIR_B, int BRAKE_B, int PWM_B, int wait) 
	  { 	 
	    pinMode(DIR_A, OUTPUT);   //Sets pin as an output  	 
    _DIR_A = DIR_A;    
	    pinMode(DIR_B, OUTPUT);    //Sets pin as an output 	 
    _DIR_B = DIR_B; 	         pinMode(PWM_A, OUTPUT);    //Sets pin as an outpu 	t 
    _PWM_A = PWM_A;     
	    pinMode(PWM_B, OUTPUT);     //Sets pin as an output 	 
	    _PWM_B = PWM_B 	     
	    pinMode(BRAKE_A, OUTPUT);  //Sets pin as an output 	 
    _BRAKE_A = BRAKE_A; 
	    pinMode(BRAKE_B, OUTPUT);   //Sets pin as an output 	 
    _BRAKE_B = B RAKE_B;    _wait = wait; 
 
     
	  } 	 
  	 
 void Half_step::AB_FWDS() 
   {                       
    	 
    digitalWrite(_BRAKE_A,LOW);  //Lowers the breaks on A   	     digitalWrite(_DIR_A, HIGH);  //Set direction to clockwise     analogWrite(_PWM_A 	, 255);    //Sets maximum speed     digitalWrite(_BRAKE_B,LOW);  //Lowers the breaks on B  	     digitalWrite(_DIR_B, LOW);   //Set direction to clockwise  
    analogWrite(_PWM_B, 255);    //Sets maximum speed 
     	 
	    delay(_wait);   //short delay 	 
     
 
   } 
    	 
	   void Half_step::B_FWDS_A_BWDS() 	 
  { 
    digitalWrite(_BRAKE_A,LOW);   //Lowers the breaks on A 	     digitalWrite(_DIR_A, LOW);    //Set direction to anti_clockwise 	     analogWrite(_PWM_A, 255);     //Sets maximum speed                              
    digitalWrite(_BRAKE_B,LOW);  //Lowers the breaks on B      digitalWrite(_DIR_B, LOW);   //Set direction to clockwise 	     analogWrite(_PWM_B, 255);    //Sets maximum speed 	     delay(_wait);    //short delay  
     
	  }  	 
   	 
    void Half_step::AB_BWDS() 
	  { 	 
    digitalWrite(_BR 	AKE_A,LOW);   //Lowers the breaks on A     digitalWrite(_DIR_A, LOW);    //Set direction to anti_clockwise 	     analogWrite(_PWM_A, 255);     //Sets maximum speed     digitalWrite(_BRAKE_B,LOW);  //Lowers the breaks on B  	     digitalWrite( _DIR_B, HIGH);   //Set direction to anti_clockwise     analogWrite(_PWM_B, 255);    //Sets maximum speed   
    delay(_wait);   //short delay   
  	 
 	 

```


Micro Step
```
#define IN1  8
#define IN2  9
#define IN3  10
#define IN4  11
int Steps = 0;
boolean Direction = true;// gre
unsigned long last_time;
unsigned long currentMillis ;
int steps_left=4095;
long time;
void setup()
{
Serial.begin(115200);
pinMode(IN1, OUTPUT); 
pinMode(IN2, OUTPUT); 
pinMode(IN3, OUTPUT); 
pinMode(IN4, OUTPUT); 
// delay(1000);

}
void loop()
{
  while(steps_left>0){
  currentMillis = micros();
  if(currentMillis-last_time>=1000){
  stepper(1); 
  time=time+micros()-last_time;
  last_time=micros();
  steps_left--;
  }
  }
   Serial.println(time);
  Serial.println("Wait...!");
  delay(2000);
  Direction=!Direction;
  steps_left=4095;
}

void stepper(int xw){
  for (int x=0;x<xw;x++){
switch(Steps){
   case 0:
     digitalWrite(IN1, LOW); 
     digitalWrite(IN2, LOW);
     digitalWrite(IN3, LOW);
     digitalWrite(IN4, HIGH);
   break; 
   case 1:
     digitalWrite(IN1, LOW); 
     digitalWrite(IN2, LOW);
     digitalWrite(IN3, HIGH);
     digitalWrite(IN4, HIGH);
   break; 
   case 2:
     digitalWrite(IN1, LOW); 
     digitalWrite(IN2, LOW);
     digitalWrite(IN3, HIGH);
     digitalWrite(IN4, LOW);
   break; 
   case 3:
     digitalWrite(IN1, LOW); 
     digitalWrite(IN2, HIGH);
     digitalWrite(IN3, HIGH);
     digitalWrite(IN4, LOW);
   break; 
   case 4:
     digitalWrite(IN1, LOW); 
     digitalWrite(IN2, HIGH);
     digitalWrite(IN3, LOW);
     digitalWrite(IN4, LOW);
   break; 
   case 5:
     digitalWrite(IN1, HIGH); 
     digitalWrite(IN2, HIGH);
     digitalWrite(IN3, LOW);
     digitalWrite(IN4, LOW);
   break; 
     case 6:
     digitalWrite(IN1, HIGH); 
     digitalWrite(IN2, LOW);
     digitalWrite(IN3, LOW);
     digitalWrite(IN4, LOW);
   break; 
   case 7:
     digitalWrite(IN1, HIGH); 
     digitalWrite(IN2, LOW);
     digitalWrite(IN3, LOW);
     digitalWrite(IN4, HIGH);
   break; 
   default:
     digitalWrite(IN1, LOW); 
     digitalWrite(IN2, LOW);
     digitalWrite(IN3, LOW);
     digitalWrite(IN4, LOW);
   break; 
}
SetDirection();
}
} 
void SetDirection(){
if(Direction==1){ Steps++;}
if(Direction==0){ Steps--; }
if(Steps>7){Steps=0;}
if(Steps<0){Steps=7; }
}
```
#### **Working project video links**
[Half Step](https://www.youtube.com/watch?v=-ckDqysjml4)

[Full Step](https://www.youtube.com/watch?v=CZA4ggSR-9A)

[Double Step](https://www.youtube.com/watch?v=aJS108vwhho)

[Micro Step](https://www.youtube.com/watch?v=S9lQOVmJet8)

#### **Conclusion**
To conclude I found this project very interesting to complete as well as s time consuming. Learning to programme the motor initially after wiring it up to the Arduino Shield correctly, took a large sum of our overall time we had to complete the project. I also found that once I had a basic knowledge of the code required to the make the motor function correctly I was able to complete each of the stages quicker.   
___

## __*LAB 6 Robotic Arm Project Sevro Control*__

___

## __*LAB 7 Robotic Arm Project ROS*__
