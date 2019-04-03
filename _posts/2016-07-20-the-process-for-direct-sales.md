---
date: 2019-04-03
title: Gramup Quickstart
categories:
  - tutorial
author_staff_member: Dan
---


![Checkmate](https://source.unsplash.com/random/1500x645)

How to start to use free instagram automation tool Gramup? The quickstart tutorial is below. Reminder: we are currently an alpha version, so please be patient while waiting for new features and share your ideas with [us](https://t.me/instabotproject)!

## Minimal equirements

While we are in early alpha version, to use our tool you should fit the requirements below.

1. Update Google Chrome browser (on desktop!)
2. Install [Extension](https://chrome.google.com/webstore/detail/instagram-yourself/njonkbhnmmjgancfbncekpgkmidhbbpo)
3. Disable 2FA on your Instagram account
4. Don't close the website while it doing his job. If you close tab - everything would stop.

## How to start automating your Instagram

1. Install and update your [Google Chrome browser](https://chrome.google.com)
2. Install our extension from the [Official store](https://chrome.google.com/webstore/detail/instagram-yourself/njonkbhnmmjgancfbncekpgkmidhbbpo)
3. Press our pink icon and login with your Instagram account
4. Open https://insta.gramup.me
5. Enjoy!

![Office](https://source.unsplash.com/random/1500x1146)

## Tasks

Task is a collection of the requests, for example, a series of likes sent to user media. There are few types of tasks, some are listed above in the "Features" section: like by hashtag, like user's media, follow followers etc. Tasks are added to the queue.

  **When one task is added to the queue, you can't run any new tasks.**

This is intentional: we automatically make big pauses between all the requests so that we don't flood the API. If you want to run a new task, stop current, wait until it unwinds, and then continue.

During the work, task prints all the relevant information to the log. If one of the requests fail, task will continue to progress, and you can see an error and it's description in the log.

**If you were downloading something, the previous and the following results should be saved OK**

If some error happens and all the requests fail, you can stop the task manually. You'll need to wait until it will unwind to it's end, though. However, don't worry, **the data you've already downloaded should be safe and sound.**

If you feel the need for some custom task, you can drop us a feature request into [Issues](https://github.com/instagrambot/web/issues/new), [Telegram](https://t.me/instabotproject) or contribute here: [build custom task (Javascript)](https://github.com/instagrambot/web/blob/master/client/src/scripts.js).

## Updating the extension

While we are in early alpha version (again, sorry), please keep our Extension updated. Your browser should update it automatically. You can update it manually:

1. Go to [chrome://extensions](chrome://extensions)
2. Press update button on the top
<img width="300" alt="Developer mode" src="https://user-images.githubusercontent.com/1909384/53411050-9198b700-39d6-11e9-8300-088791dcf6dc.png">

![Raspberries](https://source.unsplash.com/random/1500x1147)
