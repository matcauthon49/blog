+++
title = "reading"
description = "A list of books I've read/am reading."
sort_by = "date"
template = "prose.html"
page_template = "post.html"

[extra]
lang = "en"
+++

# currently reading
{{ collection(file="current.toml") }}

# fiction
{{ collection(file="fiction.toml") }}

# non fiction
{{ collection(file="nfiction.toml") }}

<!-- 
# to-read
{{ collection(file="toread.toml") }} -->
