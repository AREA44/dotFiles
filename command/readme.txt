# Shutdown

shutdown -s -t 3600

:: "-s" is shutdown | "-r" is restart | "-l" is sleep
:: "-t" is time to action
:: To cancel using "shutdown -a"

# Rename

rename *.* ???????-original.*

::“rename” is command
::*.* is “select all file in folder”. You can use “IMG*.*” to only select IMG file, etc

::“???????” hold first 7 characters

::“-original” is characters you want to insert

# Show Wifi password

netsh wlan show profile SmithHouse key=clear

::“SmithHouse” is name of Wifi