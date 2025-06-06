---
seoDescription: Microsoft Lync enables interoperability with external IM networks including Skype and other providers, facilitating seamless communication across different platforms.
type: rule
archivedreason: Deprecated
title: Do you federate Lync with Skype and other external IM providers?
guid: abdf4b9c-232f-435b-8db2-201e73fa1095
uri: do-you-federate-lync-with-skype-and-other-external-im-providers
created: 2012-04-17T16:36:35.0000000Z
authors:
  - title: Daragh Bannigan
    url: https://twitter.com/dbannigan
    noimage: true
  - title: Adam Cogan
    url: https://ssw.com.au/people/adam-cogan
related: []
redirects: []
---

Lync supports "federation" - enabling interoperability with other IM networks. Lync Server enables organizations to interoperate with four external IM services: AOL Instant Messenger, .NET Messenger Service, Yahoo! Messenger, and Google Talk.

<!--endintro-->

Some businesses such as SSW used Microsoft accounts to improve collaboration with Partners and clients. Now that Lync has the ability to federate with public IM services, we have banned the usage of Skype, as Lync is now federated with Skype. Important to note that when you make a provisioning request for federation with Windows Live and specify a domain (such as SSW.com.au) as one of your SIP domains, you are reserving that domain for your organization's Lync Server instant messaging system. Affected Windows Live users must change their Windows Live IDs if this is associated with SSW.com.au in our example.

Lync Server enables one-to-one audio and video exclusively to PIC contacts that are homed to the Skype service. This change enables corporate users with a strong presence outside of work to reduce the need to run a separate client on their corporate workstation, yet maintain a robust communications experience.
