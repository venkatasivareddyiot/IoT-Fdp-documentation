# IoT-Fdp-documentation
IoT Documentation
This is all about iot documentation and all the things that you learn in the training sessions
![GitHub Logo](https://dl1.cbsistatic.com/i/2019/10/25/3d1ad463-d007-4220-bba7-f22588292444/c1d0cff614ceb63ac7bbf23f9323d189/imgingest-7008501752514407747.png)
<img src='battery.jpg' alt='battery' />
## What is IOT?
    IoT is simply the network of interconnected things/devices which are embedded with sensors, software, network connectivity and necessary electronics that enables them to collect and exchange data making them responsive.
## IOT Uses
    Everyday Life
    Health Care
    Agriculture
    Industrial Automation
    Disaster management
    Smart cities
## The things that we are used in this sessions:
Led,LDR,Servo Motor,LCD,MIT,Thingspeak,Blynk,Cloud.
# LED
    A light-emitting diode (LED) is a semiconductor light source that emits light when current flows through it. Electrons in the semiconductor recombine with electron holes, releasing energy in the form of photons. The color of the light (corresponding to the energy of the photons) is determined by the energy required for electrons to cross the band gap of the semiconductor.[5] White light is obtained by using multiple semiconductors or a layer of light-emitting phosphor on the semiconductor device.
## How does the Light Emitting Diode work?
    The light emitting diode simply, we know as a diode. When the diode is forward biased, then the electrons &
holes are moving fast across the junction and they are combining constantly, removing one another out. Soon
after the electrons are moving from the n-type to the p-type silicon, it combines with the holes, then it
disappears. Hence it makes the complete atom & more stable and it gives the little burst of energy in the form
of a tiny packet or photon of light.
## Symbol of an LED:

## I-V characteristics:
    There are different types of light emitting diodes are available in the market and there are different LED
characteristics which include the color light, or wavelength radiation, light intensity. The important
characteristic of the LED is color. In the starting use of LED, there is the only red color. As the use of LED is
increased with the help of the semiconductor process and doing the research on the new metals for LED, the
different colors were formed.

## Types of LED'S
    Through hole LED
    SMD LED
    Bi colour LED
    Tri colour LED(RGB)
# Arduino
    The Arduino UNO is the best board to get started with electronics and coding. If this is your first experience tinkering with the platform, the UNO is the most robust board you can start playing with. The UNO is the most used and documented board of the whole Arduino family.
    
## Installing on Arduino software:




### Arduino with LED
int led=13;
void main()
{
pinMode(led,13);
}
void loop()
{
digitalWrite(13,HIGH);
delay(500);
digitalWrite(13,LOW);
delay(500);
}

