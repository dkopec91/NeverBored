---
title: "{{ replace .Name "-" " " | title }}"
description: "{{ replace .Name "-" " " | title }}"
tags: [ '3D Print', 'Functional']
date: {{ .Date }}
draft: false
showFullContent: true
---

{{< modelfiles mkrs="MKRS_URL" fname="FILE_NAME">}}

{{< modelviewer src="FILE_NAME.glb" alt="A 3D visualization of..." >}}

{{< before_after >}}
{{< gallery >}}