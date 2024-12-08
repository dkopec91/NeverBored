---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: false
tags: [ '3D Print', 'Functional']
showFullContent: true
---

{{< modelfiles mkrs="MKRS_URL" fname="FILE_NAME">}}

{{< modelviewer src="FILE_NAME.glb" alt="ALT" >}}

{{< rawhtml >}}
<table>
    <tr>
        <th style="text-align:center">Before</th>
        <th style="text-align:center" colspan=2>After</th>
    </tr>
    <tr>
        <td style="width:34%;">
            {{< zoomable src="before.jpg" alt="Before" >}}
        </td>
        <td style="border-right:0px;">
            {{< zoomable src="after.jpg" alt="After" >}}
        </td>
        <td style="border-left:0px;padding-left:0px;">
            {{< zoomable src="after2.jpg" alt="After" >}}
        </td>
    </tr>
</table>
{{< /rawhtml >}}