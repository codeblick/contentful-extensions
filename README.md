# Contentful extensions

This folder contains a set of extensions using the [UI extensions SDK](https://github.com/contentful/ui-extensions-sdk).

## SERP Preview

This extension adds a preview for url, meta title and meta description. The field itself doesn't contain the url. 
It will search for a field called "slug" in the same entry. It extends the "JSON object" type.

[You can find a demo here.](https://codeblick.github.io/contentful-extensions/serp/demo.html)

If you wan't to install the extension just pass this url to contentful:

`https://raw.githubusercontent.com/codeblick/contentful-extensions/master/serp/extension.json`

## Slug

This extension creates a URL friendly string from the user input. If the slug is not changed it will default to
a slugified version of the field "entryTitle". It extends the "Short text" type.

[You can find a demo here.](https://codeblick.github.io/contentful-extensions/slug/demo.html)

If you wan't to install the extension just pass this url to contentful:

`https://raw.githubusercontent.com/codeblick/contentful-extensions/master/slug/extension.json`
