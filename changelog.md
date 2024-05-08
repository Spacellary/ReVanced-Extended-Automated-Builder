
<details> <summary>👀 inotia00/revanced-patches </summary>

**Release Version** - [v4.7.1](https://github.com/inotia00/revanced-patches/releases/tag/v4.7.1)<br>**Changelog** -<br> YouTube
==
- feat(YouTube): add support versions `19.03.36` ~ `19.16.39`
- feat(YouTube): add `Change shorts repeat state` patch
- feat(YouTube): add `Disable auto audio tracks` patch
- feat(YouTube): change patch name `Ambient mode switch` to `Ambient mode control`
- feat(YouTube): change patch name `Change player flyout panel toggles` to `Change player flyout menu toggles`
- feat(YouTube): change patch name `Disable shorts on startup` to `Disable resuming shorts on startup`
- feat(YouTube): change patch name `Hide description components` to `Description components`
- feat(YouTube): change patch name `Hide navigation bar components` to `Navigation bar components`
- feat(YouTube): change patch name `Hide shorts components` to `Shorts components`
- feat(YouTube): change patch name `Hide suggested video overlay` to `Fix suggested video end screen`
- feat(YouTube): change patch name `MicroG support` to `GmsCore support`
- feat(YouTube): integration of `Hide suggestions shelf` patch into `Hide feed components` patch
- feat(YouTube): remove support versions `18.25.40`, `18.27.36`
- feat(YouTube): remove `Add splash animation`, `Enable song search`, `Enable language switch`, `Force opus codec`, `Force video codec`, `Hide animated button background`, `Spoof player parameters` patch
- feat(YouTube): `Append time stamps information`, `Custom seekbar color`, `Enable seekbar tapping`, `Enable new thumbnail preview`, `Hide seekbar`, `Hide time stamp` patches have been integrated into `Seekbar components` patch
- feat(YouTube): `Custom playback speed`, `Disable HDR video`, `Default video quality`, `Default playback speed`, `Enable old quality layout`, `Spoof device dimensions` patches has been integrated into `Video playback` patch
- feat(YouTube): `Custom player overlay opacity`, `Disable speed overlay`, `Hide auto player popup panels`, `Hide channel watermark`, `Hide crowdfunding box`, `Hide end screen cards`, `Hide filmstrip overlay`, `Hide info cards`, `Hide seek message`, `Hide suggested actions`, `Hide suggested video overlay` patches has been integrated into `Player components` patch
- feat(YouTube): `Disable pip notification`, `Disable update screen`, `Hide account menu`, `Hide cast button`, `Hide floating microphone`, `Hide handle`, `Hide snack bar`, `Hide tooltip content` patches has been integrated into `Hide layout components` patch
- feat(YouTube): `Enable bottom player gestures` patch has been integrated into `Swipe controls` patch
- feat(YouTube): `Enable compact controls overlay`, `Force fullscreen`, `Hide autoplay preview`, `Hide end screen overlay`, `Hide fullscreen panels`, `Landscape mode`, `Quick actions components` patches has been integrated into `Fullscreen components` patch
- feat(YouTube): `Enable tablet navigation bar`, `Hide navigation label`, `Hide navigation buttons` patches have been integrated into `Hide navigation bar component` patch
- feat(YouTube): `Hide autoplay button`, `Hide captions button`, `Hide collapse button`, `Hide music button`, `Hide previous next button` patches has been integrated into `Hide player buttons` patch
- feat(YouTube): `Hide general ads`, `Hide video ads` have been integrated into `Hide ads` patch
- feat(YouTube): `Hide search term thumbnail`,  `Hide toolbar button`, `Hide trending searches`, `Hide voice search button`, `Premium heading` patches has been integrated into `Toolbar components` patch
- feat(YouTube/Alternative thumbnails): selectively enable for home / subscriptions / search
- feat(YouTube/Description components): add `Always expand panel` and `Disable description interaction` settings (YouTube v19.02.39+)
- feat(YouTube/Description components): add `Disable rolling number animations` settings
- feat(YouTube/Description components): `Hide game sections`, `Hide music sections`, `Hide place sections` settings have been integrated into `Hide suggestions sections` settings
- feat(YouTube/Disable update screen): remove settings
- feat(YouTube/Enable debug logging): included by default
- feat(YouTube/Enable tablet mini player): add `Enable modern mini player` settings (YouTube v19.12.41+)
- feat(YouTube/Hide ads): add `Hide fullscreen ads` settings
- feat(YouTube/Hide ads): remove `Close interstitial ads` settings
- feat(YouTube/Hide feed components): add `Channel tab filter` settings
- feat(YouTube/Hide feed components): add `Hide feed captions button` settings
- feat(YouTube/Hide feed components): add `Hide playables` settings
- feat(YouTube/Hide feed components): remove `Hide gray description` settings
- feat(YouTube/Hide feed components): remove `Hide store tab` settings
- feat(YouTube/Hide feed components): remove `Select method to hide shelves` settings in `Hide carousel shelf` settings
- feat(YouTube/Hide feed components): `Hide carousel shelf` setting no longer checks navigation index
- feat(YouTube/Hide feed components): `Hide suggestions shelf` setting has been renamed to the `Hide carousel shelf` setting.
- feat(YouTube/Hide layout components): custom filtering of the protocol buffer
- feat(YouTube/Hide layout components): filter home / search results by keywords
- feat(YouTube/Hide layout components): `Hide YouTube settings menu` settings
- feat(YouTube/Hide player flyout menu): add `Hide picture-in-picture menu` settings
- feat(YouTube/Overlay buttons): add `Hide fullscreen button` settings
- feat(YouTube/Overlay buttons): hook download button for feed flyout menu
- feat(YouTube/Overlay buttons): restore `Tap and hold to toggle pause after repeat states` features
- feat(YouTube/Player components): add `Skip autoplay countdown` settings
- feat(YouTube/Player components): add `Speed overlay value` settings
- feat(YouTube/Seekbar components): add `Hide seekbar chapters` settings
- feat(YouTube/Seekbar components): add `Replace time stamp action` settings
- feat(YouTube/Settings): changing the language in YouTube settings will also be reflected in RVX settings
- feat(YouTube/Settings): move SponsorBlock settings and Return YouTube Dislike settings to RVX Settings
- feat(YouTube/Settings): remove `Double back timeout` settings
- feat(YouTube/Shorts components): add `Return shorts channel name` settings
- feat(YouTube/Shorts components): match original ReVanced code
- feat(YouTube/Shorts components): remove the settings to hide each toolbar component, add settings to hide the entire toolbar
- feat(YouTube/Shorts components): selectively hide shorts shelves for home / subscription / search / history
- feat(YouTube/Spoof app version): add target version `17.33.42`
- feat(YouTube/Spoof app version): remove deprecated target versions
- feat(YouTube/Toolbar components): add `Enable wide search bar with header` settings
- feat(YouTube/Toolbar components): add `Replace create button` settings
- feat(YouTube/Video playback): add `Replace software AV1 codec` and `Reject software AV1 codec response` settings
- fix(YouTube/Client spoof): spoof all user agents
- fix(YouTube/Default video quality): applying default video quality to shorts causes the beginning of the shorts to get stuck in a loop
- fix(YouTube/Disable resuming shorts on startup): not worked due to A/B tests
- fix(YouTube/Disable resuming shorts on startup): patch does not work on `YouTube v18.29.38`
- fix(YouTube/Description components): `Hide shopping links` settings does not worked due to A/B tests
- fix(YouTube/Enable tablet mini player): title shifts down in fullscreen (YouTube v19.12.41+)
- fix(YouTube/GmsCore support): prompt to disable battery optimizations, if not done already
- fix(YouTube/Hide channel avatar section): not worked due to A/B tests
- fix(YouTube/Hide channel profile components): `Hide channel profile links` settings not worked due to A/B tests
- fix(YouTube/Hide comments component): `Hide thanks button` setting hides the Thanks button in shorts livestreams
- fix(YouTube/Hide feed components): `Hide subscriptions channel section` setting does not support tablet layout
- fix(YouTube/Hide player buttons): remove unused filter
- fix(YouTube/Hide player buttons): `Hide captions button` setting does not require set layout params
- fix(YouTube/Hide player buttons): `Hide collapse button` setting leaves a blank space in fullscreen
- fix(YouTube/Hide suggested video end screen): no longer closes the `suggested video end screen`, but instead follows the autoplay settings
- fix(YouTube/Hide suggestions shelf): not worked due to A/B tests
- fix(YouTube/Hide tooltip content): tooltip is not hidden in fullscreen
- fix(YouTube/Hide trending searches): patch does not support working latest version
- fix(YouTube/Overlay buttons): fix various issues
- fix(YouTube/Quick actions components): `Hide comment button` settings does not work
- fix(YouTube/Return YouTube Dislike): dislike counts not visible in incognito mode
- fix(YouTube/Return YouTube Dislike): do not clip compact text when not using English
- fix(YouTube/Return YouTube Dislike): do not show error toast if API success response contains new lines
- fix(YouTube/Return YouTube Dislike): hides the glow out animation in like dislike container
- fix(YouTube/Return YouTube Dislike): real-time likes/views are sometimes shown wrong
- fix(YouTube/Return YouTube Dislike): remove support for old layout (~YouTube v17.30.xx)
- fix(YouTube/Return YouTube Dislike): turning off RYD for shorts also disables it for regular videos
- fix(YouTube/Settings): contextual action bar has a background layer
- fix(YouTube/Settings): patches version in `Patch Information` is no longer updated manually
- fix(YouTube/Settings): when the user first installs the app and opens `Import/Export settings`, it is not an empty value
- fix(YouTube/Shorts components): hide shorts shelf in search result horizontal shelves
- fix(YouTube/SponsorBlock): modernize skip buttons
- fix(YouTube/SponsorBlock): segment time intervals are displayed incorrectly when the video length exceeds 24 hours
- fix(YouTube/Video playback): versions without default video quality restrictions do not validate video quality
- fix(YouTube/Video playback): `Restore old quality layout` settings does not apply to quality menu in shorts player
- refactor(YouTube/Settings): reorganize settings menu
- refactor(YouTube/Video information): include playback speed, video quality, channel id, channel name, video title, video length, livestream, playlist id
- feat(YouTube/Translations): update translation


YouTube Music
==
- feat(YouTube Music): add support versions `6.34.51` ~ `6.50.51`
- feat(YouTube Music): add `Disable dislike redirection` patch
- feat(YouTube Music): change patch name `Enable old style library shelf` to `Restore old style library shelf`
- feat(YouTube Music): change patch name `MicroG support` to `GmsCore support`
- feat(YouTube Music): remove support versions `6.21.52` ~ `6.28.53`
- feat(YouTube Music): remove `Enable old style miniplayer` patch
- feat(YouTube Music): remove `Enable playback speed` patch
- feat(YouTube Music): `Background play`, `Exclusive audio playback` patches have been integrated into `Enable minimized playback` patch
- feat(YouTube Music): `Enable black navigation bar`, `Hide navigation bar component` patches have been integrated into `Navigation bar components` patch
- feat(YouTube Music): `Enable color match player`, `Enable force minimized player`, `Enable old player background`, `Enable old player layout`, `Remember repeat state`, `Hide fullscreen share button`, `Remember shuffle state`, `Enable zen mode` patches have been integrated into `Player components` patch
- feat(YouTube Music): `Enable compact dialog`, `Hide flyout panel`, `Replace dismiss queue`, `Replace report` patches have been integrated into `Flyout menu components` patch
- feat(YouTube Music): `Enable custom filter`, `Hide button shelf`, `Hide carousel shelf`, `Hide cast button`, `Hide category bar`, `Hide channel guidelines`, `Hide emoji picker and time stamp`, `Hide new playlist button`, `Hide history button`, `Hide playlist card`, `Hide taste builder`, `Hide tooltip content`, `Hide voice search button` patches have been integrated into `Layout components` patch
- feat(YouTube Music): `Hide account menu`, `Hide handle`, `Hide terms container` patches have been integrated into `Hide account components` patch
- feat(YouTube Music): `Hide general ads`, `Hide get premium` patches have been integrated into `Hide ads` patch
- feat(YouTube Music/Enable debug logging): add `Enable debug buffer logging` settings
- feat(YouTube Music/Enable debug logging): included by default
- feat(YouTube Music/Flyout menu components): add `Enable trim silence` settings (YT Music v6.43.52+)
- feat(YouTube Music/Flyout menu components): add `Hide 3-column component` settings (YT Music v6.36.51+)
- feat(YouTube Music/Flyout menu components): add `Replace report` settings (alternative settings of `Enable playback speed` settings)
- feat(YouTube Music/Hide ads): add `Hide fullscreen ads` settings
- feat(YouTube Music/Hide ads): add `Hide paid promotion label` settings
- feat(YouTube Music/Hide layout components): add support for custom filtering of byte buffers to `Enable custom filter`
- feat(YouTube Music/Hide layout components): add `Hide notification button` settings (YT Music v6.42.52+)
- feat(YouTube Music/Hide layout components): add `Hide sound search button` settings (YT Music v6.48.51+)
- feat(YouTube Music/Hide layout components): add `Hide sample shelf`, `Hide tap to update button` settings
- feat(YouTube Music/Litho filter): add support for identifier and byte buffer
- feat(YouTube Music/Player components): add `Enable next previous button`, `Enable swipe to dismiss miniplayer` settings (alternative setting of `Enable old style miniplayer` patch)
- feat(YouTube Music/Player components): add `Enable zen mode in podcasts` settings
- feat(YouTube Music/Player components): add `Restore old comments popup panels` settings (YT Music v6.42.52+)
- feat(YouTube Music/Settings): move SponsorBlock settings and Return YouTube Dislike settings to RVX Settings
- fix(YouTube Music/Client spoof): spoof all user agents
- fix(YouTube Music/Custom playback speed): default playback speed preset does not match with stock value
- fix(YouTube Music/Custom playback speed): do not override when custom playback speed preset is the default
- fix(YouTube Music/Enable old player background): app crashes when the app is first installed after including the patch in a specific version
- fix(YouTube Music/GmsCore support): clicking the `Manage accounts` button causes app crash
- fix(YouTube Music/GmsCore support): prompt to disable battery optimizations, if not done already
- fix(YouTube Music/Return YouTube Dislike): Do not show error toast if API success response contains new lines
- fix(YouTube Music/Settings): issue in vanilla YouTube Music v6.44.52 causes exception
- fix(YouTube Music/Settings): `Import / Export settings` crashes when certain patches are excluded
- fix(YouTube Music/SponsorBlock): even if disables SponsorBlock, fetched segments still remain in the seek bar
- fix(YouTube Music/SponsorBlock): unable to export segment behavior
- fix(YouTube Music/Spoof app version): spoofing the app version with `6.11.52` also enables old style library shelves
- refactor(YouTube Music/Settings): reorganize settings menu
- refactor(YouTube Music/Video information): include playback speed and video quality
- feat(YouTube Music/Translations): update translation


Reddit
==
- feat(Reddit): restrict support version
- feat(Reddit): remove `Hide toolbar button` patch (deprecated until Reddit adds a button like r/place or Reddit recap button to the toolbar)


Etc
==
- build: bump dependencies
- build: bump gradle wrapper
- chore: add string format indexes, to allow more flexible translations
- chore: `ReadMeFileGenerator` no longer uses a hardcoded version of `README-template.md`
- feat(GmeCore support): switch to [ReVanced GmsCore](https://github.com/ReVanced/GmsCore/releases/latest) vendor
- fix(GmeCore support): add missing constants
- refactor: fix package and code structure
- refactor: fix patch structure

※ Playback issue some YouTube users are experiencing is not yet resolved.
※ Reddit 2024.18.0+ can only be patched via [CLI](https://github.com/inotia00/revanced-documentation/wiki/Supplement.-Patch-for-latest-Reddit).
※ Compatible ReVanced Manager: [RVX Manager v1.120.1 (fork)](https://github.com/inotia00/revanced-manager/releases/tag/v1.20.1)
[Crowdin translation]
- [YouTube/European Countries](https://crowdin.com/project/revancedextendedeu)
- [YouTube/Other Countries](https://crowdin.com/project/revancedextended)
- [YT Music](https://crowdin.com/project/revancedmusicextended)
**Published at** -<br> 2024-05-08T21:25:49Z<br><sub>Change logs generated by [Docker Py Revanced](https://github.com/nikhilbadyal/docker-py-revanced)</sub>
</details>
<details> <summary>👀 inotia00/revanced-patches </summary>

**Release Version** - [v4.7.1](https://github.com/inotia00/revanced-patches/releases/tag/v4.7.1)<br>**Changelog** -<br> YouTube
==
- feat(YouTube): add support versions `19.03.36` ~ `19.16.39`
- feat(YouTube): add `Change shorts repeat state` patch
- feat(YouTube): add `Disable auto audio tracks` patch
- feat(YouTube): change patch name `Ambient mode switch` to `Ambient mode control`
- feat(YouTube): change patch name `Change player flyout panel toggles` to `Change player flyout menu toggles`
- feat(YouTube): change patch name `Disable shorts on startup` to `Disable resuming shorts on startup`
- feat(YouTube): change patch name `Hide description components` to `Description components`
- feat(YouTube): change patch name `Hide navigation bar components` to `Navigation bar components`
- feat(YouTube): change patch name `Hide shorts components` to `Shorts components`
- feat(YouTube): change patch name `Hide suggested video overlay` to `Fix suggested video end screen`
- feat(YouTube): change patch name `MicroG support` to `GmsCore support`
- feat(YouTube): integration of `Hide suggestions shelf` patch into `Hide feed components` patch
- feat(YouTube): remove support versions `18.25.40`, `18.27.36`
- feat(YouTube): remove `Add splash animation`, `Enable song search`, `Enable language switch`, `Force opus codec`, `Force video codec`, `Hide animated button background`, `Spoof player parameters` patch
- feat(YouTube): `Append time stamps information`, `Custom seekbar color`, `Enable seekbar tapping`, `Enable new thumbnail preview`, `Hide seekbar`, `Hide time stamp` patches have been integrated into `Seekbar components` patch
- feat(YouTube): `Custom playback speed`, `Disable HDR video`, `Default video quality`, `Default playback speed`, `Enable old quality layout`, `Spoof device dimensions` patches has been integrated into `Video playback` patch
- feat(YouTube): `Custom player overlay opacity`, `Disable speed overlay`, `Hide auto player popup panels`, `Hide channel watermark`, `Hide crowdfunding box`, `Hide end screen cards`, `Hide filmstrip overlay`, `Hide info cards`, `Hide seek message`, `Hide suggested actions`, `Hide suggested video overlay` patches has been integrated into `Player components` patch
- feat(YouTube): `Disable pip notification`, `Disable update screen`, `Hide account menu`, `Hide cast button`, `Hide floating microphone`, `Hide handle`, `Hide snack bar`, `Hide tooltip content` patches has been integrated into `Hide layout components` patch
- feat(YouTube): `Enable bottom player gestures` patch has been integrated into `Swipe controls` patch
- feat(YouTube): `Enable compact controls overlay`, `Force fullscreen`, `Hide autoplay preview`, `Hide end screen overlay`, `Hide fullscreen panels`, `Landscape mode`, `Quick actions components` patches has been integrated into `Fullscreen components` patch
- feat(YouTube): `Enable tablet navigation bar`, `Hide navigation label`, `Hide navigation buttons` patches have been integrated into `Hide navigation bar component` patch
- feat(YouTube): `Hide autoplay button`, `Hide captions button`, `Hide collapse button`, `Hide music button`, `Hide previous next button` patches has been integrated into `Hide player buttons` patch
- feat(YouTube): `Hide general ads`, `Hide video ads` have been integrated into `Hide ads` patch
- feat(YouTube): `Hide search term thumbnail`,  `Hide toolbar button`, `Hide trending searches`, `Hide voice search button`, `Premium heading` patches has been integrated into `Toolbar components` patch
- feat(YouTube/Alternative thumbnails): selectively enable for home / subscriptions / search
- feat(YouTube/Description components): add `Always expand panel` and `Disable description interaction` settings (YouTube v19.02.39+)
- feat(YouTube/Description components): add `Disable rolling number animations` settings
- feat(YouTube/Description components): `Hide game sections`, `Hide music sections`, `Hide place sections` settings have been integrated into `Hide suggestions sections` settings
- feat(YouTube/Disable update screen): remove settings
- feat(YouTube/Enable debug logging): included by default
- feat(YouTube/Enable tablet mini player): add `Enable modern mini player` settings (YouTube v19.12.41+)
- feat(YouTube/Hide ads): add `Hide fullscreen ads` settings
- feat(YouTube/Hide ads): remove `Close interstitial ads` settings
- feat(YouTube/Hide feed components): add `Channel tab filter` settings
- feat(YouTube/Hide feed components): add `Hide feed captions button` settings
- feat(YouTube/Hide feed components): add `Hide playables` settings
- feat(YouTube/Hide feed components): remove `Hide gray description` settings
- feat(YouTube/Hide feed components): remove `Hide store tab` settings
- feat(YouTube/Hide feed components): remove `Select method to hide shelves` settings in `Hide carousel shelf` settings
- feat(YouTube/Hide feed components): `Hide carousel shelf` setting no longer checks navigation index
- feat(YouTube/Hide feed components): `Hide suggestions shelf` setting has been renamed to the `Hide carousel shelf` setting.
- feat(YouTube/Hide layout components): custom filtering of the protocol buffer
- feat(YouTube/Hide layout components): filter home / search results by keywords
- feat(YouTube/Hide layout components): `Hide YouTube settings menu` settings
- feat(YouTube/Hide player flyout menu): add `Hide picture-in-picture menu` settings
- feat(YouTube/Overlay buttons): add `Hide fullscreen button` settings
- feat(YouTube/Overlay buttons): hook download button for feed flyout menu
- feat(YouTube/Overlay buttons): restore `Tap and hold to toggle pause after repeat states` features
- feat(YouTube/Player components): add `Skip autoplay countdown` settings
- feat(YouTube/Player components): add `Speed overlay value` settings
- feat(YouTube/Seekbar components): add `Hide seekbar chapters` settings
- feat(YouTube/Seekbar components): add `Replace time stamp action` settings
- feat(YouTube/Settings): changing the language in YouTube settings will also be reflected in RVX settings
- feat(YouTube/Settings): move SponsorBlock settings and Return YouTube Dislike settings to RVX Settings
- feat(YouTube/Settings): remove `Double back timeout` settings
- feat(YouTube/Shorts components): add `Return shorts channel name` settings
- feat(YouTube/Shorts components): match original ReVanced code
- feat(YouTube/Shorts components): remove the settings to hide each toolbar component, add settings to hide the entire toolbar
- feat(YouTube/Shorts components): selectively hide shorts shelves for home / subscription / search / history
- feat(YouTube/Spoof app version): add target version `17.33.42`
- feat(YouTube/Spoof app version): remove deprecated target versions
- feat(YouTube/Toolbar components): add `Enable wide search bar with header` settings
- feat(YouTube/Toolbar components): add `Replace create button` settings
- feat(YouTube/Video playback): add `Replace software AV1 codec` and `Reject software AV1 codec response` settings
- fix(YouTube/Client spoof): spoof all user agents
- fix(YouTube/Default video quality): applying default video quality to shorts causes the beginning of the shorts to get stuck in a loop
- fix(YouTube/Disable resuming shorts on startup): not worked due to A/B tests
- fix(YouTube/Disable resuming shorts on startup): patch does not work on `YouTube v18.29.38`
- fix(YouTube/Description components): `Hide shopping links` settings does not worked due to A/B tests
- fix(YouTube/Enable tablet mini player): title shifts down in fullscreen (YouTube v19.12.41+)
- fix(YouTube/GmsCore support): prompt to disable battery optimizations, if not done already
- fix(YouTube/Hide channel avatar section): not worked due to A/B tests
- fix(YouTube/Hide channel profile components): `Hide channel profile links` settings not worked due to A/B tests
- fix(YouTube/Hide comments component): `Hide thanks button` setting hides the Thanks button in shorts livestreams
- fix(YouTube/Hide feed components): `Hide subscriptions channel section` setting does not support tablet layout
- fix(YouTube/Hide player buttons): remove unused filter
- fix(YouTube/Hide player buttons): `Hide captions button` setting does not require set layout params
- fix(YouTube/Hide player buttons): `Hide collapse button` setting leaves a blank space in fullscreen
- fix(YouTube/Hide suggested video end screen): no longer closes the `suggested video end screen`, but instead follows the autoplay settings
- fix(YouTube/Hide suggestions shelf): not worked due to A/B tests
- fix(YouTube/Hide tooltip content): tooltip is not hidden in fullscreen
- fix(YouTube/Hide trending searches): patch does not support working latest version
- fix(YouTube/Overlay buttons): fix various issues
- fix(YouTube/Quick actions components): `Hide comment button` settings does not work
- fix(YouTube/Return YouTube Dislike): dislike counts not visible in incognito mode
- fix(YouTube/Return YouTube Dislike): do not clip compact text when not using English
- fix(YouTube/Return YouTube Dislike): do not show error toast if API success response contains new lines
- fix(YouTube/Return YouTube Dislike): hides the glow out animation in like dislike container
- fix(YouTube/Return YouTube Dislike): real-time likes/views are sometimes shown wrong
- fix(YouTube/Return YouTube Dislike): remove support for old layout (~YouTube v17.30.xx)
- fix(YouTube/Return YouTube Dislike): turning off RYD for shorts also disables it for regular videos
- fix(YouTube/Settings): contextual action bar has a background layer
- fix(YouTube/Settings): patches version in `Patch Information` is no longer updated manually
- fix(YouTube/Settings): when the user first installs the app and opens `Import/Export settings`, it is not an empty value
- fix(YouTube/Shorts components): hide shorts shelf in search result horizontal shelves
- fix(YouTube/SponsorBlock): modernize skip buttons
- fix(YouTube/SponsorBlock): segment time intervals are displayed incorrectly when the video length exceeds 24 hours
- fix(YouTube/Video playback): versions without default video quality restrictions do not validate video quality
- fix(YouTube/Video playback): `Restore old quality layout` settings does not apply to quality menu in shorts player
- refactor(YouTube/Settings): reorganize settings menu
- refactor(YouTube/Video information): include playback speed, video quality, channel id, channel name, video title, video length, livestream, playlist id
- feat(YouTube/Translations): update translation


YouTube Music
==
- feat(YouTube Music): add support versions `6.34.51` ~ `6.50.51`
- feat(YouTube Music): add `Disable dislike redirection` patch
- feat(YouTube Music): change patch name `Enable old style library shelf` to `Restore old style library shelf`
- feat(YouTube Music): change patch name `MicroG support` to `GmsCore support`
- feat(YouTube Music): remove support versions `6.21.52` ~ `6.28.53`
- feat(YouTube Music): remove `Enable old style miniplayer` patch
- feat(YouTube Music): remove `Enable playback speed` patch
- feat(YouTube Music): `Background play`, `Exclusive audio playback` patches have been integrated into `Enable minimized playback` patch
- feat(YouTube Music): `Enable black navigation bar`, `Hide navigation bar component` patches have been integrated into `Navigation bar components` patch
- feat(YouTube Music): `Enable color match player`, `Enable force minimized player`, `Enable old player background`, `Enable old player layout`, `Remember repeat state`, `Hide fullscreen share button`, `Remember shuffle state`, `Enable zen mode` patches have been integrated into `Player components` patch
- feat(YouTube Music): `Enable compact dialog`, `Hide flyout panel`, `Replace dismiss queue`, `Replace report` patches have been integrated into `Flyout menu components` patch
- feat(YouTube Music): `Enable custom filter`, `Hide button shelf`, `Hide carousel shelf`, `Hide cast button`, `Hide category bar`, `Hide channel guidelines`, `Hide emoji picker and time stamp`, `Hide new playlist button`, `Hide history button`, `Hide playlist card`, `Hide taste builder`, `Hide tooltip content`, `Hide voice search button` patches have been integrated into `Layout components` patch
- feat(YouTube Music): `Hide account menu`, `Hide handle`, `Hide terms container` patches have been integrated into `Hide account components` patch
- feat(YouTube Music): `Hide general ads`, `Hide get premium` patches have been integrated into `Hide ads` patch
- feat(YouTube Music/Enable debug logging): add `Enable debug buffer logging` settings
- feat(YouTube Music/Enable debug logging): included by default
- feat(YouTube Music/Flyout menu components): add `Enable trim silence` settings (YT Music v6.43.52+)
- feat(YouTube Music/Flyout menu components): add `Hide 3-column component` settings (YT Music v6.36.51+)
- feat(YouTube Music/Flyout menu components): add `Replace report` settings (alternative settings of `Enable playback speed` settings)
- feat(YouTube Music/Hide ads): add `Hide fullscreen ads` settings
- feat(YouTube Music/Hide ads): add `Hide paid promotion label` settings
- feat(YouTube Music/Hide layout components): add support for custom filtering of byte buffers to `Enable custom filter`
- feat(YouTube Music/Hide layout components): add `Hide notification button` settings (YT Music v6.42.52+)
- feat(YouTube Music/Hide layout components): add `Hide sound search button` settings (YT Music v6.48.51+)
- feat(YouTube Music/Hide layout components): add `Hide sample shelf`, `Hide tap to update button` settings
- feat(YouTube Music/Litho filter): add support for identifier and byte buffer
- feat(YouTube Music/Player components): add `Enable next previous button`, `Enable swipe to dismiss miniplayer` settings (alternative setting of `Enable old style miniplayer` patch)
- feat(YouTube Music/Player components): add `Enable zen mode in podcasts` settings
- feat(YouTube Music/Player components): add `Restore old comments popup panels` settings (YT Music v6.42.52+)
- feat(YouTube Music/Settings): move SponsorBlock settings and Return YouTube Dislike settings to RVX Settings
- fix(YouTube Music/Client spoof): spoof all user agents
- fix(YouTube Music/Custom playback speed): default playback speed preset does not match with stock value
- fix(YouTube Music/Custom playback speed): do not override when custom playback speed preset is the default
- fix(YouTube Music/Enable old player background): app crashes when the app is first installed after including the patch in a specific version
- fix(YouTube Music/GmsCore support): clicking the `Manage accounts` button causes app crash
- fix(YouTube Music/GmsCore support): prompt to disable battery optimizations, if not done already
- fix(YouTube Music/Return YouTube Dislike): Do not show error toast if API success response contains new lines
- fix(YouTube Music/Settings): issue in vanilla YouTube Music v6.44.52 causes exception
- fix(YouTube Music/Settings): `Import / Export settings` crashes when certain patches are excluded
- fix(YouTube Music/SponsorBlock): even if disables SponsorBlock, fetched segments still remain in the seek bar
- fix(YouTube Music/SponsorBlock): unable to export segment behavior
- fix(YouTube Music/Spoof app version): spoofing the app version with `6.11.52` also enables old style library shelves
- refactor(YouTube Music/Settings): reorganize settings menu
- refactor(YouTube Music/Video information): include playback speed and video quality
- feat(YouTube Music/Translations): update translation


Reddit
==
- feat(Reddit): restrict support version
- feat(Reddit): remove `Hide toolbar button` patch (deprecated until Reddit adds a button like r/place or Reddit recap button to the toolbar)


Etc
==
- build: bump dependencies
- build: bump gradle wrapper
- chore: add string format indexes, to allow more flexible translations
- chore: `ReadMeFileGenerator` no longer uses a hardcoded version of `README-template.md`
- feat(GmeCore support): switch to [ReVanced GmsCore](https://github.com/ReVanced/GmsCore/releases/latest) vendor
- fix(GmeCore support): add missing constants
- refactor: fix package and code structure
- refactor: fix patch structure

※ Playback issue some YouTube users are experiencing is not yet resolved.
※ Reddit 2024.18.0+ can only be patched via [CLI](https://github.com/inotia00/revanced-documentation/wiki/Supplement.-Patch-for-latest-Reddit).
※ Compatible ReVanced Manager: [RVX Manager v1.120.1 (fork)](https://github.com/inotia00/revanced-manager/releases/tag/v1.20.1)
[Crowdin translation]
- [YouTube/European Countries](https://crowdin.com/project/revancedextendedeu)
- [YouTube/Other Countries](https://crowdin.com/project/revancedextended)
- [YT Music](https://crowdin.com/project/revancedmusicextended)
**Published at** -<br> 2024-05-08T21:25:49Z<br><sub>Change logs generated by [Docker Py Revanced](https://github.com/nikhilbadyal/docker-py-revanced)</sub>
</details>
<details> <summary>👀 inotia00/revanced-cli </summary>

**Release Version** - [v4.6.1](https://github.com/inotia00/revanced-cli/releases/tag/v4.6.1)<br>**Changelog** -<br> - build: update dependencies
- feat: rollback the default values of keystore alias and password to CLI v3.0 (compatible with old keystore)
- rollback: move ReVanced Library subproject to another repository

※ support `--unsigned` and `--rip-lib` commands #[j-hc/revanced-cli](https://github.com/j-hc/revanced-cli)**Published at** -<br> 2024-05-08T17:59:05Z<br><sub>Change logs generated by [Docker Py Revanced](https://github.com/nikhilbadyal/docker-py-revanced)</sub>
</details>
<details> <summary>👀 inotia00/revanced-integrations </summary>

**Release Version** - [v1.8.2](https://github.com/inotia00/revanced-integrations/releases/tag/v1.8.2)<br>**Changelog** -<br> - fix(YouTube/Hide cast button): add missing class https://github.com/inotia00/ReVanced_Extended/issues/1955**Published at** -<br> 2024-05-08T21:55:25Z<br><sub>Change logs generated by [Docker Py Revanced](https://github.com/nikhilbadyal/docker-py-revanced)</sub>
</details>
<details> <summary>👀 inotia00/revanced-cli </summary>

**Release Version** - [v4.6.1](https://github.com/inotia00/revanced-cli/releases/tag/v4.6.1)<br>**Changelog** -<br> - build: update dependencies
- feat: rollback the default values of keystore alias and password to CLI v3.0 (compatible with old keystore)
- rollback: move ReVanced Library subproject to another repository

※ support `--unsigned` and `--rip-lib` commands #[j-hc/revanced-cli](https://github.com/j-hc/revanced-cli)**Published at** -<br> 2024-05-08T17:59:05Z<br><sub>Change logs generated by [Docker Py Revanced](https://github.com/nikhilbadyal/docker-py-revanced)</sub>
</details>
<details> <summary>👀 inotia00/revanced-patches </summary>

**Release Version** - [v4.7.1](https://github.com/inotia00/revanced-patches/releases/tag/v4.7.1)<br>**Changelog** -<br> YouTube
==
- feat(YouTube): add support versions `19.03.36` ~ `19.16.39`
- feat(YouTube): add `Change shorts repeat state` patch
- feat(YouTube): add `Disable auto audio tracks` patch
- feat(YouTube): change patch name `Ambient mode switch` to `Ambient mode control`
- feat(YouTube): change patch name `Change player flyout panel toggles` to `Change player flyout menu toggles`
- feat(YouTube): change patch name `Disable shorts on startup` to `Disable resuming shorts on startup`
- feat(YouTube): change patch name `Hide description components` to `Description components`
- feat(YouTube): change patch name `Hide navigation bar components` to `Navigation bar components`
- feat(YouTube): change patch name `Hide shorts components` to `Shorts components`
- feat(YouTube): change patch name `Hide suggested video overlay` to `Fix suggested video end screen`
- feat(YouTube): change patch name `MicroG support` to `GmsCore support`
- feat(YouTube): integration of `Hide suggestions shelf` patch into `Hide feed components` patch
- feat(YouTube): remove support versions `18.25.40`, `18.27.36`
- feat(YouTube): remove `Add splash animation`, `Enable song search`, `Enable language switch`, `Force opus codec`, `Force video codec`, `Hide animated button background`, `Spoof player parameters` patch
- feat(YouTube): `Append time stamps information`, `Custom seekbar color`, `Enable seekbar tapping`, `Enable new thumbnail preview`, `Hide seekbar`, `Hide time stamp` patches have been integrated into `Seekbar components` patch
- feat(YouTube): `Custom playback speed`, `Disable HDR video`, `Default video quality`, `Default playback speed`, `Enable old quality layout`, `Spoof device dimensions` patches has been integrated into `Video playback` patch
- feat(YouTube): `Custom player overlay opacity`, `Disable speed overlay`, `Hide auto player popup panels`, `Hide channel watermark`, `Hide crowdfunding box`, `Hide end screen cards`, `Hide filmstrip overlay`, `Hide info cards`, `Hide seek message`, `Hide suggested actions`, `Hide suggested video overlay` patches has been integrated into `Player components` patch
- feat(YouTube): `Disable pip notification`, `Disable update screen`, `Hide account menu`, `Hide cast button`, `Hide floating microphone`, `Hide handle`, `Hide snack bar`, `Hide tooltip content` patches has been integrated into `Hide layout components` patch
- feat(YouTube): `Enable bottom player gestures` patch has been integrated into `Swipe controls` patch
- feat(YouTube): `Enable compact controls overlay`, `Force fullscreen`, `Hide autoplay preview`, `Hide end screen overlay`, `Hide fullscreen panels`, `Landscape mode`, `Quick actions components` patches has been integrated into `Fullscreen components` patch
- feat(YouTube): `Enable tablet navigation bar`, `Hide navigation label`, `Hide navigation buttons` patches have been integrated into `Hide navigation bar component` patch
- feat(YouTube): `Hide autoplay button`, `Hide captions button`, `Hide collapse button`, `Hide music button`, `Hide previous next button` patches has been integrated into `Hide player buttons` patch
- feat(YouTube): `Hide general ads`, `Hide video ads` have been integrated into `Hide ads` patch
- feat(YouTube): `Hide search term thumbnail`,  `Hide toolbar button`, `Hide trending searches`, `Hide voice search button`, `Premium heading` patches has been integrated into `Toolbar components` patch
- feat(YouTube/Alternative thumbnails): selectively enable for home / subscriptions / search
- feat(YouTube/Description components): add `Always expand panel` and `Disable description interaction` settings (YouTube v19.02.39+)
- feat(YouTube/Description components): add `Disable rolling number animations` settings
- feat(YouTube/Description components): `Hide game sections`, `Hide music sections`, `Hide place sections` settings have been integrated into `Hide suggestions sections` settings
- feat(YouTube/Disable update screen): remove settings
- feat(YouTube/Enable debug logging): included by default
- feat(YouTube/Enable tablet mini player): add `Enable modern mini player` settings (YouTube v19.12.41+)
- feat(YouTube/Hide ads): add `Hide fullscreen ads` settings
- feat(YouTube/Hide ads): remove `Close interstitial ads` settings
- feat(YouTube/Hide feed components): add `Channel tab filter` settings
- feat(YouTube/Hide feed components): add `Hide feed captions button` settings
- feat(YouTube/Hide feed components): add `Hide playables` settings
- feat(YouTube/Hide feed components): remove `Hide gray description` settings
- feat(YouTube/Hide feed components): remove `Hide store tab` settings
- feat(YouTube/Hide feed components): remove `Select method to hide shelves` settings in `Hide carousel shelf` settings
- feat(YouTube/Hide feed components): `Hide carousel shelf` setting no longer checks navigation index
- feat(YouTube/Hide feed components): `Hide suggestions shelf` setting has been renamed to the `Hide carousel shelf` setting.
- feat(YouTube/Hide layout components): custom filtering of the protocol buffer
- feat(YouTube/Hide layout components): filter home / search results by keywords
- feat(YouTube/Hide layout components): `Hide YouTube settings menu` settings
- feat(YouTube/Hide player flyout menu): add `Hide picture-in-picture menu` settings
- feat(YouTube/Overlay buttons): add `Hide fullscreen button` settings
- feat(YouTube/Overlay buttons): hook download button for feed flyout menu
- feat(YouTube/Overlay buttons): restore `Tap and hold to toggle pause after repeat states` features
- feat(YouTube/Player components): add `Skip autoplay countdown` settings
- feat(YouTube/Player components): add `Speed overlay value` settings
- feat(YouTube/Seekbar components): add `Hide seekbar chapters` settings
- feat(YouTube/Seekbar components): add `Replace time stamp action` settings
- feat(YouTube/Settings): changing the language in YouTube settings will also be reflected in RVX settings
- feat(YouTube/Settings): move SponsorBlock settings and Return YouTube Dislike settings to RVX Settings
- feat(YouTube/Settings): remove `Double back timeout` settings
- feat(YouTube/Shorts components): add `Return shorts channel name` settings
- feat(YouTube/Shorts components): match original ReVanced code
- feat(YouTube/Shorts components): remove the settings to hide each toolbar component, add settings to hide the entire toolbar
- feat(YouTube/Shorts components): selectively hide shorts shelves for home / subscription / search / history
- feat(YouTube/Spoof app version): add target version `17.33.42`
- feat(YouTube/Spoof app version): remove deprecated target versions
- feat(YouTube/Toolbar components): add `Enable wide search bar with header` settings
- feat(YouTube/Toolbar components): add `Replace create button` settings
- feat(YouTube/Video playback): add `Replace software AV1 codec` and `Reject software AV1 codec response` settings
- fix(YouTube/Client spoof): spoof all user agents
- fix(YouTube/Default video quality): applying default video quality to shorts causes the beginning of the shorts to get stuck in a loop
- fix(YouTube/Disable resuming shorts on startup): not worked due to A/B tests
- fix(YouTube/Disable resuming shorts on startup): patch does not work on `YouTube v18.29.38`
- fix(YouTube/Description components): `Hide shopping links` settings does not worked due to A/B tests
- fix(YouTube/Enable tablet mini player): title shifts down in fullscreen (YouTube v19.12.41+)
- fix(YouTube/GmsCore support): prompt to disable battery optimizations, if not done already
- fix(YouTube/Hide channel avatar section): not worked due to A/B tests
- fix(YouTube/Hide channel profile components): `Hide channel profile links` settings not worked due to A/B tests
- fix(YouTube/Hide comments component): `Hide thanks button` setting hides the Thanks button in shorts livestreams
- fix(YouTube/Hide feed components): `Hide subscriptions channel section` setting does not support tablet layout
- fix(YouTube/Hide player buttons): remove unused filter
- fix(YouTube/Hide player buttons): `Hide captions button` setting does not require set layout params
- fix(YouTube/Hide player buttons): `Hide collapse button` setting leaves a blank space in fullscreen
- fix(YouTube/Hide suggested video end screen): no longer closes the `suggested video end screen`, but instead follows the autoplay settings
- fix(YouTube/Hide suggestions shelf): not worked due to A/B tests
- fix(YouTube/Hide tooltip content): tooltip is not hidden in fullscreen
- fix(YouTube/Hide trending searches): patch does not support working latest version
- fix(YouTube/Overlay buttons): fix various issues
- fix(YouTube/Quick actions components): `Hide comment button` settings does not work
- fix(YouTube/Return YouTube Dislike): dislike counts not visible in incognito mode
- fix(YouTube/Return YouTube Dislike): do not clip compact text when not using English
- fix(YouTube/Return YouTube Dislike): do not show error toast if API success response contains new lines
- fix(YouTube/Return YouTube Dislike): hides the glow out animation in like dislike container
- fix(YouTube/Return YouTube Dislike): real-time likes/views are sometimes shown wrong
- fix(YouTube/Return YouTube Dislike): remove support for old layout (~YouTube v17.30.xx)
- fix(YouTube/Return YouTube Dislike): turning off RYD for shorts also disables it for regular videos
- fix(YouTube/Settings): contextual action bar has a background layer
- fix(YouTube/Settings): patches version in `Patch Information` is no longer updated manually
- fix(YouTube/Settings): when the user first installs the app and opens `Import/Export settings`, it is not an empty value
- fix(YouTube/Shorts components): hide shorts shelf in search result horizontal shelves
- fix(YouTube/SponsorBlock): modernize skip buttons
- fix(YouTube/SponsorBlock): segment time intervals are displayed incorrectly when the video length exceeds 24 hours
- fix(YouTube/Video playback): versions without default video quality restrictions do not validate video quality
- fix(YouTube/Video playback): `Restore old quality layout` settings does not apply to quality menu in shorts player
- refactor(YouTube/Settings): reorganize settings menu
- refactor(YouTube/Video information): include playback speed, video quality, channel id, channel name, video title, video length, livestream, playlist id
- feat(YouTube/Translations): update translation


YouTube Music
==
- feat(YouTube Music): add support versions `6.34.51` ~ `6.50.51`
- feat(YouTube Music): add `Disable dislike redirection` patch
- feat(YouTube Music): change patch name `Enable old style library shelf` to `Restore old style library shelf`
- feat(YouTube Music): change patch name `MicroG support` to `GmsCore support`
- feat(YouTube Music): remove support versions `6.21.52` ~ `6.28.53`
- feat(YouTube Music): remove `Enable old style miniplayer` patch
- feat(YouTube Music): remove `Enable playback speed` patch
- feat(YouTube Music): `Background play`, `Exclusive audio playback` patches have been integrated into `Enable minimized playback` patch
- feat(YouTube Music): `Enable black navigation bar`, `Hide navigation bar component` patches have been integrated into `Navigation bar components` patch
- feat(YouTube Music): `Enable color match player`, `Enable force minimized player`, `Enable old player background`, `Enable old player layout`, `Remember repeat state`, `Hide fullscreen share button`, `Remember shuffle state`, `Enable zen mode` patches have been integrated into `Player components` patch
- feat(YouTube Music): `Enable compact dialog`, `Hide flyout panel`, `Replace dismiss queue`, `Replace report` patches have been integrated into `Flyout menu components` patch
- feat(YouTube Music): `Enable custom filter`, `Hide button shelf`, `Hide carousel shelf`, `Hide cast button`, `Hide category bar`, `Hide channel guidelines`, `Hide emoji picker and time stamp`, `Hide new playlist button`, `Hide history button`, `Hide playlist card`, `Hide taste builder`, `Hide tooltip content`, `Hide voice search button` patches have been integrated into `Layout components` patch
- feat(YouTube Music): `Hide account menu`, `Hide handle`, `Hide terms container` patches have been integrated into `Hide account components` patch
- feat(YouTube Music): `Hide general ads`, `Hide get premium` patches have been integrated into `Hide ads` patch
- feat(YouTube Music/Enable debug logging): add `Enable debug buffer logging` settings
- feat(YouTube Music/Enable debug logging): included by default
- feat(YouTube Music/Flyout menu components): add `Enable trim silence` settings (YT Music v6.43.52+)
- feat(YouTube Music/Flyout menu components): add `Hide 3-column component` settings (YT Music v6.36.51+)
- feat(YouTube Music/Flyout menu components): add `Replace report` settings (alternative settings of `Enable playback speed` settings)
- feat(YouTube Music/Hide ads): add `Hide fullscreen ads` settings
- feat(YouTube Music/Hide ads): add `Hide paid promotion label` settings
- feat(YouTube Music/Hide layout components): add support for custom filtering of byte buffers to `Enable custom filter`
- feat(YouTube Music/Hide layout components): add `Hide notification button` settings (YT Music v6.42.52+)
- feat(YouTube Music/Hide layout components): add `Hide sound search button` settings (YT Music v6.48.51+)
- feat(YouTube Music/Hide layout components): add `Hide sample shelf`, `Hide tap to update button` settings
- feat(YouTube Music/Litho filter): add support for identifier and byte buffer
- feat(YouTube Music/Player components): add `Enable next previous button`, `Enable swipe to dismiss miniplayer` settings (alternative setting of `Enable old style miniplayer` patch)
- feat(YouTube Music/Player components): add `Enable zen mode in podcasts` settings
- feat(YouTube Music/Player components): add `Restore old comments popup panels` settings (YT Music v6.42.52+)
- feat(YouTube Music/Settings): move SponsorBlock settings and Return YouTube Dislike settings to RVX Settings
- fix(YouTube Music/Client spoof): spoof all user agents
- fix(YouTube Music/Custom playback speed): default playback speed preset does not match with stock value
- fix(YouTube Music/Custom playback speed): do not override when custom playback speed preset is the default
- fix(YouTube Music/Enable old player background): app crashes when the app is first installed after including the patch in a specific version
- fix(YouTube Music/GmsCore support): clicking the `Manage accounts` button causes app crash
- fix(YouTube Music/GmsCore support): prompt to disable battery optimizations, if not done already
- fix(YouTube Music/Return YouTube Dislike): Do not show error toast if API success response contains new lines
- fix(YouTube Music/Settings): issue in vanilla YouTube Music v6.44.52 causes exception
- fix(YouTube Music/Settings): `Import / Export settings` crashes when certain patches are excluded
- fix(YouTube Music/SponsorBlock): even if disables SponsorBlock, fetched segments still remain in the seek bar
- fix(YouTube Music/SponsorBlock): unable to export segment behavior
- fix(YouTube Music/Spoof app version): spoofing the app version with `6.11.52` also enables old style library shelves
- refactor(YouTube Music/Settings): reorganize settings menu
- refactor(YouTube Music/Video information): include playback speed and video quality
- feat(YouTube Music/Translations): update translation


Reddit
==
- feat(Reddit): restrict support version
- feat(Reddit): remove `Hide toolbar button` patch (deprecated until Reddit adds a button like r/place or Reddit recap button to the toolbar)


Etc
==
- build: bump dependencies
- build: bump gradle wrapper
- chore: add string format indexes, to allow more flexible translations
- chore: `ReadMeFileGenerator` no longer uses a hardcoded version of `README-template.md`
- feat(GmeCore support): switch to [ReVanced GmsCore](https://github.com/ReVanced/GmsCore/releases/latest) vendor
- fix(GmeCore support): add missing constants
- refactor: fix package and code structure
- refactor: fix patch structure

※ Playback issue some YouTube users are experiencing is not yet resolved.
※ Reddit 2024.18.0+ can only be patched via [CLI](https://github.com/inotia00/revanced-documentation/wiki/Supplement.-Patch-for-latest-Reddit).
※ Compatible ReVanced Manager: [RVX Manager v1.120.1 (fork)](https://github.com/inotia00/revanced-manager/releases/tag/v1.20.1)
[Crowdin translation]
- [YouTube/European Countries](https://crowdin.com/project/revancedextendedeu)
- [YouTube/Other Countries](https://crowdin.com/project/revancedextended)
- [YT Music](https://crowdin.com/project/revancedmusicextended)
**Published at** -<br> 2024-05-08T21:25:49Z<br><sub>Change logs generated by [Docker Py Revanced](https://github.com/nikhilbadyal/docker-py-revanced)</sub>
</details>
<details> <summary>👀 inotia00/revanced-integrations </summary>

**Release Version** - [v1.8.2](https://github.com/inotia00/revanced-integrations/releases/tag/v1.8.2)<br>**Changelog** -<br> - fix(YouTube/Hide cast button): add missing class https://github.com/inotia00/ReVanced_Extended/issues/1955**Published at** -<br> 2024-05-08T21:55:25Z<br><sub>Change logs generated by [Docker Py Revanced](https://github.com/nikhilbadyal/docker-py-revanced)</sub>
</details>
<details> <summary>👀 inotia00/revanced-patches </summary>

**Release Version** - [v4.7.1](https://github.com/inotia00/revanced-patches/releases/tag/v4.7.1)<br>**Changelog** -<br> YouTube
==
- feat(YouTube): add support versions `19.03.36` ~ `19.16.39`
- feat(YouTube): add `Change shorts repeat state` patch
- feat(YouTube): add `Disable auto audio tracks` patch
- feat(YouTube): change patch name `Ambient mode switch` to `Ambient mode control`
- feat(YouTube): change patch name `Change player flyout panel toggles` to `Change player flyout menu toggles`
- feat(YouTube): change patch name `Disable shorts on startup` to `Disable resuming shorts on startup`
- feat(YouTube): change patch name `Hide description components` to `Description components`
- feat(YouTube): change patch name `Hide navigation bar components` to `Navigation bar components`
- feat(YouTube): change patch name `Hide shorts components` to `Shorts components`
- feat(YouTube): change patch name `Hide suggested video overlay` to `Fix suggested video end screen`
- feat(YouTube): change patch name `MicroG support` to `GmsCore support`
- feat(YouTube): integration of `Hide suggestions shelf` patch into `Hide feed components` patch
- feat(YouTube): remove support versions `18.25.40`, `18.27.36`
- feat(YouTube): remove `Add splash animation`, `Enable song search`, `Enable language switch`, `Force opus codec`, `Force video codec`, `Hide animated button background`, `Spoof player parameters` patch
- feat(YouTube): `Append time stamps information`, `Custom seekbar color`, `Enable seekbar tapping`, `Enable new thumbnail preview`, `Hide seekbar`, `Hide time stamp` patches have been integrated into `Seekbar components` patch
- feat(YouTube): `Custom playback speed`, `Disable HDR video`, `Default video quality`, `Default playback speed`, `Enable old quality layout`, `Spoof device dimensions` patches has been integrated into `Video playback` patch
- feat(YouTube): `Custom player overlay opacity`, `Disable speed overlay`, `Hide auto player popup panels`, `Hide channel watermark`, `Hide crowdfunding box`, `Hide end screen cards`, `Hide filmstrip overlay`, `Hide info cards`, `Hide seek message`, `Hide suggested actions`, `Hide suggested video overlay` patches has been integrated into `Player components` patch
- feat(YouTube): `Disable pip notification`, `Disable update screen`, `Hide account menu`, `Hide cast button`, `Hide floating microphone`, `Hide handle`, `Hide snack bar`, `Hide tooltip content` patches has been integrated into `Hide layout components` patch
- feat(YouTube): `Enable bottom player gestures` patch has been integrated into `Swipe controls` patch
- feat(YouTube): `Enable compact controls overlay`, `Force fullscreen`, `Hide autoplay preview`, `Hide end screen overlay`, `Hide fullscreen panels`, `Landscape mode`, `Quick actions components` patches has been integrated into `Fullscreen components` patch
- feat(YouTube): `Enable tablet navigation bar`, `Hide navigation label`, `Hide navigation buttons` patches have been integrated into `Hide navigation bar component` patch
- feat(YouTube): `Hide autoplay button`, `Hide captions button`, `Hide collapse button`, `Hide music button`, `Hide previous next button` patches has been integrated into `Hide player buttons` patch
- feat(YouTube): `Hide general ads`, `Hide video ads` have been integrated into `Hide ads` patch
- feat(YouTube): `Hide search term thumbnail`,  `Hide toolbar button`, `Hide trending searches`, `Hide voice search button`, `Premium heading` patches has been integrated into `Toolbar components` patch
- feat(YouTube/Alternative thumbnails): selectively enable for home / subscriptions / search
- feat(YouTube/Description components): add `Always expand panel` and `Disable description interaction` settings (YouTube v19.02.39+)
- feat(YouTube/Description components): add `Disable rolling number animations` settings
- feat(YouTube/Description components): `Hide game sections`, `Hide music sections`, `Hide place sections` settings have been integrated into `Hide suggestions sections` settings
- feat(YouTube/Disable update screen): remove settings
- feat(YouTube/Enable debug logging): included by default
- feat(YouTube/Enable tablet mini player): add `Enable modern mini player` settings (YouTube v19.12.41+)
- feat(YouTube/Hide ads): add `Hide fullscreen ads` settings
- feat(YouTube/Hide ads): remove `Close interstitial ads` settings
- feat(YouTube/Hide feed components): add `Channel tab filter` settings
- feat(YouTube/Hide feed components): add `Hide feed captions button` settings
- feat(YouTube/Hide feed components): add `Hide playables` settings
- feat(YouTube/Hide feed components): remove `Hide gray description` settings
- feat(YouTube/Hide feed components): remove `Hide store tab` settings
- feat(YouTube/Hide feed components): remove `Select method to hide shelves` settings in `Hide carousel shelf` settings
- feat(YouTube/Hide feed components): `Hide carousel shelf` setting no longer checks navigation index
- feat(YouTube/Hide feed components): `Hide suggestions shelf` setting has been renamed to the `Hide carousel shelf` setting.
- feat(YouTube/Hide layout components): custom filtering of the protocol buffer
- feat(YouTube/Hide layout components): filter home / search results by keywords
- feat(YouTube/Hide layout components): `Hide YouTube settings menu` settings
- feat(YouTube/Hide player flyout menu): add `Hide picture-in-picture menu` settings
- feat(YouTube/Overlay buttons): add `Hide fullscreen button` settings
- feat(YouTube/Overlay buttons): hook download button for feed flyout menu
- feat(YouTube/Overlay buttons): restore `Tap and hold to toggle pause after repeat states` features
- feat(YouTube/Player components): add `Skip autoplay countdown` settings
- feat(YouTube/Player components): add `Speed overlay value` settings
- feat(YouTube/Seekbar components): add `Hide seekbar chapters` settings
- feat(YouTube/Seekbar components): add `Replace time stamp action` settings
- feat(YouTube/Settings): changing the language in YouTube settings will also be reflected in RVX settings
- feat(YouTube/Settings): move SponsorBlock settings and Return YouTube Dislike settings to RVX Settings
- feat(YouTube/Settings): remove `Double back timeout` settings
- feat(YouTube/Shorts components): add `Return shorts channel name` settings
- feat(YouTube/Shorts components): match original ReVanced code
- feat(YouTube/Shorts components): remove the settings to hide each toolbar component, add settings to hide the entire toolbar
- feat(YouTube/Shorts components): selectively hide shorts shelves for home / subscription / search / history
- feat(YouTube/Spoof app version): add target version `17.33.42`
- feat(YouTube/Spoof app version): remove deprecated target versions
- feat(YouTube/Toolbar components): add `Enable wide search bar with header` settings
- feat(YouTube/Toolbar components): add `Replace create button` settings
- feat(YouTube/Video playback): add `Replace software AV1 codec` and `Reject software AV1 codec response` settings
- fix(YouTube/Client spoof): spoof all user agents
- fix(YouTube/Default video quality): applying default video quality to shorts causes the beginning of the shorts to get stuck in a loop
- fix(YouTube/Disable resuming shorts on startup): not worked due to A/B tests
- fix(YouTube/Disable resuming shorts on startup): patch does not work on `YouTube v18.29.38`
- fix(YouTube/Description components): `Hide shopping links` settings does not worked due to A/B tests
- fix(YouTube/Enable tablet mini player): title shifts down in fullscreen (YouTube v19.12.41+)
- fix(YouTube/GmsCore support): prompt to disable battery optimizations, if not done already
- fix(YouTube/Hide channel avatar section): not worked due to A/B tests
- fix(YouTube/Hide channel profile components): `Hide channel profile links` settings not worked due to A/B tests
- fix(YouTube/Hide comments component): `Hide thanks button` setting hides the Thanks button in shorts livestreams
- fix(YouTube/Hide feed components): `Hide subscriptions channel section` setting does not support tablet layout
- fix(YouTube/Hide player buttons): remove unused filter
- fix(YouTube/Hide player buttons): `Hide captions button` setting does not require set layout params
- fix(YouTube/Hide player buttons): `Hide collapse button` setting leaves a blank space in fullscreen
- fix(YouTube/Hide suggested video end screen): no longer closes the `suggested video end screen`, but instead follows the autoplay settings
- fix(YouTube/Hide suggestions shelf): not worked due to A/B tests
- fix(YouTube/Hide tooltip content): tooltip is not hidden in fullscreen
- fix(YouTube/Hide trending searches): patch does not support working latest version
- fix(YouTube/Overlay buttons): fix various issues
- fix(YouTube/Quick actions components): `Hide comment button` settings does not work
- fix(YouTube/Return YouTube Dislike): dislike counts not visible in incognito mode
- fix(YouTube/Return YouTube Dislike): do not clip compact text when not using English
- fix(YouTube/Return YouTube Dislike): do not show error toast if API success response contains new lines
- fix(YouTube/Return YouTube Dislike): hides the glow out animation in like dislike container
- fix(YouTube/Return YouTube Dislike): real-time likes/views are sometimes shown wrong
- fix(YouTube/Return YouTube Dislike): remove support for old layout (~YouTube v17.30.xx)
- fix(YouTube/Return YouTube Dislike): turning off RYD for shorts also disables it for regular videos
- fix(YouTube/Settings): contextual action bar has a background layer
- fix(YouTube/Settings): patches version in `Patch Information` is no longer updated manually
- fix(YouTube/Settings): when the user first installs the app and opens `Import/Export settings`, it is not an empty value
- fix(YouTube/Shorts components): hide shorts shelf in search result horizontal shelves
- fix(YouTube/SponsorBlock): modernize skip buttons
- fix(YouTube/SponsorBlock): segment time intervals are displayed incorrectly when the video length exceeds 24 hours
- fix(YouTube/Video playback): versions without default video quality restrictions do not validate video quality
- fix(YouTube/Video playback): `Restore old quality layout` settings does not apply to quality menu in shorts player
- refactor(YouTube/Settings): reorganize settings menu
- refactor(YouTube/Video information): include playback speed, video quality, channel id, channel name, video title, video length, livestream, playlist id
- feat(YouTube/Translations): update translation


YouTube Music
==
- feat(YouTube Music): add support versions `6.34.51` ~ `6.50.51`
- feat(YouTube Music): add `Disable dislike redirection` patch
- feat(YouTube Music): change patch name `Enable old style library shelf` to `Restore old style library shelf`
- feat(YouTube Music): change patch name `MicroG support` to `GmsCore support`
- feat(YouTube Music): remove support versions `6.21.52` ~ `6.28.53`
- feat(YouTube Music): remove `Enable old style miniplayer` patch
- feat(YouTube Music): remove `Enable playback speed` patch
- feat(YouTube Music): `Background play`, `Exclusive audio playback` patches have been integrated into `Enable minimized playback` patch
- feat(YouTube Music): `Enable black navigation bar`, `Hide navigation bar component` patches have been integrated into `Navigation bar components` patch
- feat(YouTube Music): `Enable color match player`, `Enable force minimized player`, `Enable old player background`, `Enable old player layout`, `Remember repeat state`, `Hide fullscreen share button`, `Remember shuffle state`, `Enable zen mode` patches have been integrated into `Player components` patch
- feat(YouTube Music): `Enable compact dialog`, `Hide flyout panel`, `Replace dismiss queue`, `Replace report` patches have been integrated into `Flyout menu components` patch
- feat(YouTube Music): `Enable custom filter`, `Hide button shelf`, `Hide carousel shelf`, `Hide cast button`, `Hide category bar`, `Hide channel guidelines`, `Hide emoji picker and time stamp`, `Hide new playlist button`, `Hide history button`, `Hide playlist card`, `Hide taste builder`, `Hide tooltip content`, `Hide voice search button` patches have been integrated into `Layout components` patch
- feat(YouTube Music): `Hide account menu`, `Hide handle`, `Hide terms container` patches have been integrated into `Hide account components` patch
- feat(YouTube Music): `Hide general ads`, `Hide get premium` patches have been integrated into `Hide ads` patch
- feat(YouTube Music/Enable debug logging): add `Enable debug buffer logging` settings
- feat(YouTube Music/Enable debug logging): included by default
- feat(YouTube Music/Flyout menu components): add `Enable trim silence` settings (YT Music v6.43.52+)
- feat(YouTube Music/Flyout menu components): add `Hide 3-column component` settings (YT Music v6.36.51+)
- feat(YouTube Music/Flyout menu components): add `Replace report` settings (alternative settings of `Enable playback speed` settings)
- feat(YouTube Music/Hide ads): add `Hide fullscreen ads` settings
- feat(YouTube Music/Hide ads): add `Hide paid promotion label` settings
- feat(YouTube Music/Hide layout components): add support for custom filtering of byte buffers to `Enable custom filter`
- feat(YouTube Music/Hide layout components): add `Hide notification button` settings (YT Music v6.42.52+)
- feat(YouTube Music/Hide layout components): add `Hide sound search button` settings (YT Music v6.48.51+)
- feat(YouTube Music/Hide layout components): add `Hide sample shelf`, `Hide tap to update button` settings
- feat(YouTube Music/Litho filter): add support for identifier and byte buffer
- feat(YouTube Music/Player components): add `Enable next previous button`, `Enable swipe to dismiss miniplayer` settings (alternative setting of `Enable old style miniplayer` patch)
- feat(YouTube Music/Player components): add `Enable zen mode in podcasts` settings
- feat(YouTube Music/Player components): add `Restore old comments popup panels` settings (YT Music v6.42.52+)
- feat(YouTube Music/Settings): move SponsorBlock settings and Return YouTube Dislike settings to RVX Settings
- fix(YouTube Music/Client spoof): spoof all user agents
- fix(YouTube Music/Custom playback speed): default playback speed preset does not match with stock value
- fix(YouTube Music/Custom playback speed): do not override when custom playback speed preset is the default
- fix(YouTube Music/Enable old player background): app crashes when the app is first installed after including the patch in a specific version
- fix(YouTube Music/GmsCore support): clicking the `Manage accounts` button causes app crash
- fix(YouTube Music/GmsCore support): prompt to disable battery optimizations, if not done already
- fix(YouTube Music/Return YouTube Dislike): Do not show error toast if API success response contains new lines
- fix(YouTube Music/Settings): issue in vanilla YouTube Music v6.44.52 causes exception
- fix(YouTube Music/Settings): `Import / Export settings` crashes when certain patches are excluded
- fix(YouTube Music/SponsorBlock): even if disables SponsorBlock, fetched segments still remain in the seek bar
- fix(YouTube Music/SponsorBlock): unable to export segment behavior
- fix(YouTube Music/Spoof app version): spoofing the app version with `6.11.52` also enables old style library shelves
- refactor(YouTube Music/Settings): reorganize settings menu
- refactor(YouTube Music/Video information): include playback speed and video quality
- feat(YouTube Music/Translations): update translation


Reddit
==
- feat(Reddit): restrict support version
- feat(Reddit): remove `Hide toolbar button` patch (deprecated until Reddit adds a button like r/place or Reddit recap button to the toolbar)


Etc
==
- build: bump dependencies
- build: bump gradle wrapper
- chore: add string format indexes, to allow more flexible translations
- chore: `ReadMeFileGenerator` no longer uses a hardcoded version of `README-template.md`
- feat(GmeCore support): switch to [ReVanced GmsCore](https://github.com/ReVanced/GmsCore/releases/latest) vendor
- fix(GmeCore support): add missing constants
- refactor: fix package and code structure
- refactor: fix patch structure

※ Playback issue some YouTube users are experiencing is not yet resolved.
※ Reddit 2024.18.0+ can only be patched via [CLI](https://github.com/inotia00/revanced-documentation/wiki/Supplement.-Patch-for-latest-Reddit).
※ Compatible ReVanced Manager: [RVX Manager v1.120.1 (fork)](https://github.com/inotia00/revanced-manager/releases/tag/v1.20.1)
[Crowdin translation]
- [YouTube/European Countries](https://crowdin.com/project/revancedextendedeu)
- [YouTube/Other Countries](https://crowdin.com/project/revancedextended)
- [YT Music](https://crowdin.com/project/revancedmusicextended)
**Published at** -<br> 2024-05-08T21:25:49Z<br><sub>Change logs generated by [Docker Py Revanced](https://github.com/nikhilbadyal/docker-py-revanced)</sub>
</details>
<details> <summary>👀 inotia00/revanced-patches </summary>

**Release Version** - [v4.7.1](https://github.com/inotia00/revanced-patches/releases/tag/v4.7.1)<br>**Changelog** -<br> YouTube
==
- feat(YouTube): add support versions `19.03.36` ~ `19.16.39`
- feat(YouTube): add `Change shorts repeat state` patch
- feat(YouTube): add `Disable auto audio tracks` patch
- feat(YouTube): change patch name `Ambient mode switch` to `Ambient mode control`
- feat(YouTube): change patch name `Change player flyout panel toggles` to `Change player flyout menu toggles`
- feat(YouTube): change patch name `Disable shorts on startup` to `Disable resuming shorts on startup`
- feat(YouTube): change patch name `Hide description components` to `Description components`
- feat(YouTube): change patch name `Hide navigation bar components` to `Navigation bar components`
- feat(YouTube): change patch name `Hide shorts components` to `Shorts components`
- feat(YouTube): change patch name `Hide suggested video overlay` to `Fix suggested video end screen`
- feat(YouTube): change patch name `MicroG support` to `GmsCore support`
- feat(YouTube): integration of `Hide suggestions shelf` patch into `Hide feed components` patch
- feat(YouTube): remove support versions `18.25.40`, `18.27.36`
- feat(YouTube): remove `Add splash animation`, `Enable song search`, `Enable language switch`, `Force opus codec`, `Force video codec`, `Hide animated button background`, `Spoof player parameters` patch
- feat(YouTube): `Append time stamps information`, `Custom seekbar color`, `Enable seekbar tapping`, `Enable new thumbnail preview`, `Hide seekbar`, `Hide time stamp` patches have been integrated into `Seekbar components` patch
- feat(YouTube): `Custom playback speed`, `Disable HDR video`, `Default video quality`, `Default playback speed`, `Enable old quality layout`, `Spoof device dimensions` patches has been integrated into `Video playback` patch
- feat(YouTube): `Custom player overlay opacity`, `Disable speed overlay`, `Hide auto player popup panels`, `Hide channel watermark`, `Hide crowdfunding box`, `Hide end screen cards`, `Hide filmstrip overlay`, `Hide info cards`, `Hide seek message`, `Hide suggested actions`, `Hide suggested video overlay` patches has been integrated into `Player components` patch
- feat(YouTube): `Disable pip notification`, `Disable update screen`, `Hide account menu`, `Hide cast button`, `Hide floating microphone`, `Hide handle`, `Hide snack bar`, `Hide tooltip content` patches has been integrated into `Hide layout components` patch
- feat(YouTube): `Enable bottom player gestures` patch has been integrated into `Swipe controls` patch
- feat(YouTube): `Enable compact controls overlay`, `Force fullscreen`, `Hide autoplay preview`, `Hide end screen overlay`, `Hide fullscreen panels`, `Landscape mode`, `Quick actions components` patches has been integrated into `Fullscreen components` patch
- feat(YouTube): `Enable tablet navigation bar`, `Hide navigation label`, `Hide navigation buttons` patches have been integrated into `Hide navigation bar component` patch
- feat(YouTube): `Hide autoplay button`, `Hide captions button`, `Hide collapse button`, `Hide music button`, `Hide previous next button` patches has been integrated into `Hide player buttons` patch
- feat(YouTube): `Hide general ads`, `Hide video ads` have been integrated into `Hide ads` patch
- feat(YouTube): `Hide search term thumbnail`,  `Hide toolbar button`, `Hide trending searches`, `Hide voice search button`, `Premium heading` patches has been integrated into `Toolbar components` patch
- feat(YouTube/Alternative thumbnails): selectively enable for home / subscriptions / search
- feat(YouTube/Description components): add `Always expand panel` and `Disable description interaction` settings (YouTube v19.02.39+)
- feat(YouTube/Description components): add `Disable rolling number animations` settings
- feat(YouTube/Description components): `Hide game sections`, `Hide music sections`, `Hide place sections` settings have been integrated into `Hide suggestions sections` settings
- feat(YouTube/Disable update screen): remove settings
- feat(YouTube/Enable debug logging): included by default
- feat(YouTube/Enable tablet mini player): add `Enable modern mini player` settings (YouTube v19.12.41+)
- feat(YouTube/Hide ads): add `Hide fullscreen ads` settings
- feat(YouTube/Hide ads): remove `Close interstitial ads` settings
- feat(YouTube/Hide feed components): add `Channel tab filter` settings
- feat(YouTube/Hide feed components): add `Hide feed captions button` settings
- feat(YouTube/Hide feed components): add `Hide playables` settings
- feat(YouTube/Hide feed components): remove `Hide gray description` settings
- feat(YouTube/Hide feed components): remove `Hide store tab` settings
- feat(YouTube/Hide feed components): remove `Select method to hide shelves` settings in `Hide carousel shelf` settings
- feat(YouTube/Hide feed components): `Hide carousel shelf` setting no longer checks navigation index
- feat(YouTube/Hide feed components): `Hide suggestions shelf` setting has been renamed to the `Hide carousel shelf` setting.
- feat(YouTube/Hide layout components): custom filtering of the protocol buffer
- feat(YouTube/Hide layout components): filter home / search results by keywords
- feat(YouTube/Hide layout components): `Hide YouTube settings menu` settings
- feat(YouTube/Hide player flyout menu): add `Hide picture-in-picture menu` settings
- feat(YouTube/Overlay buttons): add `Hide fullscreen button` settings
- feat(YouTube/Overlay buttons): hook download button for feed flyout menu
- feat(YouTube/Overlay buttons): restore `Tap and hold to toggle pause after repeat states` features
- feat(YouTube/Player components): add `Skip autoplay countdown` settings
- feat(YouTube/Player components): add `Speed overlay value` settings
- feat(YouTube/Seekbar components): add `Hide seekbar chapters` settings
- feat(YouTube/Seekbar components): add `Replace time stamp action` settings
- feat(YouTube/Settings): changing the language in YouTube settings will also be reflected in RVX settings
- feat(YouTube/Settings): move SponsorBlock settings and Return YouTube Dislike settings to RVX Settings
- feat(YouTube/Settings): remove `Double back timeout` settings
- feat(YouTube/Shorts components): add `Return shorts channel name` settings
- feat(YouTube/Shorts components): match original ReVanced code
- feat(YouTube/Shorts components): remove the settings to hide each toolbar component, add settings to hide the entire toolbar
- feat(YouTube/Shorts components): selectively hide shorts shelves for home / subscription / search / history
- feat(YouTube/Spoof app version): add target version `17.33.42`
- feat(YouTube/Spoof app version): remove deprecated target versions
- feat(YouTube/Toolbar components): add `Enable wide search bar with header` settings
- feat(YouTube/Toolbar components): add `Replace create button` settings
- feat(YouTube/Video playback): add `Replace software AV1 codec` and `Reject software AV1 codec response` settings
- fix(YouTube/Client spoof): spoof all user agents
- fix(YouTube/Default video quality): applying default video quality to shorts causes the beginning of the shorts to get stuck in a loop
- fix(YouTube/Disable resuming shorts on startup): not worked due to A/B tests
- fix(YouTube/Disable resuming shorts on startup): patch does not work on `YouTube v18.29.38`
- fix(YouTube/Description components): `Hide shopping links` settings does not worked due to A/B tests
- fix(YouTube/Enable tablet mini player): title shifts down in fullscreen (YouTube v19.12.41+)
- fix(YouTube/GmsCore support): prompt to disable battery optimizations, if not done already
- fix(YouTube/Hide channel avatar section): not worked due to A/B tests
- fix(YouTube/Hide channel profile components): `Hide channel profile links` settings not worked due to A/B tests
- fix(YouTube/Hide comments component): `Hide thanks button` setting hides the Thanks button in shorts livestreams
- fix(YouTube/Hide feed components): `Hide subscriptions channel section` setting does not support tablet layout
- fix(YouTube/Hide player buttons): remove unused filter
- fix(YouTube/Hide player buttons): `Hide captions button` setting does not require set layout params
- fix(YouTube/Hide player buttons): `Hide collapse button` setting leaves a blank space in fullscreen
- fix(YouTube/Hide suggested video end screen): no longer closes the `suggested video end screen`, but instead follows the autoplay settings
- fix(YouTube/Hide suggestions shelf): not worked due to A/B tests
- fix(YouTube/Hide tooltip content): tooltip is not hidden in fullscreen
- fix(YouTube/Hide trending searches): patch does not support working latest version
- fix(YouTube/Overlay buttons): fix various issues
- fix(YouTube/Quick actions components): `Hide comment button` settings does not work
- fix(YouTube/Return YouTube Dislike): dislike counts not visible in incognito mode
- fix(YouTube/Return YouTube Dislike): do not clip compact text when not using English
- fix(YouTube/Return YouTube Dislike): do not show error toast if API success response contains new lines
- fix(YouTube/Return YouTube Dislike): hides the glow out animation in like dislike container
- fix(YouTube/Return YouTube Dislike): real-time likes/views are sometimes shown wrong
- fix(YouTube/Return YouTube Dislike): remove support for old layout (~YouTube v17.30.xx)
- fix(YouTube/Return YouTube Dislike): turning off RYD for shorts also disables it for regular videos
- fix(YouTube/Settings): contextual action bar has a background layer
- fix(YouTube/Settings): patches version in `Patch Information` is no longer updated manually
- fix(YouTube/Settings): when the user first installs the app and opens `Import/Export settings`, it is not an empty value
- fix(YouTube/Shorts components): hide shorts shelf in search result horizontal shelves
- fix(YouTube/SponsorBlock): modernize skip buttons
- fix(YouTube/SponsorBlock): segment time intervals are displayed incorrectly when the video length exceeds 24 hours
- fix(YouTube/Video playback): versions without default video quality restrictions do not validate video quality
- fix(YouTube/Video playback): `Restore old quality layout` settings does not apply to quality menu in shorts player
- refactor(YouTube/Settings): reorganize settings menu
- refactor(YouTube/Video information): include playback speed, video quality, channel id, channel name, video title, video length, livestream, playlist id
- feat(YouTube/Translations): update translation


YouTube Music
==
- feat(YouTube Music): add support versions `6.34.51` ~ `6.50.51`
- feat(YouTube Music): add `Disable dislike redirection` patch
- feat(YouTube Music): change patch name `Enable old style library shelf` to `Restore old style library shelf`
- feat(YouTube Music): change patch name `MicroG support` to `GmsCore support`
- feat(YouTube Music): remove support versions `6.21.52` ~ `6.28.53`
- feat(YouTube Music): remove `Enable old style miniplayer` patch
- feat(YouTube Music): remove `Enable playback speed` patch
- feat(YouTube Music): `Background play`, `Exclusive audio playback` patches have been integrated into `Enable minimized playback` patch
- feat(YouTube Music): `Enable black navigation bar`, `Hide navigation bar component` patches have been integrated into `Navigation bar components` patch
- feat(YouTube Music): `Enable color match player`, `Enable force minimized player`, `Enable old player background`, `Enable old player layout`, `Remember repeat state`, `Hide fullscreen share button`, `Remember shuffle state`, `Enable zen mode` patches have been integrated into `Player components` patch
- feat(YouTube Music): `Enable compact dialog`, `Hide flyout panel`, `Replace dismiss queue`, `Replace report` patches have been integrated into `Flyout menu components` patch
- feat(YouTube Music): `Enable custom filter`, `Hide button shelf`, `Hide carousel shelf`, `Hide cast button`, `Hide category bar`, `Hide channel guidelines`, `Hide emoji picker and time stamp`, `Hide new playlist button`, `Hide history button`, `Hide playlist card`, `Hide taste builder`, `Hide tooltip content`, `Hide voice search button` patches have been integrated into `Layout components` patch
- feat(YouTube Music): `Hide account menu`, `Hide handle`, `Hide terms container` patches have been integrated into `Hide account components` patch
- feat(YouTube Music): `Hide general ads`, `Hide get premium` patches have been integrated into `Hide ads` patch
- feat(YouTube Music/Enable debug logging): add `Enable debug buffer logging` settings
- feat(YouTube Music/Enable debug logging): included by default
- feat(YouTube Music/Flyout menu components): add `Enable trim silence` settings (YT Music v6.43.52+)
- feat(YouTube Music/Flyout menu components): add `Hide 3-column component` settings (YT Music v6.36.51+)
- feat(YouTube Music/Flyout menu components): add `Replace report` settings (alternative settings of `Enable playback speed` settings)
- feat(YouTube Music/Hide ads): add `Hide fullscreen ads` settings
- feat(YouTube Music/Hide ads): add `Hide paid promotion label` settings
- feat(YouTube Music/Hide layout components): add support for custom filtering of byte buffers to `Enable custom filter`
- feat(YouTube Music/Hide layout components): add `Hide notification button` settings (YT Music v6.42.52+)
- feat(YouTube Music/Hide layout components): add `Hide sound search button` settings (YT Music v6.48.51+)
- feat(YouTube Music/Hide layout components): add `Hide sample shelf`, `Hide tap to update button` settings
- feat(YouTube Music/Litho filter): add support for identifier and byte buffer
- feat(YouTube Music/Player components): add `Enable next previous button`, `Enable swipe to dismiss miniplayer` settings (alternative setting of `Enable old style miniplayer` patch)
- feat(YouTube Music/Player components): add `Enable zen mode in podcasts` settings
- feat(YouTube Music/Player components): add `Restore old comments popup panels` settings (YT Music v6.42.52+)
- feat(YouTube Music/Settings): move SponsorBlock settings and Return YouTube Dislike settings to RVX Settings
- fix(YouTube Music/Client spoof): spoof all user agents
- fix(YouTube Music/Custom playback speed): default playback speed preset does not match with stock value
- fix(YouTube Music/Custom playback speed): do not override when custom playback speed preset is the default
- fix(YouTube Music/Enable old player background): app crashes when the app is first installed after including the patch in a specific version
- fix(YouTube Music/GmsCore support): clicking the `Manage accounts` button causes app crash
- fix(YouTube Music/GmsCore support): prompt to disable battery optimizations, if not done already
- fix(YouTube Music/Return YouTube Dislike): Do not show error toast if API success response contains new lines
- fix(YouTube Music/Settings): issue in vanilla YouTube Music v6.44.52 causes exception
- fix(YouTube Music/Settings): `Import / Export settings` crashes when certain patches are excluded
- fix(YouTube Music/SponsorBlock): even if disables SponsorBlock, fetched segments still remain in the seek bar
- fix(YouTube Music/SponsorBlock): unable to export segment behavior
- fix(YouTube Music/Spoof app version): spoofing the app version with `6.11.52` also enables old style library shelves
- refactor(YouTube Music/Settings): reorganize settings menu
- refactor(YouTube Music/Video information): include playback speed and video quality
- feat(YouTube Music/Translations): update translation


Reddit
==
- feat(Reddit): restrict support version
- feat(Reddit): remove `Hide toolbar button` patch (deprecated until Reddit adds a button like r/place or Reddit recap button to the toolbar)


Etc
==
- build: bump dependencies
- build: bump gradle wrapper
- chore: add string format indexes, to allow more flexible translations
- chore: `ReadMeFileGenerator` no longer uses a hardcoded version of `README-template.md`
- feat(GmeCore support): switch to [ReVanced GmsCore](https://github.com/ReVanced/GmsCore/releases/latest) vendor
- fix(GmeCore support): add missing constants
- refactor: fix package and code structure
- refactor: fix patch structure

※ Playback issue some YouTube users are experiencing is not yet resolved.
※ Reddit 2024.18.0+ can only be patched via [CLI](https://github.com/inotia00/revanced-documentation/wiki/Supplement.-Patch-for-latest-Reddit).
※ Compatible ReVanced Manager: [RVX Manager v1.120.1 (fork)](https://github.com/inotia00/revanced-manager/releases/tag/v1.20.1)
[Crowdin translation]
- [YouTube/European Countries](https://crowdin.com/project/revancedextendedeu)
- [YouTube/Other Countries](https://crowdin.com/project/revancedextended)
- [YT Music](https://crowdin.com/project/revancedmusicextended)
**Published at** -<br> 2024-05-08T21:25:49Z<br><sub>Change logs generated by [Docker Py Revanced](https://github.com/nikhilbadyal/docker-py-revanced)</sub>
</details>
<details> <summary>👀 inotia00/revanced-patches </summary>

**Release Version** - [v4.7.1](https://github.com/inotia00/revanced-patches/releases/tag/v4.7.1)<br>**Changelog** -<br> YouTube
==
- feat(YouTube): add support versions `19.03.36` ~ `19.16.39`
- feat(YouTube): add `Change shorts repeat state` patch
- feat(YouTube): add `Disable auto audio tracks` patch
- feat(YouTube): change patch name `Ambient mode switch` to `Ambient mode control`
- feat(YouTube): change patch name `Change player flyout panel toggles` to `Change player flyout menu toggles`
- feat(YouTube): change patch name `Disable shorts on startup` to `Disable resuming shorts on startup`
- feat(YouTube): change patch name `Hide description components` to `Description components`
- feat(YouTube): change patch name `Hide navigation bar components` to `Navigation bar components`
- feat(YouTube): change patch name `Hide shorts components` to `Shorts components`
- feat(YouTube): change patch name `Hide suggested video overlay` to `Fix suggested video end screen`
- feat(YouTube): change patch name `MicroG support` to `GmsCore support`
- feat(YouTube): integration of `Hide suggestions shelf` patch into `Hide feed components` patch
- feat(YouTube): remove support versions `18.25.40`, `18.27.36`
- feat(YouTube): remove `Add splash animation`, `Enable song search`, `Enable language switch`, `Force opus codec`, `Force video codec`, `Hide animated button background`, `Spoof player parameters` patch
- feat(YouTube): `Append time stamps information`, `Custom seekbar color`, `Enable seekbar tapping`, `Enable new thumbnail preview`, `Hide seekbar`, `Hide time stamp` patches have been integrated into `Seekbar components` patch
- feat(YouTube): `Custom playback speed`, `Disable HDR video`, `Default video quality`, `Default playback speed`, `Enable old quality layout`, `Spoof device dimensions` patches has been integrated into `Video playback` patch
- feat(YouTube): `Custom player overlay opacity`, `Disable speed overlay`, `Hide auto player popup panels`, `Hide channel watermark`, `Hide crowdfunding box`, `Hide end screen cards`, `Hide filmstrip overlay`, `Hide info cards`, `Hide seek message`, `Hide suggested actions`, `Hide suggested video overlay` patches has been integrated into `Player components` patch
- feat(YouTube): `Disable pip notification`, `Disable update screen`, `Hide account menu`, `Hide cast button`, `Hide floating microphone`, `Hide handle`, `Hide snack bar`, `Hide tooltip content` patches has been integrated into `Hide layout components` patch
- feat(YouTube): `Enable bottom player gestures` patch has been integrated into `Swipe controls` patch
- feat(YouTube): `Enable compact controls overlay`, `Force fullscreen`, `Hide autoplay preview`, `Hide end screen overlay`, `Hide fullscreen panels`, `Landscape mode`, `Quick actions components` patches has been integrated into `Fullscreen components` patch
- feat(YouTube): `Enable tablet navigation bar`, `Hide navigation label`, `Hide navigation buttons` patches have been integrated into `Hide navigation bar component` patch
- feat(YouTube): `Hide autoplay button`, `Hide captions button`, `Hide collapse button`, `Hide music button`, `Hide previous next button` patches has been integrated into `Hide player buttons` patch
- feat(YouTube): `Hide general ads`, `Hide video ads` have been integrated into `Hide ads` patch
- feat(YouTube): `Hide search term thumbnail`,  `Hide toolbar button`, `Hide trending searches`, `Hide voice search button`, `Premium heading` patches has been integrated into `Toolbar components` patch
- feat(YouTube/Alternative thumbnails): selectively enable for home / subscriptions / search
- feat(YouTube/Description components): add `Always expand panel` and `Disable description interaction` settings (YouTube v19.02.39+)
- feat(YouTube/Description components): add `Disable rolling number animations` settings
- feat(YouTube/Description components): `Hide game sections`, `Hide music sections`, `Hide place sections` settings have been integrated into `Hide suggestions sections` settings
- feat(YouTube/Disable update screen): remove settings
- feat(YouTube/Enable debug logging): included by default
- feat(YouTube/Enable tablet mini player): add `Enable modern mini player` settings (YouTube v19.12.41+)
- feat(YouTube/Hide ads): add `Hide fullscreen ads` settings
- feat(YouTube/Hide ads): remove `Close interstitial ads` settings
- feat(YouTube/Hide feed components): add `Channel tab filter` settings
- feat(YouTube/Hide feed components): add `Hide feed captions button` settings
- feat(YouTube/Hide feed components): add `Hide playables` settings
- feat(YouTube/Hide feed components): remove `Hide gray description` settings
- feat(YouTube/Hide feed components): remove `Hide store tab` settings
- feat(YouTube/Hide feed components): remove `Select method to hide shelves` settings in `Hide carousel shelf` settings
- feat(YouTube/Hide feed components): `Hide carousel shelf` setting no longer checks navigation index
- feat(YouTube/Hide feed components): `Hide suggestions shelf` setting has been renamed to the `Hide carousel shelf` setting.
- feat(YouTube/Hide layout components): custom filtering of the protocol buffer
- feat(YouTube/Hide layout components): filter home / search results by keywords
- feat(YouTube/Hide layout components): `Hide YouTube settings menu` settings
- feat(YouTube/Hide player flyout menu): add `Hide picture-in-picture menu` settings
- feat(YouTube/Overlay buttons): add `Hide fullscreen button` settings
- feat(YouTube/Overlay buttons): hook download button for feed flyout menu
- feat(YouTube/Overlay buttons): restore `Tap and hold to toggle pause after repeat states` features
- feat(YouTube/Player components): add `Skip autoplay countdown` settings
- feat(YouTube/Player components): add `Speed overlay value` settings
- feat(YouTube/Seekbar components): add `Hide seekbar chapters` settings
- feat(YouTube/Seekbar components): add `Replace time stamp action` settings
- feat(YouTube/Settings): changing the language in YouTube settings will also be reflected in RVX settings
- feat(YouTube/Settings): move SponsorBlock settings and Return YouTube Dislike settings to RVX Settings
- feat(YouTube/Settings): remove `Double back timeout` settings
- feat(YouTube/Shorts components): add `Return shorts channel name` settings
- feat(YouTube/Shorts components): match original ReVanced code
- feat(YouTube/Shorts components): remove the settings to hide each toolbar component, add settings to hide the entire toolbar
- feat(YouTube/Shorts components): selectively hide shorts shelves for home / subscription / search / history
- feat(YouTube/Spoof app version): add target version `17.33.42`
- feat(YouTube/Spoof app version): remove deprecated target versions
- feat(YouTube/Toolbar components): add `Enable wide search bar with header` settings
- feat(YouTube/Toolbar components): add `Replace create button` settings
- feat(YouTube/Video playback): add `Replace software AV1 codec` and `Reject software AV1 codec response` settings
- fix(YouTube/Client spoof): spoof all user agents
- fix(YouTube/Default video quality): applying default video quality to shorts causes the beginning of the shorts to get stuck in a loop
- fix(YouTube/Disable resuming shorts on startup): not worked due to A/B tests
- fix(YouTube/Disable resuming shorts on startup): patch does not work on `YouTube v18.29.38`
- fix(YouTube/Description components): `Hide shopping links` settings does not worked due to A/B tests
- fix(YouTube/Enable tablet mini player): title shifts down in fullscreen (YouTube v19.12.41+)
- fix(YouTube/GmsCore support): prompt to disable battery optimizations, if not done already
- fix(YouTube/Hide channel avatar section): not worked due to A/B tests
- fix(YouTube/Hide channel profile components): `Hide channel profile links` settings not worked due to A/B tests
- fix(YouTube/Hide comments component): `Hide thanks button` setting hides the Thanks button in shorts livestreams
- fix(YouTube/Hide feed components): `Hide subscriptions channel section` setting does not support tablet layout
- fix(YouTube/Hide player buttons): remove unused filter
- fix(YouTube/Hide player buttons): `Hide captions button` setting does not require set layout params
- fix(YouTube/Hide player buttons): `Hide collapse button` setting leaves a blank space in fullscreen
- fix(YouTube/Hide suggested video end screen): no longer closes the `suggested video end screen`, but instead follows the autoplay settings
- fix(YouTube/Hide suggestions shelf): not worked due to A/B tests
- fix(YouTube/Hide tooltip content): tooltip is not hidden in fullscreen
- fix(YouTube/Hide trending searches): patch does not support working latest version
- fix(YouTube/Overlay buttons): fix various issues
- fix(YouTube/Quick actions components): `Hide comment button` settings does not work
- fix(YouTube/Return YouTube Dislike): dislike counts not visible in incognito mode
- fix(YouTube/Return YouTube Dislike): do not clip compact text when not using English
- fix(YouTube/Return YouTube Dislike): do not show error toast if API success response contains new lines
- fix(YouTube/Return YouTube Dislike): hides the glow out animation in like dislike container
- fix(YouTube/Return YouTube Dislike): real-time likes/views are sometimes shown wrong
- fix(YouTube/Return YouTube Dislike): remove support for old layout (~YouTube v17.30.xx)
- fix(YouTube/Return YouTube Dislike): turning off RYD for shorts also disables it for regular videos
- fix(YouTube/Settings): contextual action bar has a background layer
- fix(YouTube/Settings): patches version in `Patch Information` is no longer updated manually
- fix(YouTube/Settings): when the user first installs the app and opens `Import/Export settings`, it is not an empty value
- fix(YouTube/Shorts components): hide shorts shelf in search result horizontal shelves
- fix(YouTube/SponsorBlock): modernize skip buttons
- fix(YouTube/SponsorBlock): segment time intervals are displayed incorrectly when the video length exceeds 24 hours
- fix(YouTube/Video playback): versions without default video quality restrictions do not validate video quality
- fix(YouTube/Video playback): `Restore old quality layout` settings does not apply to quality menu in shorts player
- refactor(YouTube/Settings): reorganize settings menu
- refactor(YouTube/Video information): include playback speed, video quality, channel id, channel name, video title, video length, livestream, playlist id
- feat(YouTube/Translations): update translation


YouTube Music
==
- feat(YouTube Music): add support versions `6.34.51` ~ `6.50.51`
- feat(YouTube Music): add `Disable dislike redirection` patch
- feat(YouTube Music): change patch name `Enable old style library shelf` to `Restore old style library shelf`
- feat(YouTube Music): change patch name `MicroG support` to `GmsCore support`
- feat(YouTube Music): remove support versions `6.21.52` ~ `6.28.53`
- feat(YouTube Music): remove `Enable old style miniplayer` patch
- feat(YouTube Music): remove `Enable playback speed` patch
- feat(YouTube Music): `Background play`, `Exclusive audio playback` patches have been integrated into `Enable minimized playback` patch
- feat(YouTube Music): `Enable black navigation bar`, `Hide navigation bar component` patches have been integrated into `Navigation bar components` patch
- feat(YouTube Music): `Enable color match player`, `Enable force minimized player`, `Enable old player background`, `Enable old player layout`, `Remember repeat state`, `Hide fullscreen share button`, `Remember shuffle state`, `Enable zen mode` patches have been integrated into `Player components` patch
- feat(YouTube Music): `Enable compact dialog`, `Hide flyout panel`, `Replace dismiss queue`, `Replace report` patches have been integrated into `Flyout menu components` patch
- feat(YouTube Music): `Enable custom filter`, `Hide button shelf`, `Hide carousel shelf`, `Hide cast button`, `Hide category bar`, `Hide channel guidelines`, `Hide emoji picker and time stamp`, `Hide new playlist button`, `Hide history button`, `Hide playlist card`, `Hide taste builder`, `Hide tooltip content`, `Hide voice search button` patches have been integrated into `Layout components` patch
- feat(YouTube Music): `Hide account menu`, `Hide handle`, `Hide terms container` patches have been integrated into `Hide account components` patch
- feat(YouTube Music): `Hide general ads`, `Hide get premium` patches have been integrated into `Hide ads` patch
- feat(YouTube Music/Enable debug logging): add `Enable debug buffer logging` settings
- feat(YouTube Music/Enable debug logging): included by default
- feat(YouTube Music/Flyout menu components): add `Enable trim silence` settings (YT Music v6.43.52+)
- feat(YouTube Music/Flyout menu components): add `Hide 3-column component` settings (YT Music v6.36.51+)
- feat(YouTube Music/Flyout menu components): add `Replace report` settings (alternative settings of `Enable playback speed` settings)
- feat(YouTube Music/Hide ads): add `Hide fullscreen ads` settings
- feat(YouTube Music/Hide ads): add `Hide paid promotion label` settings
- feat(YouTube Music/Hide layout components): add support for custom filtering of byte buffers to `Enable custom filter`
- feat(YouTube Music/Hide layout components): add `Hide notification button` settings (YT Music v6.42.52+)
- feat(YouTube Music/Hide layout components): add `Hide sound search button` settings (YT Music v6.48.51+)
- feat(YouTube Music/Hide layout components): add `Hide sample shelf`, `Hide tap to update button` settings
- feat(YouTube Music/Litho filter): add support for identifier and byte buffer
- feat(YouTube Music/Player components): add `Enable next previous button`, `Enable swipe to dismiss miniplayer` settings (alternative setting of `Enable old style miniplayer` patch)
- feat(YouTube Music/Player components): add `Enable zen mode in podcasts` settings
- feat(YouTube Music/Player components): add `Restore old comments popup panels` settings (YT Music v6.42.52+)
- feat(YouTube Music/Settings): move SponsorBlock settings and Return YouTube Dislike settings to RVX Settings
- fix(YouTube Music/Client spoof): spoof all user agents
- fix(YouTube Music/Custom playback speed): default playback speed preset does not match with stock value
- fix(YouTube Music/Custom playback speed): do not override when custom playback speed preset is the default
- fix(YouTube Music/Enable old player background): app crashes when the app is first installed after including the patch in a specific version
- fix(YouTube Music/GmsCore support): clicking the `Manage accounts` button causes app crash
- fix(YouTube Music/GmsCore support): prompt to disable battery optimizations, if not done already
- fix(YouTube Music/Return YouTube Dislike): Do not show error toast if API success response contains new lines
- fix(YouTube Music/Settings): issue in vanilla YouTube Music v6.44.52 causes exception
- fix(YouTube Music/Settings): `Import / Export settings` crashes when certain patches are excluded
- fix(YouTube Music/SponsorBlock): even if disables SponsorBlock, fetched segments still remain in the seek bar
- fix(YouTube Music/SponsorBlock): unable to export segment behavior
- fix(YouTube Music/Spoof app version): spoofing the app version with `6.11.52` also enables old style library shelves
- refactor(YouTube Music/Settings): reorganize settings menu
- refactor(YouTube Music/Video information): include playback speed and video quality
- feat(YouTube Music/Translations): update translation


Reddit
==
- feat(Reddit): restrict support version
- feat(Reddit): remove `Hide toolbar button` patch (deprecated until Reddit adds a button like r/place or Reddit recap button to the toolbar)


Etc
==
- build: bump dependencies
- build: bump gradle wrapper
- chore: add string format indexes, to allow more flexible translations
- chore: `ReadMeFileGenerator` no longer uses a hardcoded version of `README-template.md`
- feat(GmeCore support): switch to [ReVanced GmsCore](https://github.com/ReVanced/GmsCore/releases/latest) vendor
- fix(GmeCore support): add missing constants
- refactor: fix package and code structure
- refactor: fix patch structure

※ Playback issue some YouTube users are experiencing is not yet resolved.
※ Reddit 2024.18.0+ can only be patched via [CLI](https://github.com/inotia00/revanced-documentation/wiki/Supplement.-Patch-for-latest-Reddit).
※ Compatible ReVanced Manager: [RVX Manager v1.120.1 (fork)](https://github.com/inotia00/revanced-manager/releases/tag/v1.20.1)
[Crowdin translation]
- [YouTube/European Countries](https://crowdin.com/project/revancedextendedeu)
- [YouTube/Other Countries](https://crowdin.com/project/revancedextended)
- [YT Music](https://crowdin.com/project/revancedmusicextended)
**Published at** -<br> 2024-05-08T21:25:49Z<br><sub>Change logs generated by [Docker Py Revanced](https://github.com/nikhilbadyal/docker-py-revanced)</sub>
</details>
<details> <summary>👀 inotia00/revanced-integrations </summary>

**Release Version** - [v1.8.2](https://github.com/inotia00/revanced-integrations/releases/tag/v1.8.2)<br>**Changelog** -<br> - fix(YouTube/Hide cast button): add missing class https://github.com/inotia00/ReVanced_Extended/issues/1955**Published at** -<br> 2024-05-08T21:55:25Z<br><sub>Change logs generated by [Docker Py Revanced](https://github.com/nikhilbadyal/docker-py-revanced)</sub>
</details>
<details> <summary>👀 inotia00/revanced-cli </summary>

**Release Version** - [v4.6.1](https://github.com/inotia00/revanced-cli/releases/tag/v4.6.1)<br>**Changelog** -<br> - build: update dependencies
- feat: rollback the default values of keystore alias and password to CLI v3.0 (compatible with old keystore)
- rollback: move ReVanced Library subproject to another repository

※ support `--unsigned` and `--rip-lib` commands #[j-hc/revanced-cli](https://github.com/j-hc/revanced-cli)**Published at** -<br> 2024-05-08T17:59:05Z<br><sub>Change logs generated by [Docker Py Revanced](https://github.com/nikhilbadyal/docker-py-revanced)</sub>
</details>
<details> <summary>👀 revanced/revanced-patches </summary>

**Release Version** - [v4.7.0](https://github.com/ReVanced/revanced-patches/releases/tag/v4.7.0)<br>**Changelog** -<br> # [4.7.0](https://github.com/ReVanced/revanced-patches/compare/v4.6.0...v4.7.0) (2024-04-21)


### Bug Fixes

* **Tumblr - Fix old versions:** Improve reliability by removing remnances of Tumblr Live  ([#2988](https://github.com/ReVanced/revanced-patches/issues/2988)) ([897b4db](https://github.com/ReVanced/revanced-patches/commit/897b4dbce984270ae1fd7de5bd30bd05153e45f2))
* **YouTube - GmsCore support:** Prompt to disable battery optimizations, if not done already ([#2958](https://github.com/ReVanced/revanced-patches/issues/2958)) ([82acb84](https://github.com/ReVanced/revanced-patches/commit/82acb84b5f6ff0722a2eb080b53da9dd3622502f))
* **YouTube - Hide ads:** rename `Hide paid content` to `Hide paid promotion label` ([#3026](https://github.com/ReVanced/revanced-patches/issues/3026)) ([17e4ac9](https://github.com/ReVanced/revanced-patches/commit/17e4ac978a2f109fd62469a3163b636cd63c55ae))
* **YouTube - Hide load more button:** Include patch with `Hide layout components`, and hide button only in search feed  ([#2959](https://github.com/ReVanced/revanced-patches/issues/2959)) ([b007e8e](https://github.com/ReVanced/revanced-patches/commit/b007e8e06a3afad79b40bec1c6a14604f059049c))
* **YouTube - Hide Shorts components:** Correctly hide Shorts if navigation tab is changed using device back button ([#3007](https://github.com/ReVanced/revanced-patches/issues/3007)) ([e5848e9](https://github.com/ReVanced/revanced-patches/commit/e5848e99c4cc838595164ef673a77fe60d28086b))
* **YouTube - Player flyout menu:** Add hide Lock screen menu ([#2985](https://github.com/ReVanced/revanced-patches/issues/2985)) ([308de4a](https://github.com/ReVanced/revanced-patches/commit/308de4a63ca99b8d30d6b3242f98d6f0e2aefb37))
* **YouTube - Spoof device dimensions:** Warn about potential performance issues ([#3039](https://github.com/ReVanced/revanced-patches/issues/3039)) ([9d6f305](https://github.com/ReVanced/revanced-patches/commit/9d6f305b7c923e62b89581d221fedbe1e3f81835))
* **YouTube Music - Remove upgrade button:** Fix compatibility with latest versions ([#3045](https://github.com/ReVanced/revanced-patches/issues/3045)) ([80de996](https://github.com/ReVanced/revanced-patches/commit/80de99666555694670529bbfe2e0be7a14d66555))


### Features

* Add `Hex` patch ([#3034](https://github.com/ReVanced/revanced-patches/issues/3034)) ([3c95aac](https://github.com/ReVanced/revanced-patches/commit/3c95aac838693b354d3a7b0e3dc57c6da5adfa9e))
* **Amazon:** Add `Always allow deep-linking` patch ([#3000](https://github.com/ReVanced/revanced-patches/issues/3000)) ([a92b7fb](https://github.com/ReVanced/revanced-patches/commit/a92b7fb43c8b1b45577360cdc6d883fe2815c2f2))
* **Strava - Unlock subscription:** Remove compatible version constraint ([80a5599](https://github.com/ReVanced/revanced-patches/commit/80a55991683d7b22626224fa2935a5bf9bfcbfee))
* **Twitter:** Add `Sanitize sharing links` patch ([#3003](https://github.com/ReVanced/revanced-patches/issues/3003)) ([186b887](https://github.com/ReVanced/revanced-patches/commit/186b8874157eef1b882b05d491ba1d4ca2809535))
* **YouTube - Hide layout components:** Add option to hide horizontal shelves ([#2951](https://github.com/ReVanced/revanced-patches/issues/2951)) ([9ae0650](https://github.com/ReVanced/revanced-patches/commit/9ae0650c0005d882299996aa442410bab4261395))
* **YouTube - Hide layout components:** Hide playables ([8423515](https://github.com/ReVanced/revanced-patches/commit/842351548baa33737db09be1cbca9f87c1951341))
* **YouTube - Hide Shorts components:** Hide `Shop`, `Location` and `Save sound to playlist` buttons ([#3018](https://github.com/ReVanced/revanced-patches/issues/3018)) ([5210ac4](https://github.com/ReVanced/revanced-patches/commit/5210ac431c191987264865bf8e789ea9f3fdd360))
* **YouTube - Hide Shorts components:** Hide tagged products, hide search suggestions ([#3019](https://github.com/ReVanced/revanced-patches/issues/3019)) ([e0d2fe5](https://github.com/ReVanced/revanced-patches/commit/e0d2fe5bd2e681b9a5252a8e4ad582cc019b1606))
* **YouTube - Swipe controls:** Save and restore brightness and add auto-brightness toggle ([#2996](https://github.com/ReVanced/revanced-patches/issues/2996)) ([f6c3bc4](https://github.com/ReVanced/revanced-patches/commit/f6c3bc43190d33e06f49b74fc056d26da1bb014a))
* **YouTube:** Add 'About' preference to settings menu ([#2981](https://github.com/ReVanced/revanced-patches/issues/2981)) ([5abf894](https://github.com/ReVanced/revanced-patches/commit/5abf89444a3e6a211ec03c242eb9a7847542b08c))
* **YouTube:** Match overlay icons style to YouTube ([#3023](https://github.com/ReVanced/revanced-patches/issues/3023)) ([6849393](https://github.com/ReVanced/revanced-patches/commit/684939314be3d0d43482f229b2adb033e7aa492a))
* **YouTube:** Support version `19.09.38`, `19.10.39` and `19.11.43` ([#2971](https://github.com/ReVanced/revanced-patches/issues/2971)) ([730f3e3](https://github.com/ReVanced/revanced-patches/commit/730f3e3a7e058b60f9a8130980ecb0a747fa0a8a))
* **YT Music - Hide 'Get Music Premium' label:** Remove occurences of label in settings ([#3046](https://github.com/ReVanced/revanced-patches/issues/3046)) ([10e170a](https://github.com/ReVanced/revanced-patches/commit/10e170a7302fdb585efee663ca13c814aea46c54))



**Published at** -<br> 2024-04-21T01:50:10Z<br><sub>Change logs generated by [Docker Py Revanced](https://github.com/nikhilbadyal/docker-py-revanced)</sub>
</details>
<details> <summary>👀 revanced/revanced-cli </summary>

**Release Version** - [v4.6.0](https://github.com/ReVanced/revanced-cli/releases/tag/v4.6.0)<br>**Changelog** -<br> # [4.6.0](https://github.com/ReVanced/revanced-cli/compare/v4.5.0...v4.6.0) (2024-04-01)


### Bug Fixes

* Copy APK to output path when it is not being signed ([366f400](https://github.com/ReVanced/revanced-cli/commit/366f400c5a46491f3f262c7ff4b0df1ae3721f74))
* Use correct option description ([45a2ffa](https://github.com/ReVanced/revanced-cli/commit/45a2ffa2dd95ee8ac3c4d466463c9a5b869b8da1))


### Features

* Use more consistent option name ([223629c](https://github.com/ReVanced/revanced-cli/commit/223629c663dcd94d237110e09e4e152aa03867f9))



**Published at** -<br> 2024-04-01T14:57:09Z<br><sub>Change logs generated by [Docker Py Revanced](https://github.com/nikhilbadyal/docker-py-revanced)</sub>
</details>
<details> <summary>👀 revanced/revanced-patches </summary>

**Release Version** - [v4.7.0](https://github.com/ReVanced/revanced-patches/releases/tag/v4.7.0)<br>**Changelog** -<br> # [4.7.0](https://github.com/ReVanced/revanced-patches/compare/v4.6.0...v4.7.0) (2024-04-21)


### Bug Fixes

* **Tumblr - Fix old versions:** Improve reliability by removing remnances of Tumblr Live  ([#2988](https://github.com/ReVanced/revanced-patches/issues/2988)) ([897b4db](https://github.com/ReVanced/revanced-patches/commit/897b4dbce984270ae1fd7de5bd30bd05153e45f2))
* **YouTube - GmsCore support:** Prompt to disable battery optimizations, if not done already ([#2958](https://github.com/ReVanced/revanced-patches/issues/2958)) ([82acb84](https://github.com/ReVanced/revanced-patches/commit/82acb84b5f6ff0722a2eb080b53da9dd3622502f))
* **YouTube - Hide ads:** rename `Hide paid content` to `Hide paid promotion label` ([#3026](https://github.com/ReVanced/revanced-patches/issues/3026)) ([17e4ac9](https://github.com/ReVanced/revanced-patches/commit/17e4ac978a2f109fd62469a3163b636cd63c55ae))
* **YouTube - Hide load more button:** Include patch with `Hide layout components`, and hide button only in search feed  ([#2959](https://github.com/ReVanced/revanced-patches/issues/2959)) ([b007e8e](https://github.com/ReVanced/revanced-patches/commit/b007e8e06a3afad79b40bec1c6a14604f059049c))
* **YouTube - Hide Shorts components:** Correctly hide Shorts if navigation tab is changed using device back button ([#3007](https://github.com/ReVanced/revanced-patches/issues/3007)) ([e5848e9](https://github.com/ReVanced/revanced-patches/commit/e5848e99c4cc838595164ef673a77fe60d28086b))
* **YouTube - Player flyout menu:** Add hide Lock screen menu ([#2985](https://github.com/ReVanced/revanced-patches/issues/2985)) ([308de4a](https://github.com/ReVanced/revanced-patches/commit/308de4a63ca99b8d30d6b3242f98d6f0e2aefb37))
* **YouTube - Spoof device dimensions:** Warn about potential performance issues ([#3039](https://github.com/ReVanced/revanced-patches/issues/3039)) ([9d6f305](https://github.com/ReVanced/revanced-patches/commit/9d6f305b7c923e62b89581d221fedbe1e3f81835))
* **YouTube Music - Remove upgrade button:** Fix compatibility with latest versions ([#3045](https://github.com/ReVanced/revanced-patches/issues/3045)) ([80de996](https://github.com/ReVanced/revanced-patches/commit/80de99666555694670529bbfe2e0be7a14d66555))


### Features

* Add `Hex` patch ([#3034](https://github.com/ReVanced/revanced-patches/issues/3034)) ([3c95aac](https://github.com/ReVanced/revanced-patches/commit/3c95aac838693b354d3a7b0e3dc57c6da5adfa9e))
* **Amazon:** Add `Always allow deep-linking` patch ([#3000](https://github.com/ReVanced/revanced-patches/issues/3000)) ([a92b7fb](https://github.com/ReVanced/revanced-patches/commit/a92b7fb43c8b1b45577360cdc6d883fe2815c2f2))
* **Strava - Unlock subscription:** Remove compatible version constraint ([80a5599](https://github.com/ReVanced/revanced-patches/commit/80a55991683d7b22626224fa2935a5bf9bfcbfee))
* **Twitter:** Add `Sanitize sharing links` patch ([#3003](https://github.com/ReVanced/revanced-patches/issues/3003)) ([186b887](https://github.com/ReVanced/revanced-patches/commit/186b8874157eef1b882b05d491ba1d4ca2809535))
* **YouTube - Hide layout components:** Add option to hide horizontal shelves ([#2951](https://github.com/ReVanced/revanced-patches/issues/2951)) ([9ae0650](https://github.com/ReVanced/revanced-patches/commit/9ae0650c0005d882299996aa442410bab4261395))
* **YouTube - Hide layout components:** Hide playables ([8423515](https://github.com/ReVanced/revanced-patches/commit/842351548baa33737db09be1cbca9f87c1951341))
* **YouTube - Hide Shorts components:** Hide `Shop`, `Location` and `Save sound to playlist` buttons ([#3018](https://github.com/ReVanced/revanced-patches/issues/3018)) ([5210ac4](https://github.com/ReVanced/revanced-patches/commit/5210ac431c191987264865bf8e789ea9f3fdd360))
* **YouTube - Hide Shorts components:** Hide tagged products, hide search suggestions ([#3019](https://github.com/ReVanced/revanced-patches/issues/3019)) ([e0d2fe5](https://github.com/ReVanced/revanced-patches/commit/e0d2fe5bd2e681b9a5252a8e4ad582cc019b1606))
* **YouTube - Swipe controls:** Save and restore brightness and add auto-brightness toggle ([#2996](https://github.com/ReVanced/revanced-patches/issues/2996)) ([f6c3bc4](https://github.com/ReVanced/revanced-patches/commit/f6c3bc43190d33e06f49b74fc056d26da1bb014a))
* **YouTube:** Add 'About' preference to settings menu ([#2981](https://github.com/ReVanced/revanced-patches/issues/2981)) ([5abf894](https://github.com/ReVanced/revanced-patches/commit/5abf89444a3e6a211ec03c242eb9a7847542b08c))
* **YouTube:** Match overlay icons style to YouTube ([#3023](https://github.com/ReVanced/revanced-patches/issues/3023)) ([6849393](https://github.com/ReVanced/revanced-patches/commit/684939314be3d0d43482f229b2adb033e7aa492a))
* **YouTube:** Support version `19.09.38`, `19.10.39` and `19.11.43` ([#2971](https://github.com/ReVanced/revanced-patches/issues/2971)) ([730f3e3](https://github.com/ReVanced/revanced-patches/commit/730f3e3a7e058b60f9a8130980ecb0a747fa0a8a))
* **YT Music - Hide 'Get Music Premium' label:** Remove occurences of label in settings ([#3046](https://github.com/ReVanced/revanced-patches/issues/3046)) ([10e170a](https://github.com/ReVanced/revanced-patches/commit/10e170a7302fdb585efee663ca13c814aea46c54))



**Published at** -<br> 2024-04-21T01:50:10Z<br><sub>Change logs generated by [Docker Py Revanced](https://github.com/nikhilbadyal/docker-py-revanced)</sub>
</details>
<details> <summary>👀 revanced/revanced-integrations </summary>

**Release Version** - [v1.8.0](https://github.com/ReVanced/revanced-integrations/releases/tag/v1.8.0)<br>**Changelog** -<br> # [1.8.0](https://github.com/ReVanced/revanced-integrations/compare/v1.7.0...v1.8.0) (2024-04-21)


### Bug Fixes

* **YouTube - Disable suggested video end screen:** Require app restart ([38ae5aa](https://github.com/ReVanced/revanced-integrations/commit/38ae5aac845745824218a08053db519a3325d7a9))
* **YouTube - GmsCore support:** Prompt to disable battery optimizations, if not done already ([#601](https://github.com/ReVanced/revanced-integrations/issues/601)) ([c5c9de5](https://github.com/ReVanced/revanced-integrations/commit/c5c9de500d8f1268799e55c31c446bfe8336f79a))
* **YouTube - Hide ads:** rename `Hide paid content` to `Hide paid promotion label` ([#616](https://github.com/ReVanced/revanced-integrations/issues/616)) ([13dc172](https://github.com/ReVanced/revanced-integrations/commit/13dc17288d13d024a3fbe318ee0fb23a0d46af85))
* **YouTube - Hide keyword content:** Correctly hide content in the subscription tab ([c3bfa77](https://github.com/ReVanced/revanced-integrations/commit/c3bfa77d62b15dedfed8f697583f2f0805f0c2c1))
* **YouTube - Hide layout components:** Do not hide playlist shelf in library ([c5d38a7](https://github.com/ReVanced/revanced-integrations/commit/c5d38a7e0791ebb8fe59397fff959cc94e0a7aed))
* **YouTube - Hide layout components:** Hide horizontal tile shelves ([ba30869](https://github.com/ReVanced/revanced-integrations/commit/ba308690cf83067d3ddd54622eebcbd14bc15ac8))
* **YouTube - Hide load more button:** Include patch with `Hide layout components`, and hide button only in search feed  ([#600](https://github.com/ReVanced/revanced-integrations/issues/600)) ([c420891](https://github.com/ReVanced/revanced-integrations/commit/c420891e3ef134f30af79cf2f30da3fa2fe5a455))
* **YouTube - Hide Shorts components:** Correctly hide Shorts if navigation tab is changed using device back button ([#611](https://github.com/ReVanced/revanced-integrations/issues/611)) ([ffc3437](https://github.com/ReVanced/revanced-integrations/commit/ffc3437843c24af255d2a0dda9930d2843cac4b6))
* **YouTube - Hide Shorts components:** Do not show Shorts suggestions in video player, if all hide Shorts options are enabled ([#613](https://github.com/ReVanced/revanced-integrations/issues/613)) ([c132670](https://github.com/ReVanced/revanced-integrations/commit/c132670400e6bdf17c46b8d04d579fb49c3d2749))
* **YouTube - Hide Shorts components:** Hide paid promotion label ([3ce100c](https://github.com/ReVanced/revanced-integrations/commit/3ce100ced57d7099c2209d9a955484f1e7d418e0))
* **YouTube - Hide Shorts components:** Hide subscribe button in channel bar ([9938bbf](https://github.com/ReVanced/revanced-integrations/commit/9938bbf0de9592db015ae0cfea83e855e12f0c7e))
* **YouTube - Hide Shorts components:** Hide suggested actions in incognito mode ([bba421d](https://github.com/ReVanced/revanced-integrations/commit/bba421ddb63597bf918ecccacfd4a33493016b9f))
* **YouTube - Navigation bar hook:** Handle if search is active but hidden behind a maximized player ([cbccb46](https://github.com/ReVanced/revanced-integrations/commit/cbccb46e639003adbed941f9b88c41b4c9998729))
* **YouTube - Player flyout menu:** Add hide Lock screen menu ([#609](https://github.com/ReVanced/revanced-integrations/issues/609)) ([b2fe105](https://github.com/ReVanced/revanced-integrations/commit/b2fe105199d4a5958676cbc8f9c701541e8ff24a))
* **YouTube - Return YouTube Dislike:** Do not clip compact text when not using English ([eeaeb49](https://github.com/ReVanced/revanced-integrations/commit/eeaeb49f2a562d2690dae184153c303a5b1c4368))
* **YouTube - Return YouTube Dislike:** Do not show error toast if API success response contains new lines ([#612](https://github.com/ReVanced/revanced-integrations/issues/612)) ([9108205](https://github.com/ReVanced/revanced-integrations/commit/9108205445c533550db454731d4f9460a3241a03))
* **YouTube - Settings:** Do not show a toast if migrating old unknown settings ([f2e15a2](https://github.com/ReVanced/revanced-integrations/commit/f2e15a2e1ff59ae7780cfbd366e5165f4e2b191d))
* **YouTube - Spoof device dimensions:** Warn about potential performance issues ([#617](https://github.com/ReVanced/revanced-integrations/issues/617)) ([786ac9d](https://github.com/ReVanced/revanced-integrations/commit/786ac9d2b71886964454fcb748e656d1beed1964))


### Features

* **YouTube - Hide layout components:** Add option to hide horizontal shelves ([#598](https://github.com/ReVanced/revanced-integrations/issues/598)) ([fedace0](https://github.com/ReVanced/revanced-integrations/commit/fedace02fd5c443ef37dcf77253438b041f4c3f9))
* **YouTube - Hide layout components:** Hide playables ([d6cd550](https://github.com/ReVanced/revanced-integrations/commit/d6cd550880596de5cd2eb4a0d1325a73326d4af9))
* **YouTube - Hide Shorts components:** Hide `Shop`, `Location` and `Save sound to playlist` buttons ([#614](https://github.com/ReVanced/revanced-integrations/issues/614)) ([acfa3c9](https://github.com/ReVanced/revanced-integrations/commit/acfa3c98868b6d84572ee682ad806a0282ac6dad))
* **YouTube - Hide Shorts components:** Hide tagged products, hide search suggestions ([#615](https://github.com/ReVanced/revanced-integrations/issues/615)) ([0586fb7](https://github.com/ReVanced/revanced-integrations/commit/0586fb70e347c25742e03102441cfb37315b5937))
* **YouTube - Swipe controls:** Save and restore brightness and add auto-brightness toggle ([#610](https://github.com/ReVanced/revanced-integrations/issues/610)) ([1c8e2b2](https://github.com/ReVanced/revanced-integrations/commit/1c8e2b29410048a352cb6aad3dd02773459f91a0))
* **YouTube:** Add 'About' preference to settings menu ([#608](https://github.com/ReVanced/revanced-integrations/issues/608)) ([b8f260e](https://github.com/ReVanced/revanced-integrations/commit/b8f260ebd3e7c2dc50a57cd060b76f2e0fc4a89c))



**Published at** -<br> 2024-04-21T01:51:36Z<br><sub>Change logs generated by [Docker Py Revanced](https://github.com/nikhilbadyal/docker-py-revanced)</sub>
</details>