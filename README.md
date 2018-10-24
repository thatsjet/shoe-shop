# shoe-shop
A collection of configs and assets to turn OWASP juice-shop into Nike shoe-shop.

**TODO:**
- Logo
- name
- favicon
- showChallengeSolveNotification:false
- domain for e-mails
- theme (try them out and pick one that looks like Nike.)
- gitHubRibbon=none
- cookieConsent:
  - backgroundColor
  - buttonColor
  - textColor
  - message
  - dismissText
  - linkeText

- Load shoes
  - name
  - description
  - price
  - image
  - reviews
    - text
    - author (jim, bender, ciso, support, morty, mc.safesearch)
- Supress alerts
- Logging location/shared volume
-

**Example:**
```
server:
  port: 3000
application:
  domain: shoe-sh.op
  name: 'Shoe Shop'
  logo: '/shoe-shop/swoosh.png'
  favicon: favicon_v2.ico
  numberOfRandomFakeUsers: 0
  showChallengeSolvedNotifications: true
  showCtfFlagsInNotifications: false
  showChallengeHints: true
  showVersionNumber: true
  theme: slate
  gitHubRibbon: orange
  twitterUrl: 'https://twitter.com/owasp_juiceshop'
  facebookUrl: 'https://www.facebook.com/owasp.juiceshop'
  planetOverlayMap: orangemap2k.jpg
  planetName: Orangeuze
  recyclePage:
    topProductImage: fruit_press.jpg
    bottomProductImage: apple_pressings.jpg
  altcoinName: Juicycoin
  cookieConsent:
    backgroundColor: '#eb6c44'
    textColor: '#ffffff'
    buttonColor: '#f5d948'
    buttonTextColor: '#000000'
    message: 'This website uses fruit cookies to ensure you get the juiciest tracking experience.'
    dismissText: 'Me want it!'
    linkText: 'But me wait!'
    linkUrl: 'https://www.youtube.com/watch?v=9PnbKL3wuH4'
  securityTxt:
    contact: 'mailto:donotreply@owasp-juice.shop'
    encryption: 'https://pgp.mit.edu/pks/lookup?op=get&search=0x062A85A8CBFBDCDA'
    acknowledgements: '/#/score-board'
products:
  -
    name: 'Apple Juice (1000ml)'
    price: 1.99
    description: 'The all-time classic.'
    image: apple_juice.jpg
    reviews:
      - { text: 'One of my favorites!', author: admin }

# ~~~~~ ... ~~~~~~
```
