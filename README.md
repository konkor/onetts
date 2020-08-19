<p align="center">
  <a href="https://github.com/konkor/onetts"><img src="https://img.shields.io/github/license/konkor/onetts.svg" alt="GPLv3 License"></a>
  <a href="https://github.com/konkor/onetts"><img src="https://img.shields.io/github/stars/konkor/onetts.svg?style=social&label=Star&style=flat-square" alt="Stars"></a>
</p>

# [OneTTS - Online TTS Engine](https://github.com/konkor/onetts)


OneTTS is an GPLv3-licensed open source project for Linux users. It's an independent project with its ongoing development made possible entirely thanks to the support.

Please, consider to support the project and make it better!

**OneTTS** helps converting Text-To-Speak using Google TTS and GStreamer for audio output. Free Google TTS engine has the limitation in 100 characters per request, so this application helps to avoid this limitation by splitting the input text in 100 character chunks or less.

## How-to use
1. Raw text in command line
```
onetts "Hello One TTS!"
```
2. From a text file `TEXT_FILE`
```
onetts sample.txt
```
3. Using the stdin pipeline for input
```
cat  sample.txt | onetts
## OR
echo "Hello One TTS!" | onetts
```

## Contributions
* Report [a bug](https://github.com/konkor/onetts/issues).
* Test it on your favorite Linux distribution.
* Contribute with an idea, graphical content, translation or code [an issue](https://github.com/konkor/onetts/issues).
* Make donation to the project.

## Donations
Please, consider to support the author seriously at least temporary or one time. It's an independent open software project. It means there is no any organization or company behind it to support it except generous users. The time for the development, supporting, debugging, testing is not less then for any other project. Otherwise the project could have only spontaneous updates and supporting until it just die. **All donations is for all open-source projects of the autor.**

 * [Become a backer or sponsor on Patreon](https://www.patreon.com/konkor)
 * [PayPal EURO](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=WVAS5RXRMYVC4)
 * [PayPal USD](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=HGAFMMMQ9MQJ2)
 * Contact to the author [here](https://konkor.github.io/index.html#contact)

_Behind the development for the Linux Desktop are ordinary people who spend a lot of time and their own resources to make the Linux Desktop better. Thank you for your contributions!_


## Installation
### Dependencies
* gjs
* gir1.2-soup
* gstreamer1.0-plugins-base-apps

Linux installation:
```
#make
chmod +x onetts
sudo cp onetts /usr/local/bin/
```

### Sources and binary packages
* [GitHub master branch](https://github.com/konkor/onetts/archive/master.zip)
