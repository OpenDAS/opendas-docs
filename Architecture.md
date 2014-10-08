### Architecture ###

OpenDAS architecture is based on four components \:
* server which allows configuration of \:
    * stations
    * datas with static or intern type
    * EAN128 structures
    * consumers definition
* universal driver transmission protocols 
* stations
* message manager
* consumers 

Indeed, clients are graphical user interfaces based on a MVC architecture communicating with the DAS server thanks to various requests managed with ActiveMQ.

![OpenDAS Architecture](http://opendas.org/raw-attachment/wiki/OpendasArchitecture/OpenDAS%20architecture.png)



