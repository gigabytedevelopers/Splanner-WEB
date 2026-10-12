# Security Upgrade

## 1. Vendored jQuery

The old jQuery distribution is replaced by upstream jQuery 3.7.1 and jQuery Migrate 3.4.1 from code.jquery.com. Existing script URLs are retained, and Migrate preserves deprecated plugin APIs while the application is modernized. Verify the existing form, navigation, and plugin interactions in a test deployment before merging.
