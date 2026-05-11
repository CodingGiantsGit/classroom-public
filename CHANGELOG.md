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