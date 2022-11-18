# IMPLEMENTATION OF MY PROJECT 7 WORK
## This project is to enbale me acquire practical skills in deploying a DevOps Tooling website from a GitHub repository. 

`1. I connected to my NHS instance and confirmed that the volumes were attached using the lsblk command`

![alt text](/Project7/Images/1.%20I%20connected%20to%20my%20NHS%20instance%20and%20confirmed%20that%20the%20volumes%20were%20attached%20using%20the%20lsblk%20command.JPG)


`2. I created 3 volumes  and attached them to my NFS Server`

![alt text](/Project7/Images/2.%20I%20created%203%20volumes%20%20and%20attached%20them%20to%20my%20NFS%20Server.JPG)

`3. I created the aws red-hat instace for 3 web servers and 1 ubuntu for mysql`


![alt text](/Project7/Images/3.%20I%20created%20the%20aws%20red-hat%20instace%20for%203%20web%20servers%20and%201%20ubuntu%20for%20mysql.JPG)


`4. I partitioned the volumes using the gdisk command`

![alt text](/Project7/Images/4.%20I%20partitioned%20the%20volumes%20using%20the%20gdisk%20command.JPG)


`5. I installed the LVM package`

![alt text](/Project7/Images/5.%20I%20installed%20the%20LVM%20package.JPG)


`6. LVM Installation confirmed`

![alt text](/Project7/Images/6.%20LVM%20Installation%20confirmed.JPG)

`7. I created Physical Volumes for the 3 partitions`

![alt text](/Project7/Images/7.%20I%20created%20Physical%20Volumes%20for%20the%203%20partitions.JPG)



`8. Physical Volumes confirmed`

![alt text](/Project7/Images/8.%20Physical%20Volumes%20confirmed.JPG)

`9. I created a volume group for the partitions and named it webdata-vg`

![alt text](/Project7/Images/9.%20I%20created%20a%20volume%20group%20for%20the%20partitions%20and%20named%20it%20webdata-vg.JPG)

`10. I confirmed that volume group were created`

![alt text](/Project7/Images/10.%20I%20confirmed%20that%20volume%20group%20were%20created.JPG)


`11. I created 3 logical volumes lv-apps lv-logs and lv-opt and gave the 9gb each`

![alt text](/Project7/Images/11.%20I%20created%203%20logical%20volumes%20lv-apps%20lv-logs%20and%20lv-opt%20and%20gave%20the%209gb%20each.JPG)


`12. Creation of the logical volumes confirmed`

![alt text](/Project7/Images/12.%20Creation%20of%20the%20logical%20volumes%20confirmed%202.JPG)


`13. I formatted the 3 hard disk using the xfs format rather than ext4`

![alt text](/Project7/Images/13.%20I%20formatted%20the%203%20hard%20disk%20using%20the%20xfs%20format%20rather%20than%20ext4.JPG)


`14. I created 3 directories and mounted the logical volumes on the directories`

![alt text](/Project7/Images/14.%20I%20created%203%20directories%20and%20mounted%20the%20logical%20volumes%20on%20the%20directories.JPG)


`15. I did yum update`

![alt text](/Project7/Images/15.%20I%20did%20yum%20udtae.JPG)


`16. As yum was updating i connected to my DB server`

![alt text](/Project7/Images/16.%20As%20yum%20was%20updating%20i%20connected%20to%20my%20DB%20server.JPG)


`17. I did sudo apt update for my database server`

![alt text](/Project7/Images/17.%20I%20did%20sudo%20apt%20update%20for%20my%20database%20server.JPG)


`18. I installed mysql`

![alt text](/Project7/Images/18.%20I%20installed%20mysql.JPG)


`19. I created database on mtysql called tooling`

![alt text](/Project7/Images/19.%20I%20created%20database%20on%20mtysql%20called%20tooling.JPG)


`20. I created username webaccess and granted all privileges to it at the subnet cidr`

![alt text](/Project7/Images/20.%20I%20created%20username%20webaccess%20and%20granted%20all%20privileges%20to%20it%20at%20the%20subnet%20cidr.JPG)


`21. I confirmed that databse was formed`

![alt text](/Project7/Images/21.%20I%20confirmed%20that%20databse%20was%20formed.JPG)


`22. Back to NFS i installed nfs utilities.JPG`

![alt text](/Project7/Images/22.%20Back%20to%20NFS%20i%20installed%20nfs%20utilities.JPG)


`23.I started and enabled the nfs server`

![alt text](/Project7/Images/23.I%20started%20and%20enabled%20the%20nfs%20server.JPG)


`24. NFS server is running and active`

![alt text](/Project7/Images/24.%20NFS%20server%20is%20running%20and%20active.JPG)


`25. I changed the ownership and modified the permission`

![alt text](/Project7/Images/25.%20I%20changed%20the%20ownership%20and%20modified%20the%20permission.JPG)


`26 I restarted and checked the status after I changed the ownership and modified the permission`

![alt text](/Project7/Images/26%20I%20restarted%20and%20checked%20the%20status%20after%20I%20changed%20the%20ownership%20and%20modified%20the%20permission.JPG)


`27 I configured access to NFS for clients within the same subnet`

![alt text](/Project7/Images/27%20I%20configured%20access%20to%20NFS%20for%20clients%20within%20the%20same%20subnet.JPG)


`28. I exported so the webservers can see it when i connect27 I configured access to NFS for clients within the same subnet`

![alt text](/Project7/Images/28.%20I%20exported%20so%20the%20webservers%20can%20see%20it%20when%20i%20connect.JPG)


`29. I checked the port used by the NFS`

![alt text](/Project7/Images/29.%20I%20checked%20the%20port%20used%20by%20the%20NFS.JPG)


`30. I connected to my Webserver 1`

