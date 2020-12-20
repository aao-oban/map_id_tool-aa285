# "map_id_tool" for AAO 2.8.5 servers

**"map_id_tool" is a mutator designed for AAO 2.8.5 servers.**

**Its purpose is to help players to accurately identify the map that is running on a server in order to download the correct map and thus avoid the DCDS message**

## How does it work?

map_id_tool gets the md5 code, the map file name and the map title of the map running on the server and sends this information using the responses from the server's query port.

map_id_tool adds the map information in the field for the server administrator's email.

map_id_tool works in conjunction with the server browser and also with the Dodge website, who are in charge of processing the information to generate a download link for the map.

## How to install map_id_tool on your server?

- **STEP 1**  Get a copy of the **map_id_tool.u** file [Download Here v1.0](https://bit.ly/3h1MuZW).
- **STEP 2**  Copy the **map_id_tool.u** file to the **system** folder of your server
- **STEP 3**  Stop your server and start it adding the parameter **?Mutator=map_id_tool.map_id_tool** as shown in the following example

## EXAMPLE:

**Server.exe LAN Bridge.aao?Mutator=map_id_tool.map_id_tool log=server.log ini=server.ini**
