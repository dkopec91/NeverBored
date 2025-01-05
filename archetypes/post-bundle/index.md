---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: false
tags: [ '3D Print', 'Functional']
showFullContent: true
---

{{< modelfiles mkrs="MKRS_URL" fname="FILE_NAME">}}

{{< modelviewer src="FILE_NAME.glb" alt="ALT" >}}

{{< before_after >}}