![alt text](/Project7/Images/30.%20I%20connected%20to%20my%20Webserver%201.JPG)


`31. I installes NFS server on the first webserver`

![alt text](/Project7/Images/31.%20I%20installes%20NFS%20server%20on%20the%20first%20webserver.JPG)


`32. I created a directory and mounted it in NFH server using the Private IP address to link to our NFS`

![alt text](/Project7/Images/32.%20I%20created%20a%20directory%20and%20mounted%20it%20in%20NFH%20server%20using%20the%20Private%20IP%20address%20to%20link%20to%20our%20NFS.JPG)


`33. I confirmed that dirctory is mounted on NFS server`

![alt text](/Project7/Images/33.%20I%20confirmed%20that%20dirctory%20is%20mounted%20on%20NFS%20server.JPG)


`34. I edited fstab file and added the private ip address of the NFS server`

![alt text](/Project7/Images/34.%20I%20edited%20fstab%20file%20and%20added%20the%20private%20ip%20address%20of%20the%20NFS%20server.JPG)


`35. I installed webservers httpd`

![alt text](/Project7/Images/35.%20I%20installed%20webservers%20httpd.JPG)


`36. I installed dnf`

![alt text](/Project7/Images/36.%20I%20installed%20dnf.JPG)


`37. I installed nf-utilitiess`

![alt text](/Project7/Images/37.%20I%20installed%20nf-utilitiess.JPG)



`38. I reset my php`

![alt text](/Project7/Images/38.%20I%20reset%20my%20php.JPG)


`39. I enabled php`

![alt text](/Project7/Images/39.%20I%20enabled%20php.JPG)


`40. I followed the documentation and did  setsebool -P httpd_execmem 1`38. I enabled php`

![alt text](/Project7/Images/40.%20I%20followed%20the%20documentation%20and%20did%20%20setsebool%20-P%20httpd_execmem%201.JPG)`


`41. I mounted on my apache to connect my nfs to my apache usong the private ip address of my nfs server`

![alt text](/Project7/Images/41.%20I%20mounted%20on%20my%20apache%20to%20connect%20my%20nfs%20to%20my%20apache%20usong%20the%20private%20ip%20address%20of%20my%20nfs%20server.JPG)`


`42. I edited fstab and adde the path for apache to it`

![alt text](/Project7/Images/42.%20I%20edited%20fstab%20and%20adde%20the%20path%20for%20apache%20to%20it.JPG)`


`43. I installed git on my webserver 1`

![alt text](/Project7/Images/43.%20I%20installed%20git%20on%20my%20webserver%201.JPG)`


`44. I was able to  fork tooling source code from darey's git account`

![alt text](/Project7/Images/44.%20I%20was%20able%20to%20%20fork%20tooling%20source%20code%20from%20darey's%20git%20account.JPG)`


`45. I confirmed that tooling directory was tere and files were inside it`

![alt text](/Project7/Images/45.%20I%20confirmed%20that%20tooling%20directory%20was%20tere%20and%20files%20were%20inside%20it.JPG)`


`46.I copied all on html to the html folder on my var-www`

![alt text](/Project7/Images/46.I%20copied%20all%20on%20html%20to%20the%20html%20folder%20on%20my%20var-www.JPG)`


`48. I started http and checked status to confirn it was active`

![alt text](/Project7/Images/48.%20I%20started%20http%20and%20checked%20status%20to%20confirn%20it%20was%20active.JPG)`


`49. I checked connected on my brower usiong oublic ip address for my webserver 1 and it was working perfectly`

![alt text](/Project7/Images/49.%20I%20checked%20connected%20on%20my%20brower%20usiong%20oublic%20ip%20address%20for%20my%20webserver%201%20and%20it%20was%20working%20perfectly.JPG)`


`50. I edited the function.php folder to add the mysql database and password as well as the public ip of database`

![alt text](/Project7/Images/50.%20I%20edited%20the%20function.php%20folder%20to%20add%20the%20mysql%20database%20and%20password%20as%20well%20as%20the%20public%20ip%20of%20database.JPG)`


`51. I edited mysql.cnf address to accept from anywhere`

![alt text](/Project7/Images/51.%20I%20edited%20mysql.cnf%20address%20to%20accept%20from%20anywhere.JPG)`


`52.I was able to script to my database using the command on the documentation`

![alt text](/Project7/Images/52.I%20was%20able%20to%20script%20to%20my%20database%20using%20the%20command%20on%20the%20documentation.JPG)`


`53. I polulated mysql`

![alt text](/Project7/Images/53.%20I%20polulated%20mysql.JPG)`





`54. Ip address updated and website working perfectly`

![alt text](/Project7/Images/54.%20Ip%20address%20updated%20and%20website%20working%20perfectly.JPG)`


`55. I followed same procedure for my second webserver`

![alt text](/Project7/Images/55.%20I%20followed%20sam%20procedure%20for%20my%20second%20webserver.JPG)`


`56. I followed sam procedure for my third webserver`

![alt text](/Project7/Images/56.%20I%20followed%20sam%20procedure%20for%20my%20third%20webserver.JPG)`


`57. Ip address updated and website working perfectly for my 2nd webserver`

![alt text](/Project7/Images/57.%20Ip%20address%20updated%20and%20website%20working%20perfectly%20for%20my%202nd%20webserver.JPG)`


`58. Ip address updated and website working perfectly for my 3rd webserver`

![alt text](/Project7/Images/58.%20Ip%20address%20updated%20and%20website%20working%20perfectly%20for%20my%203rd%20webserver.JPG)`


`58. Ip address updated and website working perfectly for my 3rd webserver`

![alt text](/Project7/Images/58.%20Ip%20address%20updated%20and%20website%20working%20perfectly%20for%20my%203rd%20webserver.JPG)`