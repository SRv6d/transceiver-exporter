# Changelog

## 1.1.0 - 2022-08-25
### Changes
* Added the option to export optical power in dBm instead of mW
  * `-collector.optical-power-in-dbm`
  * Thanks for @BarbarossaTM (Cloudflare) for contributing this feature.
* Updated dependencies
  * Switched from deprecated `prometheus/common/log` to `sirupsen/logrus`

### Notes
* For this release we moved the repository from GitLab to GitHub.

## 1.0.1 - 2020-07-14
### Changes
* Switched to GoLang compliant versioning scheme
* Fixed a bug where the scrape would fail due to reading bad data

## 1.0 -  2020-07-13
### Changes
* Initial release
