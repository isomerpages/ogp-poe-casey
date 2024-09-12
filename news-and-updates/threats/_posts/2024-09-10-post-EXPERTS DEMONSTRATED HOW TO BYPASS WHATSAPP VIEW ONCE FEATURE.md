---
title: EXPERTS DEMONSTRATED HOW TO BYPASS WHATSAPP VIEW ONCE FEATURE
permalink: /experts-demonstrated-how-to-bypass-whatsapp-view-once-feature/
date: 2024-09-10
layout: post
description: Security experts have shown how to bypass WhatsApp's "View Once"
  feature, allowing users to view disappearing media multiple times. Learn about
  the vulnerability and how it affects your privacy.
image: ""
variant: tiptap
---
<h3><strong>Users are exploiting a privacy flaw in WhatsApp to bypass the app’s “View once” feature, allowing them to re-view messages.</strong></h3>
<p>The <a href="https://faq.whatsapp.com/578442220724722/?cms_platform=android" rel="noopener noreferrer nofollow" target="_blank">‘View Once</a>‘
feature in WhatsApp allows users to send photos, videos, and voice messages
that can only be viewed once by the recipient.</p>
<p>Recipients cannot forward, share, or copy the “View Once” media, and they
cannot take screenshots or screen recordings of it.</p>
<p>However, a bug in the feature in its browser-based web app allows recipients
to re-view the messages and save the picture and video, which should vanish
immediately after being displayed on the recipient’s device.&nbsp;The popular
instant messaging app also prevents users from taking screenshots.&nbsp;</p>
<p>The "View Once" feature is available only on mobile devices but not on
the web app and was first supported in 2021.&nbsp;</p>
<p>The researchers Tal Be’ery from Zengo X Research Team discovered the flaw
and published technical details of the issue this week.</p>
<p>The researchers responsibly disclosed their findings to Meta but decided
to publicly disclose the issue after discovering it was already being exploited
in the wild. They aimed to protect the privacy of WhatsApp users and provided
a <a href="https://medium.com/@TalBeerySec/once-and-forever-whatsapps-view-once-functionality-is-broken-302a508390b0" rel="noopener noreferrer nofollow" target="_blank">more technical version</a> of
the blog for further details.</p>
<p>The View once media messages are technically the same as regular media
messages, only with the “view once” flag set.&nbsp;<strong>Which means it’s the virtual equivalent of putting a note on the picture that says “don’t look”</strong>.
All that is required for attackers to circumvent it, is merely to set this
flag to false and the “view once” media immediately becomes “regular” media
and can be downloaded, forwarded and shared.” reads the <strong><a href="https://zengo.com/whatsapps-view-once-privacy-issue/" rel="noopener noreferrer nofollow" target="_blank">post</a> </strong>published
by Tal Be’ery.</p>
<p>“Given its media URL, the View once media can be downloaded&nbsp;<strong>by any client</strong>,
no authentication is needed (reader still needs the decryption key sent
with the message). Again making the task of limiting the exposure of the
media to controlled environments and platforms impossible&nbsp;</p>
<p></p>
<p>The researchers built an unofficial WhatsApp client app using Baileys,
an open-source implementation of the WhatsApp Web API, to demonstrate how
to bypass the “View once” feature. They reported their findings to Meta
but later discovered that others had already found and exploited the issue
earlier in the year. These malicious users modified the message flag from
“view once” to “false” using either a modified WhatsApp Android app or
a web extension.</p>
<p></p>
<blockquote>
<p>“To actually solve this issue, WhatsApp needs to apply a proper Digital
Rights Management (DRM) solution that also verifies there is hardware support
in place for such DRM. Such frameworks are provided by&nbsp;<a href="https://source.android.com/docs/core/media/drm" rel="noreferrer noopener" target="_blank">Android</a>&nbsp;and&nbsp;
<a href="https://developer.apple.com/streaming/fps/" rel="noreferrer noopener" target="_blank">iOS</a>&nbsp;and other modern Operating Systems.” suggest the expert.</p>
<p>“A less robust but easier solution would be to have the sender send the
“view once” message only to the primary device ( mobile ) and not to companion
linked devices ( web, desktop). Please note it will only defeat extensions
and is not relevant against patched mobile clients.”</p>
</blockquote>
<p>WhatsApp has yet to reveal when it plans to address the issue.</p>
<hr>
<p></p>
<p>Author: Pierluigi Paganini</p>