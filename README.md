Mar 20, 2023 - v3

custom search update

---

## Repo structure  

```
search
.
├── _data
├── _layouts
├── _pages
├── json
├── scripts 
├── Gemfile
└── index.html
```

_data = holds the yml file to be used by the json script

_layouts = search-home / individual search page

_pages = blank index with front matter pointing to the search-*page* layout

json = parses the data in _data

scripts = search js rebuilt

Gemfile = gem "jekyll"

index.html = front matter -> search-home layout (customizable)

_data = contains sample.yml <-- file to be used by json script

_layouts = search-home / individual search page

_pages = blank index with front matter pointing to the search-*page* layout

json = parses the data in _data

scripts = search js rebuilt

Gemfile = gem "jekyll"

index.html = front matter -> search-home layout (customizable)


.
