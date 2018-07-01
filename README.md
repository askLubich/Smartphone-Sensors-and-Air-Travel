# Smartphone Sensors and Air Travel

In 2015 I was curious what the sensors of a typical smartphone (a Nexus 5 in this case) would pick up when we fly on an airplane and whether the data would make any sense. It turned out the data does make sense and is pretty accurate. 

I used my phone to record acceleration, barometer, compass and GPS data as well as sound level. Obtaining GPS data was problematic, because receiving satellite information is hard inside a flying aluminum tube. Therefore, GPS data is a bit blocky.

### Results

The main results are summarized in the figure below:

![alt text](flight.png "sensor data summary")

Amongst other things, once can clearly identify the initial acceleration during take off and the subsequent ascent. Similarly, the deceleration during landing is visible. 

Comparing acceleration and sound level during take off (figure below), we can see the noise increasing due to the engines spooling up, followed by an acceleration of up to 3 ms/s^2. 

![alt text](Plots/TO.png "take off summary")

The reverse pattern is visible during landing:

![alt text](Plots/LND.png "landing summary")


### Prerequisites

* Python 2.7
* Jupyter Notebook
* Packages:
    * matplotlib
    * numpy
    * scipy
* Inkscape for minor touchups of a plot

### Reddit Posts

I shared this visualization on [/r/dataisbeautiful](https://www.reddit.com/r/dataisbeautiful/comments/3dg2ek/exploiting_smart_phone_sensors_flying_an_airplane/).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.