# Web Font Styling Cheat Sheet

## Font Size

### PX to EM
```javascript
// Formula: size in pixels / base size in pixels
const unit =  `${12 / 16}em`
```

### PX to %
```javascript
// Formula: size in pixels / base size in pixels * 100
const unit = `${12 / 16 * 100}%`
```

### PX to PT
```javascript
// Formula: base size in pixels * (points per inch / pixels per inch)
const unit = `${16 * (72 / 96)}pt`
```

### EM to PX
```javascript
// Formula: size in EMs * base size in pixels
const unit = `${0.75 * 16}px`
```

### EM to %
```javascript
// Formula: size in EMs * 100
const unit = `${0.75 * 100}px`
```

---

## Font Weight

|Value|Name|Value|Name|Value|Name|
|-|-|-|-|-|-|
| 100 | UltraThin | 375 | Text | 600 | Bold |
| 150 | ExtraThin | 400 | Normal | 650 | ExtraBold |
| 200 | Thin | 425 | Thick | 700 | UltraBold |
| 250 | ExtraLite | 450 | ExtraThick | 800 | Black |
| 300 | Lite | 500 | Dark | 900 | ExtraBlack |
| 350 | Book | 550 | ExtraDark | 999 | UltraBlack |

---

## Letter Spacing

### EM Unit
```javascript
// Formula: size in design / 1000
const letterTrackingValue = 20
const emUnit = `${letterTrackingValue / 1000}em`
```

### PX Unit
```javascript
// Formula: size in design * base size in pixel / 1000
const letterTrackingValue = 20
const baseFontSize = 16
const pxUnit = `${letterTrackingValue * baseFontSize / 1000}px`
```

---

## Question:

If you have question, you can always contact me on Twitter [@genesis_neo](https://twitter.com/genesis_neo) and of course here in GitHub [@genesisneo](https://github.com/genesisneo). Thank you.

---

<p align="center">-=[ :heart: ]=-</p>
