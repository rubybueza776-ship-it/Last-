SchoolTrack EAPIHS offline-first prototype.

Works: local inventory, add/edit/delete, borrow/return, repair/missing tracking, reports and JSON backups; local storage and basic offline caching when hosted over HTTPS.

Limitations: This is NOT a secure production app. Admin email/password are stored locally and do not verify email ownership. Data stays on each device; shared cloud sync is NOT configured. For shared multi-phone inventory, a Firebase project and secure authentication/database rules must be configured. Host on HTTPS, open online once, then use Chrome menu > Add to Home screen. Back up your data regularly.
