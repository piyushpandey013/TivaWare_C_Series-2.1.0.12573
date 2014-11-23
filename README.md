TivaWare_C_Series-2.1.0.12573
=============================

HASC project Repocitory

## Prerequisites:

> 1) Kivy
> 2) launchad drivers for the Tiva C Launchpad 1294

## There are two options to run the program on the 1294 launchpads
> 1) After you've installed Keil microvision, and the Tiva launchpad, you can download this repository, and replace this
> folder inside the "C:\ti" like this:
>
>      C:\ti\TivaWare_C_Series-2.1.0.12573
>
> 2) You can download this repository, and only take the next two folders (cc3000 & ek-tmrc1294xl-boost-cc3000):
>
>      TivaWare_C_Series-2.1.0.12573\cc3000
>
>      TivaWare_C_Series-2.1.0.12573\examples\boards\ek-tm4c1294xl-boost-cc3000
>
> and replace them in the following paths:
>
>      C:\ti\TivaWare_C_Series-2.1.0.12573\cc3000
>
>      C:\ti\TivaWare_C_Series-2.1.0.12573\examples\boards\ek-tm4c1294xl-boost-cc3000
>
## GUI (Graphical User Interface)
> the main GUI file (br_gui.py) is located in 
>
> TivaWare_C_Series-2.1.0.12573/gui.
>
> When you run the GUI make sure your computer and the Tiva C Launchpad are connected to the same network, and that you know
> the IP address of your cc3000 boosterpack after it has connected to the internet
> To find out the IP address of the cc3000, you can open a serial connection while you turn on the Tiva C Launchpad, and
> the IP address will be displayed on the serial port.
