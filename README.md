Sqor ft rest

cd into deps
cd into feedtools
install python deps in readme

redbug:start("foo_srv"). // trace of thigns that happen 
=======
cd out
rm deps inside ft_rest


make


SQOR_DEPLOY_ENV=development  erl -pa ebin deps/*/ebin -s sqor_ft_rest -config rel/files/development.sys.config




Pid = erlang.whereis(foo_srv).

l make bare min
make bootstrap


rm -rf bootstrap



one_for_one = one restarts, onlyone restart


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

how to subscribe to websockets 

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


feed-tools setup:

 sudo apt-get install python-setuptools python-virtualenv 





 Stats Inc:

 L = si_api:get_stats(<<"nfl">>, <<"player_ytd">>, [<<"323273">>], [])
 
 Print without bs


 rp(L). 


maps:get(<<"league">>, L)

M = #{key => 23442}.   

Pattern match our name out:

 {key := Key} = M. 


erl -pa ebin deps/*/ebin -s sqor_ft_rest -config ../local_ftrest.config -name entity_cache@127.0.0.1



Start Skirak:

erl -pa ebin deps/*/ebin -s sqor_riak -config path/to/a/development.sys.config




