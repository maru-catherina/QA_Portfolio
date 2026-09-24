# BUG-01: Intermittent playback stops while app remains open

**Severity:** High  
**Priority:** Medium  
**Type:** Functional / Background playback  
**Environment:** Samsung Galaxy S21, S23 Ultra, Coopers CP20 Pro 10" Tablet

### Description
Playback stops 1-2 times per week during long sessions  (2-3h), while the app process stays alive. Sometimes audio freezes.

### Steps to Reproduce
1. Open app and start any white noise track
2. Leave playback running in background for 2-3 hours
3. Use phone normally / lock screen
4. Observe

### Expected Result
Continuous uninterrupted playback while foreground service is active.

### Actual Result
- Audio stops. App UI still shows "Playing".
- Sometimes shows system message: "App frequently crashed" / app is put to sleep.
- Frequency: intermittent, ~1-2 times per 7-day cycle.

### Evidence
- Screenshot: 'white-noise-app/bug_reports/evidence/no-results.png`


### Tested on
- Samsung Galaxy S21 (Android 14)
- Samsung Galaxy S23 Ultra (Android 14)
- Coopers CP20 Pro 10" (Android 10)

### Notes
Issue not reproduced consistently. Suspected background restriction / Doze mode / audio focus loss. Needs check of foreground service + WakeLock.

