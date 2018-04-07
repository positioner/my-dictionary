# Dictionary in Tray

I frequently use [올ㅋ사전](http://allkdic.xoul.kr/), but it does not provide another dictionary that I also frequently use, so I made it.

This app now shows [Oxford Learner's Dictionaries](https://www.oxfordlearnersdictionaries.com/).

I plan to add a feature that a user can add another dictionary websites and choose one of them.

This app is built with [Electron](https://electronjs.org/) and [photon](http://photonkit.com).

Much code is from [tray-example](https://github.com/kevinsawicki/tray-example) and [electron-bookmark](https://github.com/2woongjae/electron-bookmark).

Icons are from [electron-bookmark](https://github.com/2woongjae/electron-bookmark).

## Running

```sh
git clone https://github.com/junghyun87/dictionary-in-tray
cd dictionary-in-tray
npm install
npm start
```

## Packaging

```sh
npm run package
open out/Dic-in-tray-darwin-x64/Dic-in-tray.app
```

![screenshot](https://user-images.githubusercontent.com/4505216/38454484-2f366892-3aa3-11e8-9e7c-baafd357891c.png)
