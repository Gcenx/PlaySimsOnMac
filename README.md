# PlaySimsOnMac
A guide for playing The Sims 1 on Intel and ARM Macs


# If the game crashes on startup
If you're on an M1 Pro/Max MacBook Pro or other higher resolution computer and the game crashes on startup, follow the instructions CAREFULLY on [this page](https://github.com/FaithBeam/Sims-1-Complete-Collection-Widescreen-Patcher) to install the widescreen patch. Try various resolutions until it works and is at a comfortable playing resolution.


# Step 1: Download The Sims Complete Collection and Wineskin Winery
The first thing you need to do is download The Sims Complete Collection from [here](https://oldgamesdownload.com/the-sims-complete-collection/).
Please keep in mind the serial number that's on that page. You'll need it later.

Next, we'll need Wineskin Winery. To get this, we need to install Homebrew first. This is as simple as running a single command. Get it [here](https://brew.sh). Copy paste the command on that page into your terminal and then follow the instructions in you terminal. MAKE SURE that at the end of the installation process you read the instructions in your terminal about how to add homebrew to your path! It should give you three commands to run in order to add it to your path. If you run `brew` later and it says the command was not found, this is why.

To install Wineskin after we have homebrew we simply run
`brew install --no-quarantine gcenx/wine/unofficial-wineskin`

# Step 2: Creating the Wineskin Wrapper
Open Wineskin Winery. You should get a window that looks like this:



<img width="287" src="https://user-images.githubusercontent.com/92334194/196012373-e92b8df3-1a5d-4b23-87d1-1cf597a3bf43.png">


Now click the + button and add the engine `WS11WineCX64Bit21.2.0` or whatever the latest one is. Make SURE you install a 64-Bit one. Click Download and Install.
Next, when you get back to the main Wineskin window, you should see that the Create New Blank Wrapper button is clickable. If it isn't, make sure that you click "Update" under Wrapper Version. After this is complete you should be able to click Create New Blank Wrapper.

Once you click that, it should ask you to enter a name for the wrapper. This will be the name of the app that you click on to open the game, so I recommend naming it The Sims.app. Click OK. You should see the spinning beach ball of death for a minute or two, then you will see this:


<img width="260" alt="Screen Shot 2022-10-15 at 8 39 31 PM" src="https://user-images.githubusercontent.com/92334194/196012560-77fad0ec-2ac2-431a-a7ff-85304e6bb5af.png">


# Step 3: Installing The Sims

Now that we've got the wrapper created, we need to install the Sims game into a sandbox within our wrapper.
Click "View wrapper in Finder". You should see a Finder window come up with your The Sims.app in it. Double click it and it should come up with a Wineskin menu. Choose Install Software. Then when the next window comes up, click "Choose Setup Executable". A file chooser window should appear. Go to where you downloaded the Sims Complete Collection (which from here on out I'm going to call `<tscc>`), then go to Game Files/ and choose start.exe. As seen below:


<img width="934" alt="Screen Shot 2022-10-15 at 8 46 35 PM" src="https://user-images.githubusercontent.com/92334194/196012714-f021d6d7-1b44-4ba0-b81c-9a022fde8eee.png">


It should come up with a familiar screen and play some nostalgic tunes:

<img width="639" alt="Screen Shot 2022-10-15 at 8 49 04 PM" src="https://user-images.githubusercontent.com/92334194/196012759-ed7b27cc-637c-413b-8e3e-b005c4cd0e9c.png">

Go through the installation like normal and MAKE SURE YOU DON'T CHANGE THE INSTALLATION PATH. It should install to either `C:/Program Files/Maxis/The Sims` or `C:/Program Files (x86)/Maxis/The Sims` and if you change this to install somewhere on your Mac, for example, the game will not work. Keep this as-is. It is a sandboxed path within The Sims.app that is meant to emulate the path as it would exist on Windows.

When you get to the serial number window, go back to Old Games Download where you got the game from and the serial number should be on there if you scroll down. (psst: it's EQMV-73XB-F8J4-GSLX-4M67)
Wait for the game to install, and when it gets to the end, it should bring as you if you'd like to register. Just say no, and then click Finish. It should bring you back to the language selection screen. Select your language again and then click "Exit". Don't click "Play" just yet, we're not finished.

When you click Exit, a new Wineskin window should appear, asking what should be the program's executable file. Click the dropdown and select Sims.exe.

<img width="586" alt="Screen Shot 2022-10-15 at 8 59 41 PM" src="https://user-images.githubusercontent.com/92334194/196013020-68c6a080-63c6-42c9-8002-f760590e49f5.png">


Now click OK and close all Wineskin windows. But KEEP that The Sims.app window open, we're not done with it yet.


# Step 4: Installing the No CD crack

Now all we have to do is install the No CD Crack so that we can actually play the game without having to insert a CD into our non-existant CD drive.
Open two windows side-by-side: in one, you should open `<tscc>/Game Files/The Sims Crack`. In the other, open where your The Sims.app file is. If you can't find it, it's in `/Users/<your username>/Applications/Wineskin/`. Here are the two windows side-by-side:


<img width="1140" alt="Screen Shot 2022-10-15 at 9 09 29 PM" src="https://user-images.githubusercontent.com/92334194/196013202-ff394304-86be-43f4-84c5-ac27f9b59f1f.png">


Next, right-click (or two finger click) on The Sims.app and click Show Package Contents. From there go to `drive_c/Program Files (x86)/Maxis/The Sims/` or `drive_c/Program Files/Maxis/The Sims/`. Drag the Sims.exe from The Sims Crack into this folder and replace it.

<img width="1135" alt="Screen Shot 2022-10-15 at 9 14 07 PM" src="https://user-images.githubusercontent.com/92334194/196013310-3a292bc4-24e8-41bc-b43d-82214be0bcdc.png">


Now double click The Sims.app and it should open the Sims!

![IMG_1530](https://user-images.githubusercontent.com/92334194/196013394-fc1ebea3-9b68-49c7-9537-b6236d742369.jpg)



# If you have any issues with this process

Please feel free to message me on reddit, u/hackergolucky! Thank you for reading and enjoy the Sims on Mac!
