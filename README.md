# gouseragent

Goでユーザーエージェント文字列を提供します。

## Install

```
go get github.com/code-raisan/gouseragent@latest
```

## Use

```golang
package main

import "github.com/code-raisan/gouseragent"

func main() {
	println(gouseragent.MozillaFirefoxWindows)
    // → Mozilla/5.0 (Windows NT ....
}
```

### 現在の対応UA

- Mozilla Firefox Windows (`gouseragent.MozillaFirefoxWindows`)

- Mozilla Firefox Linux (`gouseragent.MozillaFirefoxLinux`)

- Mozilla Firefox Mac (`gouseragent.MozillaFirefoxMac`)

- Mozilla Firefox Android (`gouseragent.MozillaFirefoxAndroid`)

- Google Chrome Windows (`gouseragent.GoogleChromeWindows`)

- Google Chrome Mac (`gouseragent.GoogleChromeMac`)

- Google Chrome Android (`gouseragent.GoogleChromeAndroid`)

- Google Chrome iOS (`gouseragent.GoogleChromeIos`)

- Apple Safari Mac (`gouseragent.AppleSafariMac`)

- Apple Safari iOS (`gouseragent.AppleSafariIos`)

- Google Bot (`gouseragent.GoogleBot`)

- Microsoft Bing Bot (`gouseragent.MicrosoftBingBot`)

- Twitter Bot (`gouseragent.TwitterBot`)

- Facebook External Hit (`gouseragent.FacebookBot`)

- Discord Bot (`gouseragent.DiscordBot`)

- Slack Link Expanding (`gouseragent.SlackBot`)