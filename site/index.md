---
layout: Home
title: Kata Containers Home

hero:
  headline: The speed of containers, the security of VMs
  button:
    title: Get Kata Containers 1.5
    url: https://github.com/kata-containers/runtime/releases/tag/1.5.0
    
getInvolvedSteps:
  - title: Join the mailing list
    entry: Receive email announcements and interaact with the community.
    link:
      url: mailto:mailman@lists.katacontainers.io
      title: mailman@lists.katacontainers.io
  - title: Slack or IRC
    entry: Chat with the project team and others using Kata Containers.
    link:
      url: https://wiki.openstack.org/wiki/Main_Page
      title: 'Slack: bit.ly/KataSlack  IRC: #kata-dev'
  - title: Weekly Architecture Committee Meetings
    entry: Updates from the community on a weekly basis.
    link:
      url: https://wiki.openstack.org/wiki/Main_Page
      title: View the Etherpad
---

<home-content>

<template slot="about">

## About Kata Containers

Kata Containers is an open source community working to build a secure container runtime with lightweight virtual machines that feel and perform like containers, but provide stronger workload isolation using hardware virtualization technology as a second layer of defense. 

Since launching in December 2017, the community successfully merged the best parts of Intel Clear Containers with Hyper.sh RunV and scaled to include support for major architectures including AMD64, ARM, IBM p-series and IBM z-series in addition to x86_64. Kata Containers also supports multiple hypervisors including QEMU, NEMU and Firecracker and integrates with the containerd project among others. 

The Kata Containers community is stewarded by the OpenStack Foundation (OSF), which supports the development and adoption of open infrastructure globally. The code is hosted at GitHub under the Apache 2 license.

<a href="/learn/" class="link is-primary"><strong>Learn More</strong></a>

</template>

<home-announcement slot="announcement" button-name="Learn More" link="/learn/">

In January 2019 the Kata Containers community landed the <a href="https://github.com/kata-containers/runtime/releases/tag/1.5.0">1.5 release</a>, which includes support for the Firecracker hypervisor from AWS, the IMB Z-Series s390x architecture as well as a new method for integrating with the containerd project. 

New hypervisors, new CPU architectures and significant integration improvements! 

</home-announcement>

</home-content>