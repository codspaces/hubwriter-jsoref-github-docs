---
title: Host key verification failed
intro: 'As a security precaution, ssh keeps track of which hosts it has previously seen.'
versions:
  fpt: '*'
  ghec: '*'
topics:
  - SSH
shortTitle: Host key verification failed
---

This means that the key that the server to which your client is connecting presented a key that doesn't match the keys that your client has seen in the past.

It could be because the server changed its keys unexpectedly -- this has happened -- in which case there should be a news reports from trustworthy sources (including the server's official blog) announcing the change.

It could also be that for one reason or another your computer is connecting to a server that is **not** the the right server. In such cases, you probably do not want to connect. You'll probably want to reach out to your support, and then the server's support for help. If the server is being impersonated, the owner of the server will probably appreciate being informed.

For more information, see "[GitHub's SSH Key Fingerprints](/authentication/keeping-your-account-and-data-secure/githubs-ssh-key-fingerprints)."
