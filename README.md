# GoesBackground
Script to grab the latest image from the GOES16 satellite and set it as the background on a Win10 computer

You will need gitbash to run this. When you initially set it up, right click SpaceBackground.sh > Open With... > Choose Another App > check Always Use This App to Open .sh Files > Git Bash
Script is set up to run in a folder directly on C:, but if you edit it you should be able to put it wherever you want.


You can set it up to automatically run in the background using Task Scheduler. Create Task; Triggers: At log on, repeat every 1 hour, indefinitely; Actions: [path to shell script]
