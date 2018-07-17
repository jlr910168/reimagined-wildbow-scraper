# reimagined-wildbow-scraper

## Now deprecated in favor of [rust-wildbow-scraper](https://github.com/nicohman/rust-wildbow-scraper). Go use that instead!

Scrapes wildbow's twig, pact and worm into epubs with some extra ease-of-use features.
Run node app.js with -t, -w, -g, -r or -p to scrape twig, worm, glow-worm, ward or pact respectively. --help for more info.
New: Now scrapes Ward(Worm 2)!

## Installation

All you'll need is npm and node. Run:

`git clone https://github.com/nicohman/reimagined-wildbow-scraper.git`

`cd reimagined-wildbow-scraper`

`npm install`

`node app.js [options]`

You might want to add an alias such as `alias riws = node ~/reimagined-wildbow-scraper/app.js` to make it easier to use.

## Usage
`node app.js --help` for list of commands:
```
    -V, --version         output the version number
    -r , --resume <json>  Resume from JSON file
    -a, --ward            Scrape Ward
    -w, --worm            Scrape Worm
    -t, --twig            Scrape Twig
    -p, --pact            Scrape Pact
    -g, --glow_worm       Scrape Worm 2 Prologue
    -h, --help            output usage information
```

It'll output an epub and a json file in your current directory. If you want to, you can save the json file and use to to resume later, saving you from having to download the whole rest of whatever book you're following along with.
