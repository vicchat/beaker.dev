---
title: Video Chat Template
---

{{< rawhtml >}}
<img class="template-thumb" src="/templates/video-chat.png">

<button class="create-drive">Create Drive From This Template</button>

<script>
  const TEMPLATE_ROOT = '/templates/video-chat'
  const TEMPLATE_TITLE = 'My Video Chat'
  window.TEMPLATE_FILES = [
    '/index.html'
  ]
</script>
<script src="/templates/index.js"></script>
{{< /rawhtml >}}

This template creates a minimal video chat between the visitors of the site. It uses the [Peersockets API](https://docs.beakerbrowser.com/apis/beaker.peersockets) to set up a WebRTC video call between users. Traffic is encrypted so that only users who possess the site's URL can read it.

(Note: this is a simple demo and won't work with more than 2 users.)

## Source

{{< tabsraw >}}
{{< tab "/index.html" >}}
{{< readcode "/static/templates/video-chat/index.html" "html" >}}
{{< /tab >}}
{{< tab "LICENSE" >}}
{{< readcode "/static/templates/LICENSE" "txt" >}}
{{< /tab >}}
{{< /tabsraw >}}