# ahk

All scripts are written to work with [AHK V2](https://lexikos.github.io/v2/docs/AutoHotkey.htm), which is technically still in Alpha (NOT AHK V1).

I renamed my main microphone to "Mic" so that it is unique from any other audio input device I might have plugged in.


## Installing AHK V2

Go to https://www.autohotkey.com/, click "Download", and select both "Download Current Version" and "Download V2 Alpha". This should download two files: `AutoHotkey_1.1.33.06_setup.exe` and `AutoHotkey_2.0-a129-78d2aa15.zip` respectively.

Run `AutoHotkey_1.1.33.06_setup.exe`, do "Custom Installation", "Unicode 64-bit" (or 32-bit if you're on a 32-bit machine), and for options be sure to select "Install script compiler". Now, you should have AutoHotkey installed to wherever you chose (default should be `C:\Program Files\AutoHotkey`).

Now, open up `AutoHotkey_2.0-a129-78d2aa15.zip`. You should see a couple of files, but the important ones are `AutoHotkeyU32.exe` and `AutoHotkeyU64.exe`. If you chose Unicode 64-bit in the previous step, rename `AutoHotkeyU64.exe` to `AutoHotkey.exe`. If you chose Unicode 32-bit in the previous step, rename AutoHotkeyU32.exe to AutoHotkey.exe. Then, replace the `AutoHotkey.exe` in `C:\Program Files\AutoHotkey` with your new `AutoHotkey.exe` executable.

Repeat above steps but with the AHK2 Compilers, replacing `AutoHotkeySC.bin` with the respective bin file that you're using (Unicode/ANSI 32/64-bit).

## Compiling AHK scripts

To compile, you should now be able to just right click any `.ahk` file and select "Compile Script". This should generate a `<script>.exe`. If you want this script to start every time you start up your machine, you'll have to add it to your Startup folder, which is typically located in `C:\Users\<Username>\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup`. To do this, you can right click your `<script>.exe`, select "Create shortcut", and copy the generated shortcut to your `Startup` folder. Note that the shortcut relies on the original .exe file existing, so deleting the exe file will break the shortcut. 
