
Automaticly import Adif file : 

curl -F "adiffile=@_FULLPATH_OF_YOUR_ADIF_FILE_.adif" \
-F  "callsign=_YOUR_CALLSIGN_" \
-F "token=_YOUR_TOKEN_" \
https://gridmaster.fr/adif


curl "https://gridmaster.fr/adif?process=_YOUR_CALLSIGN_&token=_YOUR_TOKEN_"


_FULLPATH_OF_YOUR_ADIF_FILE_ : The full path of your Adif file, include @ for curl file
_YOUR_CALLSIGN_ : The default callsign you are using on gridmaster.fr
_YOUR_TOKEN_ : The token show in your account at the bottom of https://gridmaster.fr/account
