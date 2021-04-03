# ahk

All scripts are written to work with [AHK V2](https://lexikos.github.io/v2/docs/AutoHotkey.htm), which is technically still in Alpha (NOT AHK V1).

I renamed my main microphone to "Mic" so that it is unique from any other audio input device I might have plugged in.


## Installing AHK V2

Go to https://www.autohotkey.com/, click "Download", and select both "Download Current Version" and "Download V2 Alpha". This should download two files: `AutoHotkey_1.1.33.06_setup.exe` and `AutoHotkey_2.0-a129-78d2aa15.zip` respectively.

Run `AutoHotkey_1.1.33.06_setup.exe`, do "Custom Installation", "Unicode 64-bit" (or 32-bit if you're on a 32-bit machine), and for options be sure to select "Install script compiler". Now, you should have AutoHotkey installed to wherever you chose (default should be `C:\Program Files\AutoHotkey`).

Now, open up `AutoHotkey_2.0-a129-78d2aa15.zip`. You should see a couple of files, but the important ones are `AutoHotkeyU32.exe` and `AutoHotkeyU64.exe`. If you chose Unicode 64-bit in the previous step, rename `AutoHotkeyU64.exe` to `AutoHotkey.exe`. If you chose Unicode 32-bit in the previous step, rename AutoHotkeyU32.exe to AutoHotkey.exe. Then, replace the `AutoHotkey.exe` in `C:\Program Files\AutoHotkey` with your new `AutoHotkey.exe` executable.
