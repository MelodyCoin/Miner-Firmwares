# Miner-Firmwares
Nand Dumps for BitMain and Innosilicon miners.

Used to UnBrick Control Boards and for repairs.

- All tested to work 100% 
- All dumped 1:1 from nand with 0 bad blocks.

Dumps need to be flashed using a nand programmer (Tl866ii+(with nand08/nandx8 adapter) , T48 , T56 and DATAMAN-48PRO2 tested 100% working for this and easy to find cheap, also powerful tools for any repairs)
Other model of nand programmer should work just fine too.



To Unbrick/Flash your control board
(procedure is the same for any control board): 

1 - First download the nand dump for the model of your miner

'If you are using a new or replacement chip, skip to step 6'

2 - Unsolder the Nand flash chip from the control board carefully using hot air rework station or soldering braid and lot of flux.

3 - Use soldering iron and solder braid to clean the pads and the chip pins carefully to make sure no solder is left on any pads or pin and no pins are bridged.

 MAKE SURE TO BE EXTRA CAREFUL , TSOP48 chips have VERY SMALL pins and are easy to dammage or bend!!!!
 
 4 - Using adapter and a TSOP48 socket (solderless adapters make the job 200% easier and faster) , place the chip in your programmer.
 
 5 - Do a read in your programmer software to "backup/dump" the content of your current flash, just in case. If hardbrick or brand new/replacement chip, skip this step.
 
 6 - Erase the nand in your programmer software and perform a blank check to make sure nand is well erased and is perform as intended, sometime, the are not well seated in the adapter and will cause errors.
 
 7 - Load the downloaded Nand Dump for you miner model in the programmer software and click program/flash, note that nand image are compressed in 7zip archive format. Don't forget to extract before flashing. aka not directly flash downloaded file ^^
 
 8 - If your programmer does not auto-verify, click verify in the interface to make sure data is 100% okay on the chip. If it was auto-verified good or passes, proceed to next step, if it fails, try to reseat the chip and restart the programming. If it flash ok and pass the verify, go to next step, if it still fails, make sure it is well seated in the programmer , possibility of a bad chip too. You can normally run a bad block check from the programmer software interface. if it have bad block(s), replacing the chip is advised. Don't forget to flash the new chip before soldering it if you need to replace it!
 
 9 - Once chip programmed, it is time to resolder it on the control board using your favourite method(hot air, solder paste, runing the solder iron tips, ect)
 
 IMPORTANT THAT NO PINS BRIDGE, TSOP48 are easy to bridge and miss it, make sure to use PLEANTY flux , and don't hesitate to take your time, no need to rush it!
 
 10 - Once the freshly programmed chip is well in place and soldered, and that all joint were inspected and there are no bridges,
 
 
                     <3 <3 <3     POWER UP THE CONTROLLER AND ENJOY IT WORKING LIKE BRAND NEW!!!     <3 <3 <3 
 
 Hope the files and tutorial will help as many peoples as possible and fix as many bricked controller.
 
 Most of those controller dont even come with an sd card to recover them sadly(like the Innosilicon g19 or new BitMain boards)
So I decided to dump them one by one, and make it avaible to to world so nobody get stuck with a bricked control board anymore.

If you used my fils and tutorial to save your board, please take your time to leave a comment and share your experience with the community.
If you appreciate my work, I would ask you to leave the miner running with the default pool settings for a couple hours. They are my "devfees" and help bring you more and more firmware and cool tool in the future. I got inspired by other devloppers to do this, this way my work can stay free of use and I don't have to include percentage devfees like all most others.
It also allow for good testing of the unit operation.
If your repair machine commercially or a lot of them, please make sure to leave them on default setting to test for at least an hour per units, commercial/sold service/batch type of work use is welcomed if this is respected only. Especially if you charge for your work.

Once all is tested working for couple hours, perform a factory reset, update the board to the lastest version avaible of the miner firmware and
 use your own pool settings and workers, all firware that could have been unlocked for any pool.
 
 Have a bright and butterfly day
 
 Melody
