To use this properly you will need afterburner and rtss (final build 7.3.6) but should still work with older versions

This overlay will show you:

GPU temp // clock and memory speed // voltage // ram usage // % usage
CPU temp // clock speed // % usage
RAM usage in MB
current API used by the programm/game the overlay is displayed in (e.g. OGL or D3D9)
GPU PWR usage in watts
CPU PWR usage in watts

To edit, open rtss and click on setup at the bottom -> plugins and double click OverlayEditor.dll now click on layouts -> import and select the .ovx file

To save click layouts and save

Now you can simply double click any layer you want and adjust its position or color (default is orange and I have already set a color scheme what I think is best but edit if you want) be careful though you can also drag the layers around (mousewheel to zoom)



If you click on "Data sources" at the top (idk if they are included in the .ovx file) you should see a list with:

(AB)CPU temperature
(AB)CPU clock
(AB)CPU power
(AB)Power
(RTSS)GPU1 power
(RTSS)GPU1 temperature
(RTSS)GPU1 usage
(RTSS)GPU1 clock
(RTSS)GPU1 voltage
(RTSS)GPU1 memory clock
(RTSS)GPU1 memory usage
(RTSS)CPU usage
(RTSS)RAM usage

IF they are not included in the .ovx file then simply click add and search for them in the list, use the dropdown menu to select between different data providers (afterburner, rtss, hwinfo64, aida64
or even windows performance counter but for my overlay all you need is AB and RTSS as data providers)

To check if you like the position of everything simply run any game in windowed mode (corsair icue also works if you use it) and place them side by side so you can edit it while checking it simultaneously

In case you don't wanna use afterburner and use hwinfo64 or any other software instead just remove the first four data sources (the ones with (AB)) and look for the sensors in the respective programm



Refer to my reddit post for the hypertext you can use

https://www.reddit.com/r/MSI_Gaming/comments/pwwz85/is_there_a_way_to_add_a_data_source_that_shows/

To save simply click layouts in top left corner and save
