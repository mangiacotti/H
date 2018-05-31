H1
by Scott Mangiacotti
Tucson, Arizona USA
May 2018


1	All based on AdaFruit GPS Hat and AdaFruit GPS class library and AdaFruit instructions for RPI on Windows IoT
2	See web link: https://learn.adafruit.com/adafruit-class-library-for-windows-iot-core/gps-class
3	Universal Windows application type in VS2017
4	Remote device (by RPI name) for debug
5	Windows IoT build 14393
6	Name: Golfy McGpsFace
7	Programmed for Blue Tee distance only. Design easily accommodate others
8	Programmed for Skyline Country Club, Tucson Arizona USA only. Design easily accommodate others
9	Visual Studio 2017 Community Edition, C# Universal Windows Platform project/solution


App notes and known issues
-The entire application, including Windows IoT core, crashed often in early development.
-Internet research lead to not providing enough power to the RPI and GPS HAT. 
-Needed replace the default power supply that comes with the RPI2 with one that provided more amperage.
-Not sure the amperage need but used an externally powered USB device with up to  8 amps.  I would guess it needs around 2.5 amps.
-Even with more power, the build crashes periodically and was unable to fully debug the root cause.
-I think it is related to the generation RPI that I am using. I cannot get a recent build of the Windows -IoT core to boot. This is why an older build is used here (14393)
