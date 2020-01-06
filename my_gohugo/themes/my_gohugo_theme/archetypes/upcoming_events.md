---
title: "{{ replace .Name "-" " " | title }}"
address: ""
postalCode: "75000"
city: "Paris"
label: ""
when: "{{ dateFormat "02 January 2006" .Date }}"
description: ""
photos: ""
draft: true
important: false
association: ""
type: "upcoming_events"
---