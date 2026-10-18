# Files to upload to GitHub

Website: Steven's Travel Penang  |  Channel: https://www.youtube.com/@stevenstravelpenang7832
Total: 24 files (1 web page + 23 pictures). All picture links were tested and none are broken.

## The list

| # | File to upload | Video date | Video |
|---|----------------|-----------|-------|
| 1 | `index.html` | the website itself | all 23 videos |
| 2 | `images/2026-10-18.jpg` | 18 Oct | China’s 1st Rescue Cat Park |
| 3 | `images/2026-10-11.jpg` | 11 Oct | Ciqikou Ancient Town: 1,000 Years of History |
| 4 | `images/2026-10-04.jpg` | 4 Oct | Chongqing Jiefangbei: Night Walk & Food Heaven |
| 5 | `images/2026-10-03.jpg` | 3 Oct | Best Hotel in Chongqing? 44th Floor Suite Tour |
| 6 | `images/2026-09-27.jpg` | 27 Sept | China's Misty Gorge Hidden River Cruise |
| 7 | `images/2026-09-26.jpg` | 26 Sept | 1,700-Year-Old Gongtan Ancient Town |
| 8 | `images/2026-09-14.jpg` | 14 Sept | Tianmen Mountain Heavens Gate: Full Day & Night Review |
| 9 | `images/2026-09-13.jpg` | 13 Sept | Zhangjiajie's HIDDEN Night Market: Meili Xiangxi Grand Theatre |
| 10 | `images/2026-09-07.jpg` | 7 Sept | Zhangjiajie Must-Eat: Brigade Old Fishing Village 1973 |
| 11 | `images/2026-09-06.jpg` | 6 Sept | Huangshizhai + Golden Whip Stream: Zhangjiajie Line C - Full Review |
| 12 | `images/2026-08-31.jpg` | 31 Aug | Most Tourists Never See This: Zhangjiajie Line A - Full Review |
| 13 | `images/2026-08-30.jpg` | 30 Aug | Exploring Zhangjiajie Line B Full Review |
| 14 | `images/2026-08-23-a.jpg` | 23 Aug | World Champion Cave: Yellow Dragon Cave Full Tour |
| 15 | `images/2026-08-23-b.jpg` | 23 Aug | FULL Experience: Zhangjiajie Grand Canyon |
| 16 | `images/2026-08-16.jpg` | 16 Aug | China's Waterfall Town Comes Alive! Furong at Night |
| 17 | `images/2026-08-15.jpg` | 15 Aug | Walking Through a Waterfall! Furong Ancient Town |
| 18 | `images/2026-08-08.jpg` | 8 Aug | Hidden Gems of Furong Town: Floral Hotel · Baihe Huagu Hotel |
| 19 | `images/2026-07-26.jpg` | 26 July | Unreal Night Fenghuang |
| 20 | `images/2026-08-02.jpg` | 2 Aug | Dehang Local Tour: Aizhai Bridge & Miao Village |
| 21 | `images/2026-07-12.jpg` | 12 July | Train to Fenghuang |
| 22 | `images/2026-07-19.jpg` | 19 July | China's Most Beautiful Ancient Water Town |
| 23 | `images/2026-07-05.jpg` | 5 July | First Day in Zhangjiajie: Train + Hotel + Great Food + 72 Qilou |
| 24 | `images/2026-06-27.jpg` | 27 June | Zhangjiajie Self Travel Guide: 14 Days - RM 6K/pax All-in |

The 23 pictures go inside a folder named `images` (all lowercase). The page `index.html` stays in the main folder, not inside `images`.

## Option A: upload from a computer (recommended)

1. Unzip `github-final.zip`. You get `index.html`, an `images` folder and this list. Do not upload this list.
2. On github.com, create a new **Public** repository, for example `stevens-travel-penang`.
3. Click **uploading an existing file**. Drag in `index.html` and the whole `images` folder at the same time (use Chrome or Edge).
4. Wait until all 24 files are listed, then click **Commit changes**.
5. Open the repository, check that you see `index.html` and an `images` folder. Click the `images` folder and check that it holds 23 pictures.

## Option B: if the folder will not upload (phone, or Safari)

The page also finds pictures placed in the main folder. Upload all 24 files directly into the repository, with no folder. The pictures will still show.

## Turn on the website

1. Repository **Settings**, then **Pages**.
2. **Source**: Deploy from a branch. **Branch**: main. **Folder**: / (root). Click **Save**.
3. After one to two minutes the address is `https://YOUR-USERNAME.github.io/stevens-travel-penang/` (your username is under your profile picture, top right).

## If pictures do not show

- Refresh without the saved copy: Ctrl+Shift+R, or open the link in a private tab.
- Make sure the file names have not changed. They must match the list above exactly, all lowercase, ending in `.jpg`.
- Make sure `index.html` sits next to the `images` folder, not inside it.

## Adding a new video later

Send Claude the YouTube link, the publish date and a thumbnail named by date (for example `25_Oct.png`). Claude sends back a new `index.html` and one new picture. Upload both: **Add file**, **Upload files**, **Commit changes**.
