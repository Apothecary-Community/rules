---
title: "Matrix Tips & Tricks"
date: 2022-12-01T23:44:55-05:00
---

## Spoilers

Spoilers are very useful for posting potentially triggering content safely. Depending on your client, you may or may not be able to add an inline content warning. Instructions for using spoilers depend on your client.

### Fluffychat

In Fluffychat, text can be spoilered by adding two pipes to the start and end of your message.
It also supports adding a warning for the spoiler, by putting a pipe in the middle of the spoiler.

```
||cw suicide|hidden content here!||
```

### Element

Element does not have support for inline CW text, but there is a spoiler command on both android and desktop.

```
/spoiler Spoilered Text
```

If desired, there is also a workaround with the `/html` command on desktop only.

```
/html <span data-mx-spoiler="cw suicide">hidden content here!</span>
```

### Element iOS

Sadly, there is currently no support for spoilering text in Element iOS. Please use fluffychat on ios if spoilers are an important requirement for your experience !

### Nheko

To send a message with a content warning, use the raw html.

```
<span data-mx-spoiler="cw suicide">hidden content here!</span>
```

This is a temporary measure until the spoiler feature is finalized in this client.

### ⚠️ Warning ⚠️

Spoiler reasons are not supported in all clients, namely element android, until this is fixed it's reccomended to also put a content warning in an additional message.

## Emotes

Apothecary rooms have emotes scattered amongst them which fit the theme of each room! In all the rooms you're joined in, check to see if there are emotes available in it!

### Client Support

#### Android

Fluffychat is a nice client for android which has good support for emotes!
Schildichat is an element fork with emote support as well, if you prefer that style.

#### UBPorts

Cinny has good emote support and is a nice matrix client on UBPorts!

#### iOS

Fluffychat has good emote support and is also on iOS!

### Linux

Fluffychat has decent linux support, and has good emote support.
Cinny works well in web browsers, but the flatpak version has a few quirks, and has good emote support.
Nheko also works on linux, and is a QT client with good emote support.

### Windows

Cinny web works well on windows.
Fluffychat may work ok, but has  not been tested by our QA team.
Nheko may work ok, but has  not been tested by our QA team.

### MacOS 
Cinny web works well on macos.
Nheko may work ok, but has  not been tested by our QA team.
