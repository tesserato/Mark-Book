# Mark Book

Carry your guitar songbook in your pocket! Mark Book is an app that implements a very simple mark up language, akin to markdown, to generate songbooks. 

We intend to make musical performances simpler by enabling you to have your repertoire with you all the time, ready to be accessed and updated if needed.

Your songbook is stored in a text file with the extension .mb, which can be edited with any text editor. The format is intended to be readable even before rendered, exposing all the important information, such as chord fingerings. The implementation renders those files in an elegant and compact way, to enable consulting and editing your songbook even on small screens.

# Features
- Free
- Saves songbook in a future proof, open format
- Defined chord fingerings have priority over inferred fingerings
- Optionally mark the beginning of each verse
- Open .mb files by double-clicking on them in windows 
- Light and dark themes
- Change both input and output font sizes
- Change song panel size
- Internal state is automatically saved: current songbook, theme, font sizes, panel size, etc...

## Symbols overview:

- ! Starts a new song
- \# visible comment
- \| invisible comment
- \> chord line



# Roadmap

I've been pondering about this for a long time now, the idea always being to create an opinionated app with a minimalistic design and a concise set of features that just works out of the box.

The long term goal is to make the experience as simple as possible, with the shallowest learning curve. In the near future, we expect chords to be generated on the fly, and the best possible fingering for each song chosen automatically. The app already implements a rudimentary chord detection engine, but for best results, we advise that chords be defined beforehand.

# Get the app
The app is completely free, without ads, and is available on a number of different platforms, with more coming soon.

## Web App

- [markbookapp.z13.web.core.windows.net](https://markbookapp.z13.web.core.windows.net/)
- [markbookapp-secondary.z13.web.core.windows.net](https://markbookapp-secondary.z13.web.core.windows.net/)


## Progressive Web App (PWA)
- [markbook-app.web.app](https://markbook-app.web.app/#/)


## Windows 64 bit

Windows releases are available in the "Releases" section of this repository:

[Installer](https://github.com/tesserato/Mark-Book/releases/download/v1.2/MarkBook_1_3_Installer.exe)

[Zip](https://github.com/tesserato/Mark-Book/releases/download/v1.2/MarkBook_1_3.zip)

## Android 

[Play Store](https://play.google.com/store/apps/details?id=mark.book)

The apk can be directly downloaded in the "Releases" section of this repository:

[APK](https://github.com/tesserato/Mark-Book/releases/download/v1.2/MarkBook_1_3.apk)




# Extensive list of [chords](https://en.wikibooks.org/wiki/Guitar/Chords/Full_List_Standard_Tuning)


# Known limitations

The field of app development went a long way since my [last attempt in making a songbook app](https://songbapp.github.io/), and I chose to implement it this time using the Flutter library.
Flutter is a great library, and made it possible to make those 3 apps with a single codebase. It was, however, initially designed with mobile in mind, and it shows. Some know limitations are listed below.

- Hovering/clicking area could be bigger
- Lack of undo/redo functionality
- Lack keyboard shortcuts
- Input text scrollbar could behave better


# Support the development:

You can know more about the developer [here](https://carlos-tarjano.web.app/). If you have comments, suggestions, questions or would like to be part of the team, drop a message at **tesserato@hotmail.com**

There is also a "Songs" folder, where .mb files can be downloaded. If you would like to contribute songs, send them to **tesserato@hotmail.com**.

## You can donate using one of the methods below:

### Bitcoin

[![Bitcoin](./icons/bitcoin.png)](https://www.blockchain.com/btc/address/1JZcai4xDpBrt2wCx1uZBmVx7MjvzVqwBz)

### PayPal

[![PayPal](./icons/paypal.png)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=HS7BYUUUM6N6W)


