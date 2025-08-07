# Hackintosh i3 12100 RX 570 macOS Sequoia 15.5 Working
Working macOS 15.5 Alder Lake Build
<img width="1920" height="1080" alt="Screenshot 2025-08-07 at 14 43 49" src="https://github.com/user-attachments/assets/6b83d38a-947c-42dc-8d8b-ca015159275d" />
<img width="392" height="689" alt="Screenshot 2025-08-07 at 14 33 46" src="https://github.com/user-attachments/assets/51e155c8-a7d2-4d18-92ae-5eaaea8a9652" />


Specs:
<ul><li>CPU: i3 12100F</li>
<li>GPU: RX 570</li>
<li>Motherboard: Gigabyte H610M H</li>
<li>RAM: G Skill 16GB DDR4 RAM</li>
<li>WiFi/BT: Intel AX210 WiFi/BT PCI Card</li>
<br><br>
What's working:<ul>
<li>Almost everything</li>
<li>Bluetooth! (thanks to <a href=https://www.reddit.com/r/hackintosh/comments/1fsvhsj/finally_i_made_my_bluetooth_work_in_sequoia/>this</a> post, using a user edited Bluetooth kext for Sequoia)</li>
<li>Bluetooth key syncing between Windows and macOS using <a href=https://www.reddit.com/r/hackintosh/comments/p5ost3/macos_monterey_and_windows_bluetooth_pairing/>this</a> guide</li>
<li>USB Mapping</li>
<li>Audio, HDMI Audio</li>
<li>Bootcamp (not needed but I set it up anyway)</li>
</ul><br><br>
What's not working
<ul><li>Airportltwm (Heliport works but no Airdrop/other features)</li>
<li>Keyboard wake from sleep (GPRW Patch was needed for getting sleep to work, but it disables USB wake from sleep, so need power button to wake from sleep</li>
<li>RTC Wake from sleep (a fix for this probably exists, but I've been lazy to search for it. Might fix it sometime in the future, but for now the PC wakes up from sleep every hour or so)</li>
</ul><br><br>
<li>I followed <a href=https://www.reddit.com/r/hackintosh/comments/sp1zgv/opencore_alder_lake_12thgen_intel_hackintosh/>this</a> guide for Alder Lake specific changes, as the Dortania website doesn't have a guide for Alder Lake yet</li>
<li>Huge thanks to the authors of all the guides I have mentioned in this post, as well as to OpenCore and the entire Hackintosh community!</li>
