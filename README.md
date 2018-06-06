# HSCOD_final_assignment
Audio_coprocessor-Final assignment for the HSCOD in SDU Sonderborg

The audio-processor is made from an IP-block connect to the zynqprocessor of a zedboard, and include the interface to the
adau1761 chip from Stefan Scholl (https://kluedo.ub.uni-kl.de/frontdoor/deliver/index/docId/4034/file/zedboard_audio_doc.pdf).

The function of the processor are: -a sine wave with changeable frequency
                                   -a satooth wave with changeable frequency
                                   -echo what ever comes in the line_in with changeable delay
                                   -and just a loopback
                                   
The user can choose which channel should be use (left,right or both)

by Barne Carstensen

