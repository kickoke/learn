---
title: "circular_buffer"
custom_edit_url: https://github.com/netdata/netdata/edit/master/libnetdata/circular_buffer/README.md
---



`struct circular_buffer` is an adaptive circular buffer. It will start at an initial size
and grow up to a maximum size as it fills. Two indices within the structure track the current
`read` and `write` position for data.
