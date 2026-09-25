# White Noise App - Test Cases

## Manual Test Cases

| ID | Title | Preconditions | Steps | Expected Result | Status | Evidence |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| TC-WN-01 | Install from Play Store | Android device | 1. Open Play Store 2. Install White Noise | App installed | PASS | - |
| TC-WN-02 | Play sound | App installed | 1. Open app 2.Choose the sound 3. Tap Play | Sound plays | PASS | - |
| TC-WN-03 | Stop sound | Sound stops | 1. Tap Stop  | After tap the stop button the sound stopped  | PASS | - |
| TC-WN-04 | Timer 15m | App open | 1. Set 15m timer 2. Start | Stops after 15m | PASS | - |
| TC-WN-05 | Timer 30m | App open | 1. Set 30m timer 2. Start | Stops after 30m | PASS | - |
| TC-WN-06 | Timer 60m | App open | 1. Set 60m timer 2. Start | Stops after 60m | PASS | - |
| TC-WN-07 | Timer 120m | App open | 1. Set 120m timer 2. Start | Stops after 120m | PASS | - |
| TC-WN-08 | Timer 180m | App open | 1. Set 180m timer 2. Start | Stops after 180m | PASS | - |
| TC-WN-09 | Volume increase| Sound playing, volume not max | 1. Tap the button Volume + 2. Repeat until max| Volume increases, max limit works | PASS | - |
| TC-WN-10 | Volume decrease| Sound playing, volume not mute | 1. Tap the button Volume - 2. Repeat until mute| Volume decreases, min/mute works, no crash at 0 | PASS | - |
| TC-WN-11 | Background mode | Sound playing | 1. Minimize app / Lock screen | Sound continues | PASS | - |

## Production Monitoring (Post-Release)

| ID | Title | Preconditions | Steps | Expected Result | Status | Evidence |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| TC-WN-12 | Crash-free monitoring | App in Production ~1 year, last update Aug 2026 | 1. Open Play Console > Quality > Crashes & ANR | No crashes in last 28 days | PASS | [Screenshot](https://github.com/maru-catherina/QA_Portfolio/blob/main/white-noise-app/play-console-no-crashes.jpg)  |
| TC-WN-13 | ANR monitoring | App in Production | 1. Check ANR in Play Console | No ANR, 0 affected users | PASS | [Screenshot](https://github.com/maru-catherina/QA_Portfolio/blob/main/white-noise-app/play-console-no-crashes.jpg) |

## Evidence

[No Crashes](https://github.com/maru-catherina/QA_Portfolio/blob/main/white-noise-app/play-console-no-crashes.jpg) 

*Play Console: Aug 27 - Sep 24, 2026 - No results - 0 crashes, 0 ANR - Monitoring 28 days after Aug 2026 update*
