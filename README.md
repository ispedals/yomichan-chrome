# Yomichan for Chrome #

The Yomichan for Chrome extension turns your browser into a tool for building Japanese language literacy by helping you
to decipher texts which would be otherwise too difficult tackle. This extension was inspired in part by
[Rikaichan](https://addons.mozilla.org/en-US/firefox/addon/rikaichan/) and
[Rikaikun](https://chrome.google.com/webstore/detail/rikaikun/jipdnfibhldikgcjhfnomkfpcebammhp?hl=en), but it stands
apart in its goal of being a all-encompassing learning tool as opposed to a mere browser-based dictionary. It is the
natural evolution of the [Yomichan](https://foosoft.net/projects/yomichan) plugin that I developed for
[Anki](http://ankisrs.net/) when I was starting to learn Japanese back in 2011.

<iframe width="800" height="500" src="https://www.youtube.com/embed/90_A1VpTnMk" frameborder="0" allowfullscreen></iframe>

## Installation ##

The most straightforward way to install this extension is to download it from its listing in the [Chrome Web
Store](https://chrome.google.com/webstore/detail/yomichan/ogmnaimimemjmbakcfefmnahgdfhfami). If you are a developer, you
can also clone the [repository on GitHub](https://github.com/FooSoft/yomichan-chrome-ext), provided that you have have
[Git LFS](https://git-lfs.github.com/) installed (it is required to download the included dictionary files).

If you wish to make use of the *AnkiConnect* functionality to create Japanese flash cards directly from your browser,
you must install the [AnkiConnect](https://foosoft.net/projects/anki-connect) extension first. If you already have
[Yomichan](https://foosoft.net/projects/yomichan) installed, AnkiConnect can be used after it is enabled in the plugin
preferences.

## Usage ##

1.  Click on the Yomichan browser action button in the upper right corner of the window (labeled ヨミ).
2.  Hold down the <kbd>Shift</kbd> or the middle mouse button while you move your mouse over Japanese text.
3.  Resize the definition window by dragging the bottom right corner of the window.
4.  Clicking on a Kanji will display the Kanji information page, including a Kanji stroke diagram.
5.  Users of [AnkiConnect](https://foosoft.net/projects/anki-connect) will see buttons that can be used to create cards.
6.  Right click on the Yomichan browser action button and select *Options* to configure the extension.

## Screenshots ##

[![Vocabulary definitions](img/vocab-thumb.png)](img/vocab.png)
[![Kanji information](img/kanji-thumb.png)](img/kanji.png)
[![Options page](img/options-thumb.png)](img/options.png)

## Build Requirements ##

* Python 3
* [Handlebars](https://www.npmjs.com/package/handlebars)
* 7-zip

## License ##

GPL
