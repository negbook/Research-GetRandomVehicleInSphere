# Research-GetRandomVehicleInSphere  
GetRandomVehicleInSphere may not get train and trailers (maybe)

Class                       Flags  
14 15                       :-1  
16                          :16390  
17                          :2,6,7,94
20                          :2,6,7,94  
0~13                       :2,4,7,94  

0 only find some police  
2 same as 6,94.maybe perfer to hit some classes.forexample 6 is perfer to find service car like taxi.   no plane no train no heli  
2,6 dont find when player is in,but 94 is included player is in  
7 finds more than 2.which finds FBI/POLICE/SHERIFF s  . no plane no train no heli  no player is in  
-1 only find (4 police helis and 1 police boat)  
16390 find only 16    planes
    
2146=67590=2,6,94  
100359 = 67711 = 2175= 127 = 23 = 7  
16386 = 16390  
  
12294 specialA  
20503 specialB  plane + heli
101383 police cars and a bike

2,6,7,94 not included trailer

2+101383 = 7


want to get all car , bike and bicycle:  not supported player is in  
entity = GetRandomVehicleInSphere( x,y,z, radius , 0 , 7 )   
want to get all car , bike and bicycle:  supported player is in  
entity = GetRandomVehicleInSphere( x,y,z, radius , 0 , 23 or 127 or 2175 or 67711)   

want to get all car , bike and bicycle without polices:  not supported player is in  
entity = GetRandomVehicleInSphere( x,y,z, radius , 0 , 2 )   
want to get all car , bike and bicycle without polices:  supported player is in  
entity = GetRandomVehicleInSphere( x,y,z, radius , 0 , 94 )   

want to get all planes :  not supported player is in 
entity = GetRandomVehicleInSphere( x,y,z, radius , 0 , 16390 )   
want to get all planes , helis:  supported player is in  
entity = GetRandomVehicleInSphere( x,y,z, radius , 0 , 20503 )   




