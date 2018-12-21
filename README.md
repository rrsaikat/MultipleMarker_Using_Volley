# Show-Multiple-Markers-Using-Android-Volley-Library

<p align="center">
  <img src="https://github.com/rrsaikat/MultipleMarker_Using_Volley/raw/master/Screenshot_2018-04-16-09-05-04.png" height="550" width="350"/>
  <img src="your_relative_path_here_number_2_large_name" width="250"/>
</p>

Sample app download link ---> https://drive.google.com/open?id=1zVXgbT52muBZCDlF_z4q61atZrwYZdcF

<div align="center">
  <a href="https://www.youtube.com/watch?v=GcAQMNljno4"><img src="https://github.com/rrsaikat/MultipleMarker_Using_Volley/raw/master/youtube%20video%20pic.PNG" height="350" width="550" alt="IMAGE ALT TEXT"></a>
</div>



<p>Step 1:</p>
<p>Create your own free or paid web hosting server, you can try 000webhost.com or byethost.com for creating free web server with a domain
name(e.g: http://rrsaikat.mydiscussion.net) . Now go to htdocs of your domain and locate the <b>location.php</b> file into a subfolder named 
myjson. Before locating the location.php file you need to configure your own phpmyadmin hostname, username, password and database name 
also (e.g: $host='sql104.byethost12.com'; $uname='rrsaikat';$pwd='1234';$db="xyz";)</p>
<p>Download link of location.php ----->https://drive.google.com/open?id=1OqllLb_B-95x159ABj37TfqLYcrLwpY9</p>


<p>Step 2:</p>
<p>Create a database named "xyz" in your phpMyadmin and then import this Location.sql file (n.b: Must create a database first then import,otherwise error occurs) .</p>
<p>Location.sql ----->https://drive.google.com/open?id=1AJyJJ9mWtE9DcKo0vdhtP1nCCVyQ9S8e</p>

<p>Step 3:</p>
<p>Now go to your web browser and hit the Server URL you created(e.g: http://your_domain_name/subfolder/location.php)</p>
<p>This is my JSON data -------->http://rrsaikat.mydiscussion.net/myjson/location.php </p>
<p>Click the above URL in step 3 to see the json response from the server and our json will look like this :</p>

	{  
	   "FL":[  
	      {  
		 "0":"1",
		 "id":"1",
		 "1":"23.8103",
		 "latitude":"23.8103",
		 "2":"90.4125",
		 "longitude":"90.4125"
	      },
	      {  
		 "0":"2",
		 "id":"2",
		 "1":"22.7010",
		 "latitude":"22.7010",
		 "2":"90.3535",
		 "longitude":"90.3535"
	      },
	      {  
		 "0":"3",
		 "id":"3",
		 "1":"23.6",
		 "latitude":"23.6",
		 "2":"89.8333333",
		 "longitude":"89.8333333"
	      }
	   ]
	}

<p>Step 4:</p>
<p>After importing the project from github into android studio, you need to create your own google_maps_api key and add them so carefully.Then create credintials and edit your api key by adding restriction of your key as only Android apps, give package and SHA-1 fingerprint into it.</p>
<p align="center">
  <img src="https://github.com/rrsaikat/MultipleMarker_Using_Volley/raw/master/Capture.JPG" height="550" width="350"/>
</p>



<p>Step 5:</p>
<p>Give thumbs up(like) ,share and subscribe the video :D 
One thing you always remember that "Sharing is Caring". Good Luck everyone!</p>


## LICENSE

    Multiple markers using volley library in android studio 3.0.3
    Copyright (C) 2018  Md. rezwan rabbi

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.
