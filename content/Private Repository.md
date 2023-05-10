---

title: Private Repository(*alpha*)

enableToc: false

---
At this time, we offer limited specific support for private repositories. To use a private repository, please generate a key on your site dashboard. A public key will be added to the dashboard. Please add this to your git provider as a deploy key, or ssh key. Try to pull your site again.

Current support:
- SSH based
- Generated per-site deploy key

Future changes:
- Expanded git support
- Github oauth support
- Gitlab oauth support
- streamline git clone/pull implementation

`* If you want to use a private repo your url needs to be in the format git@[host]:[repo], (should not contain https://)`
`** If you are not using a private repo, delete your deploy key and use a public repo to ensure proper cloning`