# Projects
All Projects



##########################################################################
#########################################################################
network-arch

This Network diagram shoes the architecture of the internal network and how things communicate The first section is
##################    The entire Infrastructure uses a    #####################
######################        10.0.0.0/8 IP address        ###################

See below details for zone / data center specific IP address information

SITE-A-IP: 10.5.0.0/16

VLAN / SUBNET INFORMATION


Enterprise Admin Block -        VLAN 5 -             10.5.5.0/24
Server Block -                  VLAN 10 -            10.5.10.0/24
Application Block -             VLAN 15 -            10.5.15.0/24
Dev/Staging Block -             VLAN 20 -            10.5.20.0/24
IT Support Block -              VLAN 25 -            10.5.25.0/24
Visitors/Quarantine -           VLAN 30 -            10.5.30.0/24
Enrollment/Remote Block -       VLAN 240 -           10.5.240.0/20

Management Subnet -                                  10.5.0.0/16
Storage Network -                                    1.1.1.0/24
DMZ Network -                                        172.16.0.0/24

SITE-B-IP: 10.10.0.0/16 

VLAN / SUBNET INFORMATION



Enterprise Admin -              VLAN 5 -             10.10.5.0/24
Server Block -                  VLAN 10 -            10.10.10.0/24
Application Block -             VLAN 15 -            10.10.15.0/24
Dev/Staging Block -             VLAN 20 -            10.10.20.0/24
IT Support Block -              VLAN 25 -            10.10.25.0/24
Visitors/Quarantine -           VLAN 30 -            10.10.30.0/24
Enrollment/Remote Block -       VLAN 240 -           10.10.240.0/20

Management Subnet -                                  10.10.0.0/16
Storage Network -                                    1.1.1.0/24
DMZ Network -                                        172.16.0.0/24

SITE-C-IP: 10.15.0.0/16

****VLAN / SUBNET INFORMATION****

Enterprise Admin -               VLAN 5 -            10.15.5.0/24
Server Block -                   VLAN 10 -           10.15.10.0/24
Application Block -              VLAN 15 -           10.15.15.0/24
Dev/Staging Block -              VLAN 20 -           10.15.20.0/24
IT Support Block -               VLAN 25 -           10.15.25.0/24
Visitors/Quarantine -            VLAN 30 -           10.15.30.0/24
Enrollment/Remote Block -        VLAN 240 -          10.15.240.0/20

Management Subnet -                                  10.15.0.0/16
Storage Network -                                    1.1.1.0/24
DMZ Network -                                        172.16.0.0/24
DMZ Network - 172.16.0.0/24

SITE-D-IP: 10.20.0.0/16

****VLAN / SUBNET INFORMATION****

Enterprise Admin -                VLAN 5 -           10.20.5.0/24
Server Block -                    VLAN 10 -          10.20.10.0/24
Application Block -               VLAN 15 -          10.20.15.0/24
Dev/Staging Block -               VLAN 20 -          10.20.20.0/24
IT Support Block -                VLAN 25 -          10.20.25.0/24
Visitors/Quarantine -             VLAN 30 -          10.20.30.0/24
Enrollment/Remote Block -         VLAN 240 -         10.20.240.0/20

Management Subnet -                                  10.20.0.0/16
Storage Network -                                    1.1.1.0/24
DMZ Network -                                        172.16.0.0/24


SITE-E-IP: 10.25.0.0/16

VLAN / SUBNET INFORMATION


Enterprise Admin -                VLAN 5 -           10.25.5.0/24
Server Block -                    VLAN 10 -          10.25.10.0/24
Application Block -               VLAN 15 -          10.25.15.0/24
Dev/Staging Block -               VLAN 20 -          10.25.20.0/24
IT Support Block -                VLAN 25 -          10.25.25.0/24
Visitors/Quarantine -             VLAN 30 -          10.25.30.0/24
Enrollment/Remote Block -         VLAN 240 -         10.25.240.0/20

Management Subnet -                                  10.25.0.0/16
Storage Network -                                    1.1.1.0/24
DMZ Network -                                        172.16.0.0/24

Enterprise Admin - VLAN 5 - 10.25.5.0/24 
Server Block- VLAN 10 - 10.25.10.0/24 
Application Block - VLAN 15 - 10.25.15.0/24 
Dev/Staging Block - VLAN 20 - 10.25.20.0/24 
IT Support Block - VLAN 25 - 10.25.25.0/24 
Visitors/Quarantine - VLAN 30 - 10.25.30.0/24 
Enrollment/Remote Block - VLAN 240 - 10.25.240.0/20
Management Subnet - 10.25.0.0/16 Storage 
Network - 1.1.1.0/24 
DMZ Network - 172.16.0.0/24
