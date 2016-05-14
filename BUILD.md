# Build Notes

## ToDos / Ideas

- Use npm (instead of zip archive) to get shower scripts & templates - why? why not?
  - plus - easier to update and manage (??)


## Alternatives

Thanks to Adolfo Villafiorita for all the work on packaging shower (w/ s9).
Keep it up.
See <https://github.com/avillafiorita/slideshow-shower>



## Update Notes

Get zip archive from github/shower/shower  
- look for archive link e.g. shwr.me/shower.zip (note: do NOT use the github zip archive);
  the archive is hosted "externally"

Prepare new simpler file structure

move shower/themes/*  to just themes/*

## Material Theme

move themes/material/index.html  => slides.material.html   -- and change links in source e.g.

```
in head:
  <link rel="stylesheet" href="themes/material/styles/screen-16x10.css">
in body:
  <script src="shower.min.js"></script>
```

move themes/material/pictures/*    => pictures/*

note: pictures are user-content "images" (in contrast to "system/built-in" theme images in images folder)


## Ribbon theme

move themes/ribbon/index.html  => slides.ribbon.html   -- and change links in source
move themes/ribbon/pictures/*    => pictures/*
