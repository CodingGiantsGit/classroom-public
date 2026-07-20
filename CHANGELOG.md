## 2026-07-20

### Added
- Keyboard shortcuts for the meeting room — Alt+M/K to toggle mic/camera, Alt+C for chat, Alt+H for help, Alt+, and Alt+. to jump between shared screens, and holding Alt+X for push-to-talk; moderators also get Alt+L, Alt+G, Alt+P, and Alt+T for participants, grid view, screen pin, and the timer
- A "Keyboard Shortcuts" section in Settings listing every available shortcut

### Improved
- Grid view now arranges tiles more sensibly on narrower windows before switching to a side-by-side layout on wider screens
- Cancelling an AI assistant response now stops it immediately instead of continuing in the background
- Messages with numbered lists or plain dashed separators (e.g. `---`) now display correctly instead of showing garbled formatting
- URLs pasted inside a code block are now clickable links

### Fixed
- The AI assistant now shows a clear error instead of spinning forever if a response fails to load
- Clicking the focus icon on a raise-hand notification no longer leaves the screen-check timer in a stale state

## 2026-06-11

### Added
- Joining a lesson while already connected shows a warning dialog letting you choose to continue, open a second session for another device, or cancel

### Improved
- The "join additional session" option on the join screen is now a visible button, making multi-device setups easier to discover
- When a user is connected on two devices, moderator actions (mute, remove) now apply to both sessions at once
- Stop Recording now reliably stops all active streams even if the session reconnected after recording started

### Fixed
- A user joined from two devices no longer hears their own microphone played back from the second session
- The speaking indicator on a participant tile now lights up correctly when the user is speaking from either of their two active sessions

## 2026-05-26

### Improved
- Reconnections now show a clearer "performance issue detected" message and automatically lower video quality so the meeting recovers faster
- Participant videos in the side carousel only render when scrolled into view, easing CPU and bandwidth on lessons with many students
- Tablet-sized screens now get the full side-panel meeting layout instead of the narrow mobile layout
- Your own tile in the participant carousel now appears right after the teacher, before other students
- Screen-check timer label stays visible on every tile, even at the densest grid density
- Default classroom timer is now 5 minutes

### Fixed
- Duplicate join/leave notifications during brief reconnects are now suppressed
- Joining a lesson from the waiting room no longer gets stuck if the microphone, camera, or background effect fails to start
- Double-clicking the remove or pin controls on a participant tile no longer toggles the focused view by accident
## 2026-05-15

### Fixed
- Camera and screen-share tracks now display reliably on Firefox during lessons

## 2026-05-11

### Added
- Moderators can remove individual chat messages from the room chat
- Reactions and the focused-screen highlight ring can each be hidden from Settings → General
- Pinch-to-zoom and double-click controls in the meeting view for quickly focusing a participant or screen share

### Improved
- Control panel and settings dialog adapt better to small and narrow screens
- Grid layout density adjusts automatically based on the number of participants on screen
- Only the focused screen share plays audio when several are shared at once, preventing overlapping sound

## 2026-05-04

### Added
- Moderators can draw and annotate directly on top of a screen share, and the strokes are visible to all participants in both grid and carousel views
- Moderators can now cancel a running classroom timer with one click from the timer overlay
- Chat messages and emoji reactions are now rate-limited to prevent accidental spamming
- Timer sound can be toggled separately in the Notifications settings tab

### Improved
- Notification sound defaults are now tailored to the role — students hear screen-share requests by default and stay quiet otherwise, while moderators hear chat, join, leave, and raise-hand sounds
- Default notification volume lowered to 50% for a less intrusive classroom experience

## 2026-04-27

### Improved
- Joining a meeting no longer requires granting microphone permission upfront — participants can join muted and enable their mic at any time
- Visual Effects was update to use external library instead of custom implementation - environment settings.

## 2026-04-24

### Added
- Dark mode — switch between light, dark, and system theme from the new General section in Settings or from the join screen
- Raise hand button moved into the control bar, so it is always visible without covering the video area
- Moderators see a dedicated raise-hand notification with quick actions to focus the student's screen or lower their hand
- Pinned messages can now be collapsed to a small icon to keep the view clear

### Improved
- Leave confirmation dialog has a friendlier look with a cleaner layout
- Audio noise suppression is applied as soon as a student joins from the waiting room
- Chat and notification colors fully adapt to the active theme

## 2026-04-22

### Added
- A unified Settings panel consolidates video quality, visual effects, and notification sounds in one place
- Notification sound preferences — teachers and students can choose which sounds play (chat, join, leave, raise hand) and adjust their volume
- Speaking indicators next to participants in the sidebar list, so it's easy to see who is talking at a glance
- An explicit close button on dialogs for a clearer way to dismiss them

### Improved
- Grid view layout is more consistent and easier to manage, with clearer screen-check indicators
- Chat rendering handles long messages, links, and code snippets more cleanly, and auto-scrolls reliably
- Notification sounds are louder and play at full volume by default

## 2026-04-20

### Improved
- Participant tiles no longer dim when a participant is not speaking, keeping the classroom view consistent
- Virtual backgrounds are more stable and visually consistent during lessons
- Audio and video are now recorded as separate tracks, enabling more flexible post-lesson editing