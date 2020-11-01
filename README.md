# tutor-ffmpeg

Yang perlu kita lakukan adalah menambahkan C:\ffmpeg\bin ke system path kita, dan itu akan memahami bekerja.

Buka file explorer dan klik kanan pada [This Pc] kemudian pilih properties

Lalu pilih advanced system settings
<img src="http://gregzaal.com/ss/System_2014-05-30_19-26-45.png" width="128" height="128"/>

Open up the Environment Variables:


And then edit the Path variable:



The Path is just a list of folders that contain commands you’re allowed to use without typing in the full path of the exe files.

So, go ahead and add C:\ffmpeg\bin to the end of the line, making sure that there’s a semi-colon (;) after the previous folder:

