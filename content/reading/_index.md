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


# to-read

I have a burning hatred for the Goodreads and Storygraph UIs and the personalities drawn to it, so I am demoing the use of this page to manage the books on my tbr. I am not expecting to ever complete this list.

**classical**
{{ collection(file="tr-classical.toml") }}

**classics**
{{ collection(file="tr-classics.toml") }}

**philosophy**

{{ collection(file="tr-philosophy.toml") }}

**general non-fiction**

{{ collection(file="tr-nf.toml") }}
