---
title: Upgrade to latest Version-Bagisto
layout: default
---

# Upgrade to latest version of Bagisto

To Upgrade your current version to latest version of bagisto, you need to follow some steps

- Firstly, you need to download the latest version of bagisto. You can download from these two provided links

1.  [Download Bagisto](https://bagisto.com/en/download/)
2.  [Download from Github](https://github.com/bagisto/bagisto)

- Now, after the download has been completed. Run some commands in terminal

1. Run _composer create-project_

2. After the command has been executed. Within your **.env** file, enter your old project database credentials for which you want to upgrade the bagisto.

3. Run _php artisan vendor:publish_

   -> Press 0 and then press enter to publish all assets and configurations.

4. Copy storage folder of older version of bagisto to latest downloaded bagisto version. You may find storage folder in project root

5. Run _php artisan storage:link_

6. Run _composer dump-autoload_
