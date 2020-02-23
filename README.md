# Likers Blocker

A Chrome extension to block all likers of a tweet.

Inspired by [Mario Sixtus (@sixtus)](https://twitter.com/sixtus):

> In Übrigen wünsche ich mir für solche Fälle ein Twitter-Add-On, das alle Liker eines bestimmten Tweets blockt, weil es nur Arschlöcher sein können. Wer programmiert es?
> – [10:41 am · 22 Feb. 2020](https://twitter.com/sixtus/status/1231152136857231360)

In collaboration with [@pkreissel](https://twitter.com/pkreissel), who wrote the [back-end](https://github.com/pkreissel/ichbinhier_twittertools) for this tool.

## Installation

* Go to the releases tab and download the .crx file from the latest release.
* Open it in Chrome.
* Conform the installation.

## Usage

* Once you click on a tweet, there is a link which indicates how many people liked this tweet.
* click on that link and you should get a list of all likers and a button on the top which says "block all".
* click on that button and confirm if you are sure and wait for the success message.
* ✔ DONE. All the dumbasses are blocked. 😇

## Known Issues and to dos

see [Issues](https://github.com/dmstern/likers-blocker/issues)

## Collaboration

Feel free to suggest improvements or to create pull requests!

### Development

To test the extension locally:

* clone this repository
* in Chrome, go to `chrome://extensions`
* enable the developer mode with the regarding toggle button on the right side
* click on "Load unpacked"
* Select the folder of the cloned repository
