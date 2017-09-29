# BinghamtonU-ICS-Testbed
Set of ICS Testbed network captures during programming, system startup, and system operation

This repository contains a collection of industrial control system (ICS) network captures for the ICS testbed at Binghamton University. The various devices and their network connections are portrayed in the image file, BU_ICS_TestbedLayout. The testbed emulates a power generation plant and is dsecribed in detail in the paper:

E. Korkmaz, A. Dolgikh, M. Davis, V. Skormin. “Industrial Control Systems Security Testbed”, Annual Symposium on Information Assurance, 2016.

When referring to these network data captures in research works, we ask that you please cite the paper:

E. Korkmaz, M. Davis, A. Dolgikh, V. Skormin, "Detection and Mitigation of Time Delay Injection Attacks on Industrial Control Systems with PLCs," in Mathematical Methods, Models, and Architectures for Computer Network Security, Warsaw, 2017. 


The IP addresses for the testbed networked devices are:
IP Address			  |	  Device Name
__________________|__________________________________________________
192.168.200.245		|	  Allen-Bradley ControlLogix 1756 5561 Controller
192.168.200.241		|	  Allen-Bradley FLEX I/O 1794 IE4XOE2
192.168.200.240		|	  Allen-Bradley PowerFlex 1.5HP AC Drive
192.168.200.145		|	  Allen-Bradley PowerFlex 0.5HP AC Drive
192.168.200.140		|	  Allen-Bradley Micro850 PLC 2080-LC50-24QWB
192.168.200.133		|	  Programming Station Computer

Description of pcap Contents: All files are created by capturing all ControlLogix PLC traffic and RSLinx traffic on the switch. 

DevicePluggedIn_RunSequenceStartStop - 
This file contains the network capture showing the various devices connecting to the industrial network, followed by starting system operations and then turning off the system.

ProgramPLC - 
This file contains a network capture of the programming station programming the PLC with ladder logic.

RSLinx_BrowseNetworkDevices -
Network capture of RSLinx searching network for devices and information about devices. 
