# Localization

## Adding a new localization

**See also https://mozilla-l10n.github.io/documentation/products/firefox_desktop/adding_nightly.html**

**Part One: Nightly**

- Update these files:
    - comm/mail/locales/all-locales
    - comm/mail/locales/l10n.toml
    - comm/mail/locales/l10n-changesets.json
    - comm/calendar/locales/all-locales
    - comm/calendar/locales/l10n.toml

Once that all lands and a Nightly runs, the next thing to check on is product-details.
Thunderbird.net uses **thunderbird_primary_builds.json** to create the download link for Nightly builds.
Product Details updates happen when a beta, release, or ESR gets shipped (Firefox or Thunderbird). Wait for that, then a rebuild of thunderbird.net may need to be triggered manually depending on various factors.

