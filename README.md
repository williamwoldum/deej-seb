# Installation
1. Tryk på `Code -> Download Zip` og pak zip-filen ud
2. Gem `deej` mappen et sted på din pc (`C:\Program Files` er et udmærket sted)
3. Lav et shortcut til `deej\deej.exe` og flyt genvejen til `%APPDATA%\Microsoft\Windows\Start Menu\Programs\Startup`
4. Sæt enheden i din foretrukne usb-port (det er "besværligt" at ændre port senere, så vælg en permanent port)
5. Åben `Device manager / Ports (COM & LPT)` og aflæs hvilken COM-port enheden `CH340` er tilsluttet
6. Åben `deej\config.yaml` og ændre værdien af `com_port` til den aflæste værdi fra forrige trin (husk at gemme filen)
7. Du kan nu starte `deej\deej.exe`, hvis alt er gået efter planen burde du i en ny fil `deej\logs\deej-latest-run.txt` bl.a. gerne kunne aflæse `Detected sliders	{"amount": 5}`, desuden burde potentiometerne nu virke 
    - Hvis noget er gået galt er COM-porten nok forkert
    - Alternativt genstart `deej\deej.exe` (kan aflsuttes vi joblisten)
    - Hvis den klager over "serial port busy" så prøv at genstarte din pc med enheden tilsluttet

# Konfiguration
Du kan lege med `deej\config.yaml` som du har lyst til.\
Det er her du kan ændre hvad potentiometerne kontrollerer.

Du kan læse mere her https://github.com/omriharel/deej                  
                                                                          
                                                                    
                                                                                                    
                                     ...                                                            
                                    :::::                                                           
                                   ****++=                                                          
                                   #%%###*                                                          
                                   %%%%%#*+                                                         
                                   %%@@%%#*                                                         
                                   %@@@@%#*                                                         
                                   %@@@@@%*                                                         
                                    %%%%%#*+                                                        
                                    #%%%%%#+                  ====-=                                
                                    #%%%@@%*+         ====-=+*+++++====                             
                                     %@@@@%#=       **+++++==**+++++===                             
                                     #%#*##*=-      ***+++++==#++++===++                            
                                      %#*++*=- +===--**=+++=-=%++++++=*#  =====                     
                                      %%#+=+=-++++++==*+==+===#*+*+++=++=---=-:-=                   
                                       ##*=--=***++++=+#++++==*+-::::::=-----=-===                  
                                       *++---+#***++===%****++*=-:....::-:-====+==                  
                                       +-===+#%#*+++===###***#@@#*=---::-==+++**==+                 
                                       =--+*#%@#***+++=*@%###%@@@@%%%###**####*++++                 
                                      *+=+++#%@%##****++@@%%%@@@@@@@@@@@@@@@%***+++                 
                                      **##%%@@@@######*+#@@@@@@@@@@@@@@@@@@@%#*+=+++                
                                      *+--:--+*#%%%%%####@@@@@@@@@@@@@@@@@%##**+++++                
                                      ++----=+*#%%@@@@@@@@@@@@@@@%#*++++==**+++++***                
                                      *+=======*#%@@@@@@@@@@@@%#**+==--:---++++*##%%                
                                      ***--===+###%@@@@@@##*+=====--::::--::=++*###                 
                                       *+=---=+==#%%%@%*+===-::::-=-::::::-===*##%%                 
                                       ++=====--=+==+*=---:--:::::::---====++*#%@@                  
                                       *++=+=--==-:-+=----:::--=========++++#%%@                    
                                       #*+++=-=-:::==-===------===+++*****##%@                      
                                        #**+--::::-=-==++==+++=+++****###%%@@                       
                                         *+=---::-++==+=++*******####%%@@@@                         
                                         **+==---=++++*######%%%%%%%@@@@@                           
                                          #*+++=++=+**++*#%@@@@@@@@@@@@                             
                                           ###***+***#***##%%@@@@@@@@                               
                                            %%%%%%%###%####%%%%%@%%%%                               
                                             ###*****+++*********####                               
                                             %##***###*****+****###***                              
                                              #******#**+*++++****+++*                              
                                              #*******#*+++==++++===+**                             
                                              #*++++++**+++=========+**                             
                                               **++++++*+++=--=======+*#                            
                                               *++=+===*+=+======--==++*                            
                                               #*++++=+*++++==-----===+**                           
                                               #*++++==++====-------===+*                           