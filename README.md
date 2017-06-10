ONLY FOR APPLE USERS

# Process_Done_Notification
Applescript service to get notified when long, non-terminal processes like downloads finish. 
You enter a process (e.g. one related to the download) and get notified when its goes under an
% of CPU activity you specify. Tested it on one download so far and worked great.

FOR BEGINNERS:

1) Download the repository and unzip the 'Process_done_notification.workflow.zip' file. 
2) Then, open a finder window, click 'command+shift+g' and copy '~/Library/Services' in the opening window and click 'enter'.
Then put the 'Process_done_notification.workflow' file into this directory (the Services folder).

In order to trigger this workflow, in most programs click on the program menu (e.g. 'Safari' in the upper corner and open the menu 'Services', 
and then select 'Process_done_notification'. You also can configure a shortcut by going into 'system preferences'
and then 'keyboard' and then 'shortcuts' and then on the left 'services'. Now scroll to the bottom all the way and double-click 
the area on the right of the shortcut 'Process_done_notification'. Now enter the shortcut you want to use to trigger the Process_done_notification.
After that, the shortcut should trigger the Process_done_notification from any program.

USAGE:

1) Start Process_done_notification
2) Look at the activity monitor (it should have been opened). Sort it descending by CPU activity. You should see that one of the most used processes 
has something to do with whatever you want to get notified when its over (e.g. a download). Look at the column 'PID' and 
copy this value into the popup window. Then write a small value (0.1 mostly is good) after that. It specifies how few of the 
CPU has to be used by the process to be considered done. Click enter twice. When the process is done, you will get a notification 
from the notification center. Thus, keep an eye on not having notifications muted while the process.



