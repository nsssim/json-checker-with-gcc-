# json-checker-with-gcc-
this is my bui ltversion of the json checker from http://www.json.org/JSON_checker/ using mingw + gcc 

you can use the release version like this to check a bunch of json files : 

jsnochecker.bat
---------------
cmd /K "for %%i in (*.json) do jsnochecker < %%i"
pause
