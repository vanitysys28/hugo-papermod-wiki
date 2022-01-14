## Languages Supported

| Name                         | ISO Code | Available Translations                                                                      |
| ---------------------------- | -------- | ------------------------------------------------------------------------------------------- |
| Arabic                       | ar       | prev_page, next_page, read_time, toc, translations, home                                    |
| Bulgarian                    | bg       | prev_page, next_page, read_time, toc, translations                                          |
| Bengali                      | bn       | prev_page, next_page, read_time, toc, translations, home, edit_post, code_copy, code_copied |
| Catalan                      | ca       | prev_page, next_page, read_time, toc, translations, home                                    |
| Northern and Central Kurdish | ckb      | prev_page, next_page, read_time, toc, translations, home, code_copy, code_copied            |
| Danish                       | da       | prev_page, next_page, read_time, toc, translations, home, edit_post, code_copy, code_copied |
| German                       | de       | prev_page, next_page, read_time, toc, translations, edit_post                               |
| English                      | en       | prev_page, next_page, read_time, toc, translations, home, edit_post, code_copy, code_copied |
| Esperanto                    | eo       | prev_page, next_page, read_time, toc, translations, home, code_copy, code_copied            |
| Spanish                      | es       | prev_page, next_page, read_time, toc, translations, home, code_copy, code_copied            |
| Farsi                        | fa       | prev_page, next_page, read_time, toc, translations, home, code_copy, code_copied            |
| French                       | fr       | prev_page, next_page, read_time, toc, translations, home, code_copy, code_copied            |
| Hebrew                       | he       | prev_page, next_page, read_time, toc, translations, home                                    |
| Hindi                        | hi       | prev_page, next_page, read_time, toc, translations                                          |
| Hungarian                    | hu       | prev_page, next_page, read_time, toc, translations                                          |
| Indonesian                   | id       | prev_page, next_page, read_time, toc, translations                                          |
| Italian                      | it       | prev_page, next_page, read_time, toc, translations                                          |
| Japanese                     | ja       | prev_page, next_page, read_time, toc, translations, code_copy, code_copied                  |
| Korean                       | ko       | prev_page, next_page, read_time, toc, translations, home, code_copy, code_copied            |
| Kurdish                      | ku       | prev_page, next_page, read_time, toc, translations, home, code_copy, code_copied            |
| Mongolian                    | mn       | prev_page, next_page, read_time, toc, translations, home, code_copy, code_copied            |
| Dutch                        | nl       | prev_page, next_page, read_time, toc, translations, home, edit_post, code_copy, code_copied |
| Polish                       | pl       | prev_page, next_page, read_time, toc, translations, home, edit_post, code_copy, code_copied |
| Portuguese                   | pt       | prev_page, next_page, read_time, toc, translations                                          |
| Russian                      | ru       | prev_page, next_page, read_time, toc, translations                                          |
| Turkish                      | tr       | prev_page, next_page, read_time, toc, translations, home, code_copy, code_copied            |
| Ukrainian                    | uk       | prev_page, next_page, read_time, toc, translations, home, code_copy, code_copied            |
| Uzbek                        | uz       | prev_page, next_page, read_time, toc, translations, home                                    |
| Vietnamese                   | vi       | prev_page, next_page, read_time, toc, translations, home, code_copy, code_copied            |
| Taiwanese Chinese            | zh-tw    | rev_page, next_page, read_time, toc, translations, home, code_copy, code_copied             |
| Chinese                      | zh       | prev_page, next_page, read_time, toc, translations, home, code_copy, code_copied            |

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

- id: edit_post
  translation: "Edit"

- id: code_copy
  translation: "copy"

- id: code_copied
  translation: "copied!"
```
