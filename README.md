"# greenhouse"


Windows (node-pie)

1. Open file C:\Users\Your_User_Name\AppData\Roaming\npm\node_modules\node-pie\node_modules\node-red\Settings.js 

Searching for the line begining with 
            httpStatic: '/home/hol/node-red-static/',
then modifies it to
            httpStatic: path.join('','public'),

2. Copy gauge.min.js to folder

C:\Users\Your_User_Name\AppData\Roaming\npm\node_modules\node-pie\node_modules\node-red\public\scripts



Windows (node-red)

1. Open file C:\Users\Phaitoon\AppData\Roaming\npm\node_modules\node-red\Settings.js 

Searching for the line begining with
        httpStatic: '/home/hol/node-red-static/',
then modifies it to
        httpStatic: path.join('','public'),

2. Copy gauge.min.js to folder

C:\Users\Phaitoon\AppData\Roaming\npm\node_modules\node-red\public\scripts

3. Copy all images to
C:\Users\Phaitoon\AppData\Roaming\npm\node_modules\node-red\public\images



Linux (Raspberry PI)

1. Open file $HOME/.node-red/Settings.js

Edit the line which begins with
      httpStatic: '/home/hol/node-red-static/',
to
      httpStatic: '/home/pi/.node-red/public'

2. Copy gauge.min.js to directory

      $home/pi/node-red/public/scripts    

3. Copy all images to 

      $home/pi/node-red/public/images    



NOTE: อ้างถึง src='/scripts/gauge.min.js'
