# Awacino for Unraid

Unraid template for the **Awacino unattended device**: it makes your Unraid
server reachable from the Awacino app - its terminal and its network - with no
port forwarding and no router settings.

## Install

1. In the Awacino app, open **Add unattended device → Install on NAS** and copy
   the setup code.
2. In Unraid, open **Settings → Docker → Template Repositories**, add
   `https://github.com/imagenotion/nas_unraid` and click **Save**.
3. Open **Docker → Add Container**, choose **Template: awacino-unattended**,
   paste the setup code and click **Apply**.

Once Awacino is listed in Community Applications, you can also find it under
**Apps** by searching for Awacino.

The image is `docker.awacino.net/awacino/unattended:latest` (amd64 and arm64).

More: https://www.awacino.com/technology/unattended/#nas
Support: https://www.awacino.com/support/contact/

## Licence

The files in this repository (template, profile, README) are MIT licensed, see
`LICENSE`. The Awacino application and the container image are licensed
separately: https://www.awacino.com/licence/
