---
title:  "테스트"
search: false
categories: 
  - Jekyll
tag: [test, jekyll]
last_modified_at: 2018-02-19T08:05:34-05:00
---

This post should not appear in the search index because it has the following YAML Front Matter:

```yaml
search: false
```
# header 1
## header 2
### header 3
#### header 4
##### header 5
###### header 6

**Note:** `search: false` only works to exclude posts when using **Lunr** as a search provider.
{: .notice--info}

To exclude files when using **Algolia** as a search provider add an array to `algolia.files_to_exclude` in your `_config.yml`. For more configuration options be sure to check their [full documentation](https://community.algolia.com/jekyll-algolia/options.html).

### title

```yaml
algolia:
  # Exclude more files from indexing
  files_to_exclude:
    - index.html
    - index.md
    - excluded-file.html
    - _posts/2017-11-28-post-exclude-search.md
    - subdirectory/*.html
```