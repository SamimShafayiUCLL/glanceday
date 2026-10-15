# Privacy

_Last updated: October 16, 2026 (version 1.1.0)_

Glanceday is built to keep your day on your phone.

**What stays on your phone.** Your tasks, lists, notes, settings and backups are stored only on your device. There is no account and no cloud sync. A backup file is only created when you choose "Back up", and it is saved wherever you pick.

**Calendar.** If you turn it on, Glanceday reads the calendars you select to show today's events. It never changes or uploads them.

**Weather.** If you turn weather on, Glanceday sends the coordinates of your place (from the city you typed, or your approximate location if you allow it) to the [MET Norway Locationforecast API](https://api.met.no/) to fetch the forecast. Nothing else is sent. MET Norway's own terms apply to that request.

**Task apps.** If you turn on Task apps, Glanceday reads tasks from Tasks.org or OpenTasks on your phone and marks them done there when you tick them off. Those apps handle any syncing (for example with Nextcloud); Glanceday sends nothing itself.

**Update check.** Unless you switch it off, Glanceday asks the GitHub Releases API at most once a day for the latest version number. That request includes no information about you or your tasks; GitHub sees it like any web request.

**Location.** Only approximate location is used, only for the weather, and only if you choose "use my location".

**No tracking.** Glanceday has no ads, analytics, crash reporting or third-party SDKs that collect data. Fonts are loaded through Android's built-in Google Fonts provider.

**Bug reports.** "Report a bug or idea" opens a GitHub issue form in your browser with your app version, Android version and phone model filled in. You can see and edit everything before you send it, and nothing is sent unless you submit the form.

**Questions.** Open an issue on this repository.
