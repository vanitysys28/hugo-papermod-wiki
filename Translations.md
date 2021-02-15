## Languages Supported

| Name       | ISO Code | Available Translations                                   |
| ---------- | -------- | -------------------------------------------------------- |
| Bulgarian  | bg       | prev_page, next_page, read_time, toc, translations       |
| Catalan    | ca       | prev_page, next_page, read_time, toc, translations, home |
| German     | de       | prev_page, next_page, read_time, toc, translations       |
| English    | en       | prev_page, next_page, read_time, toc, translations, home |
| Spanish    | es       | prev_page, next_page, read_time, toc, translations       |
| Farsi      | fa       | prev_page, next_page, read_time, toc, translations       |
| French     | fr       | prev_page, next_page                                     |
| Hindi      | hi       | prev_page, next_page, read_time, toc, translations       |
| Hungarian  | hu       | prev_page, next_page, read_time, toc, translations       |
| Indonesian | id       | prev_page, next_page, read_time, toc, translations       |
| Italian    | it       | prev_page, next_page, read_time, toc, translations       |
| Japanese   | ja       | prev_page, next_page, read_time, toc, translations       |
| Korean     | ko       | prev_page, next_page                                     |
| Russian    | ru       | prev_page, next_page, read_time, toc, translations       |
| Chinese    | zh       | prev_page, next_page, read_time, toc, translations       |

## Want to add your Language ?

Fork the theme, add `langcode.yaml` and submit a Pull Request.

Sample `langcode.yaml`

ISO codes can be found here: https://www.w3schools.com/tags/ref_language_codes.asp

```yml
- id: prev_page
  translation: "Prev Page"

- id: next_page
  translation: "Next Page"

- id: read_time
  translation:
      one: "1 min"
      other: "{{ .Count }} min"

- id: toc
  translation: "Table of Contents"

- id: translations
  translation: "Translations"

- id: home
  translation: "Home"
```
