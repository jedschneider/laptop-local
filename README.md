# Laptop: Local Configuration

My local configuration setup for using [laptop](https://github.com/thoughtbot/laptop) to configure
my development and digital life.

[Medium
article](https://medium.com/@jedschneider/laptop-local-a-devops-oriented-workflow-for-mac-os-x-ecc67c6badf)

Uses [mas](https://github.com/mas-cli/mas) for App Store apps.
Uses [dotfiles](https://github.com/thoughtbot/dotfiles) for IDE config.

Brew and Cask for other dependency installs.

## Usage

1. Install Laptop
2. Clone repo
3. `sh laptop-local/setup`
4. `sh laptop/mac` (re-run laptop script)

## Other setup (reminders)

- Keybase is installed, but it needs to be configured for the user. Open keybase
  and be prepared with another keybase configured device to finish the 2FA.
Keybase is where I store an encrypted `dmg` backup of my .ssh directory. So once
keybase is connected I can pull down my ssh keys. This gives me access to github
and other connected services.

## Todo:

1. Automate the backup of secrets.
  - AWS Config files
  - .ssh directory
2. Fetch and bootstrap copies of cloud files (cloud storage vendor to be
   determined)
3. git configuration
