# Task 3 - LVM

1. Создать 4 файла размером 1Гб каждый, создать loopback устройства из файлов при помощи losetup.    
2. Создать физические разделы на этих устройствах при помощи pvcreate. Создать volume group из первых двух девайсов. На ней создать logical volume при помощи lvcreate.  
4. Создать файловую систему при помощи mkfs.ext3, подмонтировать её, посмотреть какой размер.    

5. Добавить оставшиеся два  устройства в группу. Изменить размер логического тома, затем размер файловой системы. Проверить размер при помощи df. В качестве результата сделать два скриншота команд.    

