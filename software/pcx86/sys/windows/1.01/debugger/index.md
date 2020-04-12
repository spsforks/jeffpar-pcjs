---
layout: page
title: Microsoft Windows 1.01 with Debugger
permalink: /software/pcx86/sys/windows/1.01/debugger/
machines:
  - id: ibm5160-ega-win101
    type: pcx86
    debugger: true
    resume: 1
    state: /software/pcx86/sys/windows/1.01/state.json
    config: /configs/pcx86/machine/ibm/5160/ega/640kb/debugger/machine.xml
    drives: '[{name:"10Mb Hard Disk",type:3,path:"/harddisks/pcx86/10mb/PCDOS200-WIN101-EGA.json"}]'
---

{% include machine.html id="ibm5160-ega-win101" %}