homeassistant-enigma-player for vu+ satellite-boxes e.g. Duo2, SoloSE ...

... HomeAssistant 0.75.x  --> copy enigma.py to /config/custom_components/media_player/enigma.py

sample part of configuration.yaml


media_player:                                                                                                                                                     
  - platform: enigma                                                                                                                                              
    host: 192.168.x.x                                                                                                                                           
    port: 23                                                                                                                                                      
    username: root                                                                                                                                                
    password: !secret                                                                                                                                         
    timeout: 20   
