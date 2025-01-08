open your terminal
make sure you have latest version of dotnet 7 sdk installed with the command "dotnet --list-sdks"

run the command in terminal: dotnet run
a link will be shown like "http://localhost:5050"
make sure if the launchSettings.json ports are the same as the link below (in this example, 5050)


you can check the requisitions with the file FruitsAPI.http (check the var hostaddress port) clicking over "Send Request" over the commands with Rest Client extension for vs code or
you can open in a browser the url "http://localhost:5050/swagger/index.html" and try out the requisitions or
you can open in a browser the url "http://localhost:5050/fruitlist/", it will return all the database. If you want a specific item add the id number in the end. Or
you can open another terminal and use the command "httprepl http://localhost:5050/", then go to the repository using "cd" and then check for the commands like "get" or "delete 1" "etc"
