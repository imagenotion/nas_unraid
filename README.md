# Awacino for Unraid

Unraid template for the **Awacino unattended device**: it makes your Unraid
server reachable from the Awacino app - its terminal and its network - with no
port forwarding and no router settings.

## Install

1. In the Awacino app, open **Add unattended device → Install on NAS** and copy
   the setup code.
2. In Unraid, open **Apps** and search for **Awacino** (Community Applications), then paste the setup code
   and click **Apply**.

Without Community Apps: save `awacino-unattended.xml` as
`/boot/config/plugins/dockerMan/templates-user/my-awacino-unattended.xml`, then
use **Docker → Add Container → Template: awacino-unattended**.

The image is `docker.awacino.net/awacino/unattended:latest` (amd64 and arm64).

More: https://www.awacino.com/technology/unattended/#nas
Support: https://www.awacino.com/support/contact/
