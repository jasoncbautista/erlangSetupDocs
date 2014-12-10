




SqorWeb sockets


rm -rf /deps
make




observer:start().


make app 



Running release:


byte code  vs self contained released:

 ./_rel/websocket_example/bin/websocket_example console



/path add
erl -pa  




Running our montolithic app:


./start.sh local 



make sure to setup rabbit first 

Rabbit 
sudo service rabbitmq-server start



Rabbit:

http://localhost:15672/


add sqor user 


look at user and make sure you got it:

rel/files/local.sys.config


Admin -> Add user 
Admin -> click on user sqoradmin  -> Tags: Admin 
update user 
click on set permission


disable geuest , eventually.... 



https://localhost:8080
advanced -> proceed


click connection to disconnect

-> publish msg

use user key i.e 37444

payload


Exchanges -> Direct



Mini Msgs ()
king.id.Action
event.123.update
event.*.update

user.3445.____


Broadcast:

any event related to this player.. goes there

anyone that cares about that player goes there



To subcribe publish, and unsucbrscribe"

{"command": "subscribe", "route": "a.b.*"}


Subscribe from client:

{"command":"subscribe","route":"a.b.*"}


Now go to queue -> broadcast a.b.*
publish -> a.b.c

any data for payload
