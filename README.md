# ansible-mongodb
This role installs and configures mongodb on Ubuntu machines.
Most parts of this ansible role are taken from Stouts.mongodb https://github.com/Stouts/Stouts.mongodb. Thanks for all 
your work!

Differences to the Stouts.mongodb role are:
- Docker support removed
- MMS support removed
- Minor fixes for the service startup, that caused problems in our setup