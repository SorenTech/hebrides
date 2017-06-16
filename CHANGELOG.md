
2.0 / 2017-06-16
==================

  * Updating google analytics dahsboard to 5.0.1, sparkpost to 3.0.1
  * Bump google-analytics-dashboard and sparkpost plugins for major updates
  * Remove wp-smushit from wp-lock
  * Update wp-security-audit-log to 2.6.4
  * Updating wordpress-seo to 4.9
  * Updating updraftplus to 1.13.4
  * Update two-factor-authentication to 1.2.22
  * Updating so-widgets-bundle to 1.9.2
  * Updating jch-optimize to 2.1
  * Updating goodbye-captcah to 3.1.6
  * Updating dashboard widgets suite to 1.4
  * Updating broken link checker to 1.11.3
  * Fix: remove bnfw plugin from composer.lock
  * Reinstalling wordpress core to work around update to johnpbloch repo structure
  * Updating compser.lock to include new installed packages
  * Feat: Switch to shortpixel for image compression (better performance)
  * Fix: ignore error logs in version control
  * Feat: Switch to using sparkpost for email, better interoperability between different sites

1.5.3 / 2017-03-15
==================

  * Feat: Add Cloudflare and so-widgets-bundle as part of core stack

1.5.2 / 2017-03-15
==================

  * Updating wordpress, wp-security-audit-log, bnfw, wp-smushit, and php_codesnifer
  * Fix: don't specify exact version for google analytics dashboard
  * Feat: organize composer.json file
  * Beautify composer.json
  * Fix: Ignore files added by server or by hosting provider
  * Fix: don't track error or mail logs
  * Fix: manage all compsoer ignores in one place
  * Feat: Ignore theme files, we will always install these from a separate repo using composer

1.5.1 / 2017-03-04
==================

  * Upgrading updraftplus to 1.12.35
  * Initial checkin of synch.sh script

1.5.0 / 2017-03-02
==================

  * Adding dashboard widgets suite plugin
  * Adding Better Notitications for WordPress

1.4.0.2 / 2017-03-02
==================

  * Fix: removing auto-loading for now because it doesn't seem to work

1.4.0.1 / 2017-03-01
==================

  * Fix: Missed a few mu-plugins

1.4.0 / 2017-03-01
==================

  * Feat: designate core plugins as mu-plugins so that they autoload

1.3.0 / 2017-03-01
==================

  * Swapping MonsterInsights for Google Analytics Dashboard
  * Updating wordpress-seo to 4.4
  * Updating updraftplus to 1.12.34
  * Updating two-factor-authentication to 1.2.21

1.2.0 / 2016-02-17
==================

  * Feat: Adding s3 uploads variables to our sample .env file
  * Updating goodbye-captchca to 3.1.3
  * Updating wordpress-seo to 4.3
  * Updating wp-security-audit-log to 2.6
  * Updating two-factor-authentication to 1.2.17
  * Pulling down changes from upstream master

1.1.1. / 2017-02-02
==================

  * Updating wordpress-seo to 4.2.1
  * Updated two-factor-authentication to 1.2.16

1.1 / 2017-01-27
==================

  * Fix: Adding Goodbye Captcha/WP Bruiser plugin for spam protection
  * Fix: Remove WP-Spamshield-- not compatible with nginx

1.0.2 / 2017-01-26
==================

  * Fix: Update updraftplus to 1.12.32
  * Fix: Upgrading to WordPress 4.7.2 security release
  * Fix: Update dependency version designations so that non-breaking updates will be installed more seamlessly
  * Fix: Updating reference tags for two-factor-authentication plugin and wp-spamshield

1.0.1 / 2017-01-25
==================

  * Adding official new changelog
  * Renaming bedrock changelog to avoid confusion
  * Moved bedrock changelog to new file, starting separate changelog for this repository
  * Fix: spelling error on S3_UPLOADS_BUCKET_URL constant

1.0 / 2017-01-25
================

Initial Release
