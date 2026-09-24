# Test Cases — DevZone Landing

**Environment:** Chrome 126, Firefox, Safari / Desktop & Mobile (iPhone 14, S23 Ultra)
**URL:** [devzone link]

| ID | Scenario | Priority | Steps | Expected Result | Actual Result | Status |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| TC-01 | Header loads logo + name | Low | 1. Open landing | Logo & "DevZone Studio" visible within 1s | As expected | PASS |
| TC-02 | CTA routes to contact form | High | 1. Click main CTA | Smooth scroll to #contact form | As expected | PASS |
| TC-03 | Navigation anchors work | Medium | 1. Click each nav link | Scroll to correct section, no 404 | As expected | PASS |
| TC-04 | Portfolio zoom on hover | Low | 1. Hover portfolio image | Image scales ~20% with transition | As expected | PASS |
| TC-05 | Watch Preview opens modal | High | 1. Click Watch Preview | Modal + overlay + autoplay | As expected | PASS |
| TC-06 | Hide video closes modal | High | 1. Click Hide / X / ESC | Modal closes, video stops | As expected | PASS |
| TC-07 | Contact form - Name validation | Medium | 1. Enter 1 char in Name 2. Submit | Error: "Min 2 characters" | No error, accepts 1 char | **FAIL** -> [BUG-01](https://github.com/maru-catherina/QA_Portfolio/blob/main/devzone-landing/bug_reports)|
| TC-08 | Contact form - Phone format | High | 1. Enter <11 / >11 digits 2. Submit | Error for invalid format | Error shown | PASS |
| TC-09 | Contact form - Email format | High | 1. Enter `test@` 2. Submit | Error: "Please enter valid email..." | Error shown, not submitted | PASS |
| TC-10 | Contact method toggle | Medium | 1. Switch Phone/Email/Telegram | Only one active, value saved | As expected | PASS |
| TC-11 | Contact form successful submit | Critical | 1. Fill valid data 2. Click Send | "Message sent successfully!" + fields cleared | As expected | PASS |
| TC-12 | Mobile menu open | Medium | 1. Resize to 375px 2. Click hamburger | Menu slides in | As expected | PASS |
| TC-13 | Mobile menu close (hamburger) | Medium | 1. Click hamburger again | Menu slides out | As expected | PASS |
| TC-14 | Mobile menu close (outside) | Low | 1. Open menu 2. Click outside | Menu closes | As expected | PASS |



