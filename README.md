at-command-set
==============

ESP8266 AT+ Command Set

Few of the commands Listed below have an Inquiry Mode and Test Mode. 
Inquiry Mode will be executed with a ? at the end of the command "AT+CWMODE?" this will return the current status of the Module i.e. CWMODE=3
Test Mode commands will be exicuted with an =? at the end of a command "AT+CWMODE=?" this will return the possible parameters input i.e. 1=Sta, 2=AP, 3=both 

The commands entered has a <CR> at end so do not forget to add a <CR> or else there will be no output.

I have aggregated the below list from nurdspace.nl as well as electrodrgon.com. Please visit these links for further information

Commands         Description                        Type         Reply          Set/Execute             Parameters                   Examples

AT               generic cmd                        basic        OK             -                       -                            -   
AT+RST           Resets the mod                     basic        Module info    -                       -                            AT+RST 
AT+GMR           returns the current Fw version     basic        Fw Version     -                       -                            -
AT+CWMODE        Wifi Mode Set                      Wifi         Mode SET       AT+CWMODE=<Mode>        Mode 1=Sta, 2=AP, 3=both     AT+CWMODE=2
AT+CWLAP         Lists all available AP             Wifi         list of AP     AT+CWLAP                -                            AT+CWLAP
AT+CWJAP         Joins an Access Point              Wifi         OK             AT+CWJAP=<ssid>,<pwd>   Your Wifi SSID and Password  AT+CWJAP=<test>,<123456789>
AT+CWQAP         Quits the Access Point             Wifi                        AT+CWQAP                -                            AT+CWQAP
AT+CWSAP         Set Mod Access Point parameters    Wifi                        AT+CWSAP=<ssid>,<pwd>,  desired SSID,Password,       
                                                                                <chl>,<ecn>             channel, encryption
AT+CWLIF         Check join device IP               Wifi                        AT+CWLIF                -                            AT+CWLIF
AT+CIPSTATUS     get conn status                    TCP/IP       <id>,<type>    AT+CIPSTATUS            -                          
                                                                 <addr>,<port>

Will add rest Soon !
