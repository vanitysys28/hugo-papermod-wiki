## Languages Supported

| Name       | ISO Code | Available Translations                                                                      |
| ---------- | -------- | ------------------------------------------------------------------------------------------- |
| Arabic     | ar       | prev_page, next_page, read_time, toc, translations, home                                    |
| Bulgarian  | bg       | prev_page, next_page, read_time, toc, translations                                          |
| Catalan    | ca       | prev_page, next_page, read_time, toc, translations, home                                    |
| German     | de       | prev_page, next_page, read_time, toc, translations, edit_post                               |
| English    | en       | prev_page, next_page, read_time, toc, translations, home, edit_post, code_copy, code_copied |
| Spanish    | es       | prev_page, next_page, read_time, toc, translations                                          |
| Farsi      | fa       | prev_page, next_page, read_time, toc, translations                                          |
| French     | fr       | prev_page, next_page                                                                        |
| Hebrew     | he       | prev_page, next_page, read_time, toc, translations, home                                    |
| Hindi      | hi       | prev_page, next_page, read_time, toc, translations                                          |
| Hungarian  | hu       | prev_page, next_page, read_time, toc, translations                                          |
| Indonesian | id       | prev_page, next_page, read_time, toc, translations                                          |
| Italian    | it       | prev_page, next_page, read_time, toc, translations                                          |
| Japanese   | ja       | prev_page, next_page, read_time, toc, translations                                          |
| Korean     | ko       | prev_page, next_page                                                                        |
| Portuguese | pt       | prev_page, next_page, read_time, toc, translations                                          |
| Russian    | ru       | prev_page, next_page, read_time, toc, translations                                          |
| Uzbek      | uz       | prev_page, next_page, read_time, toc, translations, home                                    |
| Chinese    | zh       | prev_page, next_page, read_time, toc, translations                                          |

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

- id: code_copy
  translation: "copy"

- id: code_copied
  translation: "copied!"
```
