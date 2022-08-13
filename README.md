# Mesh-Studio-i18n
Translations for PewPew Mesh Studio.

## Contributing
IMPORTANT! Before translating to a language missing from the list, make an [issue](https://github.com/pewpewlive/Mesh-Studio-i18n/issues) first.

Translation process is very similar to [ppl-i18n](https://github.com/pewpewlive/ppl-i18n), except for `%s` we have `{0}`, `{1}`, etc. Some strings have `\n` in them. Keep them in! They signal a new line.

Use of poedit is discouraged since it adds header data we don't need and it adds unnecessary comments.

### What is `.mo` file?
`.mo` file is `.po` file, but in binary form. You can generate it using `msgfmt` utility or we will compile it for you.
