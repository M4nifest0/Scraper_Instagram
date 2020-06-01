# Scraper_Instagram![Locations](https://github.com/attakercyebr/haxk4lx_toolkit/blob/master/levlogo.png) 

✂●●●●●●●●●●●●●●●●●●●●●●●●●●●●

![NPM](https://img.shields.io/npm/l/instatouch.svg?style=for-the-badge) ![npm](https://img.shields.io/npm/v/instatouch.svg?style=for-the-badge) ![Codacy grade](https://img.shields.io/codacy/grade/037f8049f7e048a2b03a95fda8863f39.svg?style=for-the-badge)

Scrape useful information from instagram.

No login or password are required.

This is not an official API support and etc. This is just a scraper that is using instagram graph api to scrape media.

✂●●●●●●●●●●●●●●●●●●●●●●●●●●●●

# Scraper_Instagram![Locations](https://github.com/attakercyebr/Scraper_Instagram/blob/master/1.jpg) 

# Scraper_Instagram![Locations](https://github.com/attakercyebr/Scraper_Instagram/blob/master/2.jpg) 

# Scraper_Instagram![Locations](https://github.com/attakercyebr/Scraper_Instagram/blob/master/3.jpg) 

# Scraper_Instagram![Locations](https://github.com/attakercyebr/Scraper_Instagram/blob/master/4.jpg) 

# Scraper_Instagram![Locations](https://github.com/attakercyebr/Scraper_Instagram/blob/master/6.jpg) 


✂●●●●●●●●●●●●●●●●●●●●●●●●●●●●

## Features

-   Scrape media posts from username, hashtag or location
-   Scrape comments from a specific instagram post
-   Scrape users who liked specific post
-   Scrape followers **`REQUIRES AN ACTIVE SESSION`**
-   Scrape following **`REQUIRES AN ACTIVE SESSION`**
-   Download and save media to a ZIP archive
-   Create JSON/CSV files with a post information

✂●●●●●●●●●●●●●●●●●●●●●●●●●●●●

**Note:**

-   If you need to download all user posts or comments then do not specify count or set it to 0(zero)
-   location and hashtag should always have count >0

✂●●●●●●●●●●●●●●●●●●●●●●●●●●●●

**Posts - JSON/CSV output:**

```
    id: '378545457875',
    isVideo: false,
    shortcode: 'hack4lx',
    takenAtTimestamp: 23123123,
    commentsDisabled: false,
    location:{
        id: '258698578',
        has_public_page: true,
        name: 'Eiffel Tower, Paris',
        slug: 'eiffel-tower-paris'
    },
    thumbnailSrc: 'THUMNAIL_URL',
    displayUrl:'PREVIEW_URL',
    url:'MAIN_URL_SRC',
    ownerId: '1321313',
    ownerUsername: 'hack4lx',
    likes: 232,
    comments: 11,
    views: 0,
```
✂●●●●●●●●●●●●●●●●●●●●●●●●●●●●

# How To Install and Use

git clone https://github.com/attakercyebr/Scraper_Instagram

cd Scraper_Instagram

Commands:
  instatouch user [id]      Scrape posts from username. Enter only username
  instatouch hashtag [id]   Scrape posts from hashtag. Enter hashtag without
  instatouch comments [id]  Scrape comments from a post. Enter post url or post id
  instatouch likers [id]    Scrape users who liked a post. Enter post url or post id

Options:
  --help                  Show help                                    [boolean]
  --version               Show version number                          [boolean]
  --count, -c             Number of post to scrape                  [default: 0]
  --mediaType             Media type to scrape
                             [choices: "image", "video", "all"] [default: "all"]
  --proxy, -p             Set proxy                                [default: ""]
  --download              Download and archive all scraped posts to a ZIP file
                                                      [boolean] [default: false]
  --asyncDownload         How many posts should be downloaded at the same time
                                                                    [default: 5]
  --progress              Show progress in terminal    [boolean] [default: true]
  --filename, --file, -f  Name of the output file              [default: "[id]"]
  --filepath              Directory to save file
                                           [default: "{CURRENT_PATH}"]
  --filetype, --type, -t  Type of output file
                              [choices: "csv", "json", "both"] [default: "json"]
```

**Example 1:**
Scrape 50 video posts from hashtag summer. Save post info in to a CSV file (by default)

```sh
$ instatouch hashtag Cyber --count 50 --mediaType video

Output:
JSON path: /{CURRENT_PATH}/Cyber_1552945544582.csv
```

**Example 2:**
Scrape 100 posts from user natgeo, download and save them to a ZIP archive. Save post info in to a JSON and CSV files (--filetype all)

```
$ instatouch user natgeo --count 100 --download true --filetype all

Output:
ZIP path: /{CURRENT_PATH}/natgeo_1552945659138.zip
JSON path: /{CURRENT_PATH}/natgeo_1552945659138.json
CSV path: /{CURRENT_PATH}/natgeo_1552945659138.csv
```

**Example 3:**
Scrape 50 posts from user natgeo, download and save them to a ZIP archive. Save post info in to a JSON and CSV files (--filetype all). Save all files to a custom path (--filepath /custom/path/to/save/files)

```
$ instatouch user natgeo --count 50 --download true --filetype all --filepath /custom/path/to/save/files

Output:
ZIP path: /custom/path/to/save/files/natgeo_1552945659138.zip
JSON path: /custom/path/to/save/files/natgeo_1552945659138.json
CSV path: /custom/path/to/save/files/natgeo_1552945659138.csv
```

**Example 4:**
Scrape 200 comments from this post https://www.instagram.com/p/hack4lx/. Save comment data in to a CSV file

```
$ instatouch comments https://www.instagram.com/p/hack4lx/ --count 50

Output:
CSV path: /{CURRENT_PATH}/hack4lx_1552945659138.csv
```

**Example 5:**
Scrape 200 users who liked this post https://www.instagram.com/p/hack4lx/. Save comment data in to a CSV file

```
$ instatouch likers https://www.instagram.com/p/hack4lx/ --count 200

Output:
CSV path: /{CURRENT_PATH}/hack4lx_1552945659138.csv
```
✂️●●●●●●●●●●●●●●●●●●●●●●●●●●●●

⚠️ Read-First:

🔞The author of the does not encourage anyone to repeat this. Otherwise, you will be solely responsible. The was created for informational purposes. And for the fact that you caution you!🙏

✂️●●●●●●●●●●●●●●●●●●●●●●●●●●●●

#Description👀

Title📌 Scraper_Instagram

💀 Made by ☠️👊 𝕿𝖍𝖎𝖘 𝕴𝖘 𝕿𝖍𝖊 𝓜4𝓷𝓲𝓯𝓮𝓼𝓽0 𝕿𝖊𝖆𝖒™💪🏴‍☠️

Author 🏴‍☠️ rainboy1 | erfan4lx | Vampire4lx

Aate ♾ 2020 May

Version 👁‍🗨 2.1.9

Usage 👌 cd Scraper_Instagram 

Channel  Combo List 👍  [![Telegram Chanel](https://img.shields.io/badge/chat%20on-Telegram-blue.svg)](https://t.me/hack4lxCombo)


✂️●●●●●●●●●●●●●●●●●●●●●●●●●●●●

[![Join To Telegram Groups](https://img.shields.io/badge/chat%20on-Telegram-blue.svg)](https://t.me/M4nifest0)
👆👆👆👆👆


☠️👊𝓷𝓲𝓯𝓮𝓼𝓽4𝓷𝓲𝓯𝓮𝓼𝓽0 (MCS) Telegram Groups We are a team of  𝓑𝓵𝓪𝓬𝓴  𝓗𝓪𝓽  𝓗𝓪𝓬𝓴𝓮𝓻𝓼  because we know what is at stake. We prepare hackers by providing training and hacking tools. We are one of the few Black hat hacking teams that show you their skills.👁‍🗨💪

✂️●●●●●●●●●●●●●●●●●●●●●●●●●●●●

Telegram Chat ID 📞 [![Telegram Chat](https://img.shields.io/badge/chat%20on-Telegram-blue.svg)](https://t.me/hack4lx)

✂️●●●●●●●●●●●●●●●●●●●●●●●●●●●●

<p align="center">
  ✯ Follow Me On ♥️
</p>
<p align="center">
  <a href="https://www.youtube.com/channel/UC73xXDVwfS8mE4ExtOg63sw/videos?view_as=subscriber">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQVvLr5fD-eMCnZcAP7FjjrSYKH22i5onx2VZVX8dydMoe-dQLHRmUKb8xs&s" width="40" height="40">
  </a>
  <a href="https://t.me/M4nifest0">
    <img src="https://media.istockphoto.com/vectors/white-paper-plane-on-blue-background-vector-illustration-vector-id951164518?s=170x170" width="40" height="40">
</p>

