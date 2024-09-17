<p align="center">
   <img alt="is-a.dev Banner" src="./media/banner.png">
</p>

<p align="center">
   <img alt="Domains" src="https://img.shields.io/github/directory-file-count/is-always-online/register/domains?color=4E48DE&label=domains&style=for-the-badge">
   <img alt="Open Pull Requests" src="https://img.shields.io/github/issues-raw/is-always-online/register?color=4E48DE&label=issues&style=for-the-badge">
   <img alt="Open Issues" src="https://img.shields.io/github/issues-pr-raw/is-always-online/register?color=4E48DE&label=pull%20requests&style=for-the-badge">
</p>

<h1 align="center">is-always.online</h1>

<p align="center"><strong>is-always-online</strong> is a service that allows developers to get ".is-always.online" domain for their websites, api service.</p>

### Discord Server

Make sure to join our Discord server:
https://discord.gg/78Mc4UVqMV

## Issues

If you have any problems, feel free to [open a issue](https://github.com/is-always-online/register/issues/new/choose).

If you have an issue that contains confidental infomation, send an email to security@is-always.online.

## Register

### Manual Registration

- [Fork](https://github.com/is-always-online/register/fork) and star this repository
- Add a new file called `your-domain-name.json` in the `domains` folder to register `your-domain-name.is-always.online`

```json
{
  "description": "Project Description",
  "subdomain": "example",
  "owner": {
    "repo": "https://github.com/username/repo",
    "email": "hello@example.com"
  },
  "record": {
    "A": ["1.1.1.1", "1.0.0.1"],
    "AAAA": ["::1", "::2"],
    "CNAME": "example.com",
    "MX": ["mx1.example.com", "mx2.example.com"],
    "TXT": ["example_verification=1234567890"]
  },

  "proxied": false
}
```

- Your pull request will be reviewed and merged. _Make sure to keep an eye on it incase we need you to make any changes!_
- After the pull request is merged, please allow up to 24 hours for the changes to propagate
- Enjoy your new `.is-always.online` domain!

## Status

You can check the uptime of our services on our [status dashboard](https://status.is-always.online).

### Donate

If you like this project, please consider donating so we can keep this project running forever!

<a href='https://ko-fi.com/K3K0QX2YQ' target='_blank'><img height='36' style='border:0px;height:36px;' src='https://storage.ko-fi.com/cdn/kofi2.png?v=3' alt='Buy Me a Coffee at ko-fi.com' /></a>
