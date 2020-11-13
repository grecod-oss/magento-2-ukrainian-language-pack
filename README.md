# magento-2-ukrainian-language-pack

## Magento 2 Ukrainian Language Pack

Full **Magento 2 Ukrainian Language Pack** inlcudes maximum of translations, with error messages, even popular third party modules. You have to download a zip translation file via the link and install it on the store. Then, you should choose the right store locale (Ukrainian (Ukraine)) from the backend. Please get the guides below for the perfect convertion.

## How to Install Ukrainian Language Pack

There are 3 different methods to install this language pack.

### ✓ Method #1. Composer method (Recommend)
Install the Ukrainian language pack via composer is never easier.

**Install Ukrainian pack**:

```
composer require mageplaza/magento-2-ukrainian-language-pack:dev-master
php bin/magento setup:static-content:deploy -f uk_UA
php bin/magento indexer:reindex
php bin/magento cache:clean
php bin/magento cache:flush
```

**Update  Ukrainian pack**:

```
composer update mageplaza/magento-2-ukrainian-language-pack:dev-master
php bin/magento setup:static-content:deploy -f uk_UA
php bin/magento indexer:reindex
php bin/magento cache:clean
php bin/magento cache:flush

```

### ✓ Method #2. Copy & Paste method (Not recommended)

This method suitable for non-technical people such as merchants. Just download the package then flush cache.

**Overview**

- Step 1: Download the Ukrainian language pack
- Step 2: Unzip Ukrainian pack
- Step 3: Flush Magento 2 Cache

#### Step 1 : Download the Ukrainian language pack

You can download the language pack from above link

#### Step 2: Unzip Ukrainian pack

Unzip the Ukrainian language pack to Magento 2 root folder. In this guide, we extract to `/var/www/`
Your Magento 2 root folder can be: `/var/www/storename.com/`

```
unzip master.zip app/i18n/Grecod/
```

Rename folder `magento-2-ukrainian-language-pack` to `uk_ua`.


You also can unzip locally and upload them to Magento 2 root folder.

#### Step 3: Flush Magento 2 Cache

Flush Cache on your Magento 2 store


### ✓ Method #3. Download and install manually (Not recommended)

To download and install Ukrainian pack manually, you have to access to your server via FTP or SFTP.

#### Step 1: Download the package

- [Download .zip](https://github.com/grecod-oss/magento-2-ukrainian-language-pack/archive/master.zip)
- [Download .tar.gz](https://github.com/grecod-oss/magento-2-ukrainian-language-pack/tarball/master)

#### Step 1: Unzip and upload

Unzip the compressed file and upload file `master.zip` into `app/i18n/Grecod/uk_ua/`

This language pack code is: **uk_ua**

#### Step 2: Flush cache

Flush Cache on your Magento 2 store


## How to Activate the Ukrainian language pack 

Now time to active the Ukrainian language pack for your Magento 2 store. From Magento 2 admin panel, navigate to `Stores > Configuration > General > Locale Options`


## How to contribute

Contribute to this language at :
- [On Github](https://github.com/grecod-oss/): It's faster, our team will approve it after you send pull request.


## Supported Magento versions

It supports all Magento 2 versions include Magento 2 Open-Source (Community), Magento 2 Commerce (EE), Magento Cloud, Magento B2B, Magento MSI.

- Magento v2.0.x
- Magento v2.1.x
- Magento v2.2.x
- Magento v2.3.x
