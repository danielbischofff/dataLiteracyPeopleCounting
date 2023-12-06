# dataLiteracyPeopleCounting


1. Technical side:
- we got to track Bluetooth via btmon from a linux bootable usb on all of our devices from 13 to 14 today (I can write a kind of protocol/todo list with all we did so that we make sure each one of us can replicate the process)

TODOS:
- try out playing with bluetoothctl so that it refreshes less often (around 1 or 2 per minute) . (currently 1 h takes 133 mb of storage, which is still an ok size)
- try finding Dani's Bluetooth device inside the data (Address: 98:50:2E:56:67:08) to see if it's automatically encrypted by his iPhone and know how the mac address encryption works (e.g. if we even find him, and if not, if we can somehow find out at what interval the addresses change and if we can even measure how long someone was at the mensa from the data from today)
- decide if we also want to try out wifi tracking (a friend which is pretty tech savy might help us to track all devices, not only the ones connected to the nearest hotspot. this would probably produce better estimates for the number of ppl as everybody has wifi on, as for Bluetooth it seems the majority is apple users and you cand find out more about the devices if you know how to interpret their certificates. This might also enable us to track people better if it works ) I will update you after I talk to my friend a bit longer on what software we can use if we want to do the switch

2. Research side:
!!! Big problem: if the Bluetooth(/wifi) chips on our laptops are different, it might be that they have different ranges, and therefore different capturing abilities. We might want to test this or only use 1 device before the data gathering process so that we don't introduce additional uncertainty.
- Dani and I thought about some additional measures:
A. try to count the number of people at tables each 30 mins to check/validate our number of devices measure
B. If we can measure the physical range in which we detect devices (because SSRI is not the perfect measure for spatial proximity) we can maybe better infer the number of ppl
C. (really high end) See if the range changes if there are a lot of devices (possible explanation that a lot of signals overwhelm our chip and change it's tracking ability) and maybe even use this interference to quantify how many people there are at the mensa

TODOS:
- Decide on exact tracking spot for the next days so that we sit in the same place and don't produce additional noise/biases

3. Organisatory points
TODOS
- Have a meeting with everybody this week to decide on the most pressing data gathering details before we start the official tracking operation
- Open GitHub and discuss all technical issues there
- (Suggestion) start estimating the workload with a chart like this (https://app.teamgantt.com/projects/gantt?ids=3762131, currently invited you but apparently only 3 ppl can join in the free version) so that we can better determine priorities and time ressources
