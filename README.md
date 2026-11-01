# PabloAlaniz Tap

Homebrew formulae for [PabloAlaniz](https://github.com/PabloAlaniz)'s tools.

## domainhack

[domainhack](https://github.com/PabloAlaniz/find-amazing-domains) finds domain
hacks hiding in real words (plato -> pla.to) and checks them live at the
registries over RDAP and WHOIS, no API keys.

```bash
brew install pabloalaniz/tap/domainhack
domainhack name myproject
```

Or `brew tap pabloalaniz/tap` and then `brew install domainhack`. In a
`brew bundle` `Brewfile`:

```ruby
tap "pabloalaniz/tap"
brew "domainhack"
```

The formula is tested on macOS and Linux by `brew test-bot` on every push.
`brew help`, `man brew` or [Homebrew's documentation](https://docs.brew.sh)
for the rest.
