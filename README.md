# SafeCabsApp

After a late night Stand-Up comedy at Shephard Audi Bangalore, all the Males and Females are
trying to leave the venue and booking their cabs via SafeCabs at the same time. However, to make
sure that all the males and females are safe, the software developers at SafeCabs came up with an
algorithm whereby either a SafeCab can have all Females or all Males or two Females and two
Males. All other combinations may lead to an unsafe passenger.
Your task as the SafeCabs developer is to solve this problem with proper modularization and
making it thread safe at the same time. Once an acceptable combination of riders is possible, ride
should start.


- Register Cab Requestors
- Allow only Restered Cab Requestors to request and board the cab
- Consider the all the ride requestors as threads when requesting a cab.
- The Cab which is available first should move first
- Cab Driver will not start ride untill it has all 4 passengers
- All the cab requests should wait untill a new cab appears
- Consider SafeCabs is only operational near Shephard Audi Bangalore, so cab distance can be
ignored. All the available cabs can be used fulfill the cab requests.
- Write Unit Test Cases for as many critical sections of your code as possible.
