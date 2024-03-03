# KEST
1. uhh
2. a
 i. Andri fann mest allar skipanir sem notaðar voru. Númi skrifaði mest allt í <br>
 ii. <br>
  -$ sudo useradd -m -c "Áslaug Hauksdóttir." -G allir,forritun,soludeild,sudo aslaug  <br>
  -$ sudo passwd aslaug<br>
  -$ sudo passwd -e aslaug<br>
  -$ sudo usermod -aG sudo aslaug<br>
 iii. <br>
 ![mynd 1](https://media.discordapp.net/attachments/1021524863984357387/1049987848864006195/image.png)<br>
 iv. <br>
 ![mynd 2](https://media.discordapp.net/attachments/1021524863984357387/1049988229174153226/image.png)<br>
 v. <br>
 ![mynd 3](https://media.discordapp.net/attachments/1021524863984357387/1049988503485820938/image.png)<br>
 shadow <br>
 ![mynd 4](https://media.discordapp.net/attachments/1021524863984357387/1050885042517315614/shadow.PNG?width=520&height=577)
 
 # Til Áslaugar
 ### Til að aflæsa user
 **-$** usermod -u user                                                                                                   <br>
 ### Til að búa til user
 **-$** sudo useradd -m -c "Nafn" -G group1,group2,sudo user                                                              <br>
 
 
 

#=============================================================#


## Commands til að muna
-$ sudo groupadd groupname                                                                                                 <br>
-$ sudo useradd -g users -G groupname users

### Gott að vita  
-$ sudo groupdel groupname                                                                                                 <br> 
-$ grep groupname /etc/group                                                                                               <br>

**-$** -m -c "nafn" -g group1,group2 -s /bin/bash ursname       
**-$** sudo usermod -s /bin/bash johan                                                           <br>
eða                                                                                                                        <br>
**-$** sudo useradd -G allir,forritun -c "Númi Hrafn" -m numi                                                              <br>
 
**-$** sudo useradd -m -c "Áslaug J." -G allir,forritun,soludeild,sudo aslaug                                              <br>
**-$** sudo usermod -G allir,soludeild,sudo aslaug

### Delete
**-$** sudo userdel user                                                                                                   <br>
**-$** sudo groupadd -r groupname
