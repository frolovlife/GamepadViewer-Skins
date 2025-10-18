# :information_source: General info

These are custom skins of various controllers for [GamepadViewer](https://gamepadviewer.com/). You can use them to display the buttons that are being pressed on your stream as an overlay.

> [!IMPORTANT]
> GamepadViewer works with XInput controllers. Work with DirectInput controllers is not guaranteed.

From time to time, I'll be tweaking existing skins and adding new ones. Please Star this project to avoid losing it.

## :tv: How to use with OBS Studio, StreamLabs etc.

1. Choose the controller skin you want to display on your stream below.
2. Copy the link for OBS Studio with or without mapping, as needed.<br>*Some controllers, such as the 8BitDo M30, don't have analog sticks, but their D-pad functions as the left stick. To ensure proper operation with these controllers, use the link with mapped LStick to DPad.*
3. Create a Browser source on the scene in OBS Studio.
4. Paste the copied link into the Browser source URL field and click «OK».
> [!NOTE]
> All links for OBS Studio are designed for the first player's controller. To display the second, third, or fourth player's controller, replace `p=1` in the link with `p=2`, `p=3`, or `p=4` respectively.

## :wrench: How to use with GamepadViewer's URL generator

1. Choose the controller skin you want to display on your stream below.
2. Copy the raw CSS link of these skin.
3. Go to [GamepadViewer URL Generator](https://gamepadviewer.com/#generate).
4. Paste the copied link into the «Custom CSS URL» field.
5. Configure the remaining parameters as desired and copy the generated link.
6. Paste the generated link into the Browser source address bar in OBS Studio and click «OK».

# :video_game: Controller skins

- [8BitDo](#8bitdo)
  - [8BitDo M30 (black)](#8bitdo-m30-black)
  - [8BitDo M30 (white)](#8bitdo-m30-white)
- [**Sega**](#sega)
  - [Sega Mega Drive 2 (Genesis 2)](#sega-mega-drive-2-genesis-2)
  - [Sega Saturn model 2 (black)](#sega-saturn-model-2-black)
  - [Sega Saturn model 2 (white)](#sega-saturn-model-2-white)
  - [Sega Saturn model 2 (gray)](#sega-saturn-model-2-gray)
- [**Nintendo**](#nintendo)
  - [Famicom](#famicom)
  - [NES](#nes)
  - [NES «Dogbone»](#nes-dogbone)
  - [Super Famicom](#super-famicom)
  - [SNES (USA)](#snes-usa)
  - [SNES (Europe)](#snes-europe)
- [**Famiclones**](#famiclones)
  - [Dendy Classic](#dendy-classic)
  - [Dendy Junior (var. 1)](#dendy-junior-var-1)
  - [Dendy Junior (var. 2)](#dendy-junior-var-2)
- [**NEC**](#nec)
  - [NEC PC Engine PI-PD001](#nec-pc-engine-pi-pd001)
  - [NEC PC Engine PI-PD002](#nec-pc-engine-pi-pd002)
  - [NEC PC Engine PI-PD6](#nec-pc-engine-pi-pd6)
  - [NEC PC Engine PI-PD8](#nec-pc-engine-pi-pd8)
  - [NEC TurboGrafx 16](#nec-turbografx-16)
  - [NEC PC Engine Duo](#nec-pc-engine-duo)
  - [NEC TurboDuo](#nec-turboduo)
  - [NEC PC Engine PCE-TP2](#nec-pc-engine-pce-tp2)
  - [NEC PC Engine PCE-TP1 (Arcade Pad 6)](#nec-pc-engine-pce-tp1-arcade-pad-6)
  - [NEC PC-FX](#nec-pc-fx)
- [**SNK**](snk)
  - [Neo-Geo CD](#neo-geo-cd)


## 8BitDo

### 8BitDo M30 (black)

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/8bitdo/m30/preview-black.svg" width="40%"></p>

- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/8bitdo/m30-black.css)
- [For OBS Studio etc. (with mapping: LStick to DPad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/8bitdo/m30-black.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/8bitdo/m30-black.css)

### 8BitDo M30 (white)

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/8bitdo/m30/preview-white.svg" width="40%"></p>

- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/8bitdo/m30-white.css)
- [For OBS Studio etc. (with mapping: LStick to DPad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/8bitdo/m30-white.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/8bitdo/m30-white.css)

## Sega

### Sega Mega Drive 2 (Genesis 2)

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/sega/megadrive2/preview.svg" width="40%"></p>

- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/sega/megadrive2.css)
- [For OBS Studio etc. (with mapping: LStick to DPad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/sega/megadrive2.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [For OBS Studio etc. (with mapping: LStick to DPad, LT to Mode)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/sega/megadrive2.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"8","disabled":false,"choiceType":"buttons","choice":"6"}]}) (for 8BitDo M30)
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/sega/megadrive2.css)

### Sega Saturn model 2 (black)

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/sega/saturn-m2/preview-black.svg" width="40%"></p>

- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/sega/saturn-m2-black.css)
- [For OBS Studio etc. (with mapping: LStick to DPad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/sega/saturn-m2-black.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/sega/saturn-m2-black.css)

### Sega Saturn model 2 (white)

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/sega/saturn-m2/preview-white.svg" width="40%"></p>

- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/sega/saturn-m2-white.css)
- [For OBS Studio etc. (with mapping: LStick to DPad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/sega/saturn-m2-white.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/sega/saturn-m2-white.css)

### Sega Saturn model 2 (gray)

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/sega/saturn-m2/preview-gray.svg" width="40%"></p>

- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/sega/saturn-m2-gray.css)
- [For OBS Studio etc. (with mapping: LStick to DPad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/sega/saturn-m2-gray.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/sega/saturn-m2-gray.css)


## Nintendo

### Famicom

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/nintendo/famicom/preview-famicom.svg" width="40%">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/nintendo/famicom/preview-famicom-xy.svg" width="40%"></p>

Original
- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nintendo/famicom.css)
- [For OBS Studio etc. (with mapping: X to A, A to B)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nintendo/famicom.css&map={"mapping":[{"targetType":"buttons","target":"0","disabled":false,"choiceType":"buttons","choice":"2"},{"targetType":"buttons","target":"1","disabled":false,"choiceType":"buttons","choice":"0"},{"targetType":"buttons","target":"2","disabled":false,"choiceType":"buttons","choice":"3"},{"targetType":"buttons","target":"3","disabled":false,"choiceType":"buttons","choice":"1"}]})
- [For OBS Studio etc. (with mapping: LStick to DPad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nintendo/famicom.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [For OBS Studio etc. (with mapping: LStick to DPad, X to A, A to B)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nintendo/famicom.css&map={"mapping":[{"targetType":"buttons","target":"0","disabled":false,"choiceType":"buttons","choice":"2"},{"targetType":"buttons","target":"1","disabled":false,"choiceType":"buttons","choice":"0"},{"targetType":"buttons","target":"2","disabled":false,"choiceType":"buttons","choice":"3"},{"targetType":"buttons","target":"3","disabled":false,"choiceType":"buttons","choice":"1"},{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/nintendo/famicom.css)

With buttons X and Y
- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nintendo/famicom-xy.css)
- [For OBS Studio etc. (with mapping: LStick to DPad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nintendo/famicom-xy.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/nintendo/famicom-xy.css)

### NES

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/nintendo/nes/preview.svg" width="40%">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/nintendo/nes/preview-xy.svg" width="40%"></p>

Original
- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nintendo/nes.css)
- [For OBS Studio etc. (with mapping: X to A, A to B)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nintendo/nes.css&map={"mapping":[{"targetType":"buttons","target":"0","disabled":false,"choiceType":"buttons","choice":"2"},{"targetType":"buttons","target":"1","disabled":false,"choiceType":"buttons","choice":"0"},{"targetType":"buttons","target":"2","disabled":false,"choiceType":"buttons","choice":"3"},{"targetType":"buttons","target":"3","disabled":false,"choiceType":"buttons","choice":"1"}]})
- [For OBS Studio etc. (with mapping: LStick to DPad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nintendo/nes.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [For OBS Studio etc. (with mapping: LStick to DPad, X to A, A to B)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nintendo/nes.css&map={"mapping":[{"targetType":"buttons","target":"0","disabled":false,"choiceType":"buttons","choice":"2"},{"targetType":"buttons","target":"1","disabled":false,"choiceType":"buttons","choice":"0"},{"targetType":"buttons","target":"2","disabled":false,"choiceType":"buttons","choice":"3"},{"targetType":"buttons","target":"3","disabled":false,"choiceType":"buttons","choice":"1"},{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/nintendo/nes.css)

With buttons X and Y
- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nintendo/nes-xy.css)
- [For OBS Studio etc. (with mapping: LStick to DPad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nintendo/nes-xy.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/nintendo/nes-xy.css)

### NES «Dogbone»

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/nintendo/dogbone/preview.svg" width="40%"></p>

- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nintendo/dogbone.css)
- [For OBS Studio etc. (with mapping: X to A, A to B)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nintendo/dogbone.css&map={"mapping":[{"targetType":"buttons","target":"0","disabled":false,"choiceType":"buttons","choice":"2"},{"targetType":"buttons","target":"1","disabled":false,"choiceType":"buttons","choice":"0"},{"targetType":"buttons","target":"2","disabled":false,"choiceType":"buttons","choice":"3"},{"targetType":"buttons","target":"3","disabled":false,"choiceType":"buttons","choice":"1"}]})
- [For OBS Studio etc. (with mapping: LStick to DPad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nintendo/dogbone.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [For OBS Studio etc. (with mapping: LStick to DPad, X to A, A to B)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nintendo/dogbone.css&map={"mapping":[{"targetType":"buttons","target":"0","disabled":false,"choiceType":"buttons","choice":"2"},{"targetType":"buttons","target":"1","disabled":false,"choiceType":"buttons","choice":"0"},{"targetType":"buttons","target":"2","disabled":false,"choiceType":"buttons","choice":"3"},{"targetType":"buttons","target":"3","disabled":false,"choiceType":"buttons","choice":"1"},{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/nintendo/dogbone.css)

### Super Famicom

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/nintendo/snes/preview-sfc.svg" width="40%"></p>

- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nintendo/sfc.css)
- [For OBS Studio etc. (with mapping: LStick to DPad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nintendo/sfc.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [For OBS Studio etc. (with mapping: LStick to DPad, LT to RB)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nintendo/sfc.css&map={"mapping":[{"targetType":"buttons","target":"5","disabled":false,"choiceType":"buttons","choice":"6"},{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]}) (for 8BitDo M30)
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/nintendo/sfc.css)

### SNES (USA)

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/nintendo/snes/preview-snes.svg" width="40%"></p>

- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nintendo/snes.css)
- [For OBS Studio etc. (with mapping: LStick to DPad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nintendo/snes.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [For OBS Studio etc. (with mapping: LStick to DPad, LT to RB)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nintendo/snes.css&map={"mapping":[{"targetType":"buttons","target":"5","disabled":false,"choiceType":"buttons","choice":"6"},{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]}) (for 8BitDo M30)
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/nintendo/snes.css)

### SNES (Europe)

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/nintendo/snes/preview-snes-eu.svg" width="40%"></p>

- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nintendo/snes-eu.css)
- [For OBS Studio etc. (with mapping: LStick to DPad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nintendo/snes-eu.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [For OBS Studio etc. (with mapping: LStick to DPad, LT to RB)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nintendo/snes-eu.css&map={"mapping":[{"targetType":"buttons","target":"5","disabled":false,"choiceType":"buttons","choice":"6"},{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]}) (for 8BitDo M30)
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/nintendo/snes-eu.css)


## Famiclones

### Dendy Classic

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/famiclones/dendy-classic/preview.svg" width="40%"></p>

- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/famiclones/dendy-classic.css)
- [For OBS Studio etc. (with mapping: LStick to DPad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/famiclones/dendy-classic.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/famiclones/dendy-classic.css)

### Dendy Junior (var. 1)

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/famiclones/dendy-junior/preview-v1.svg" width="40%"></p>

- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/famiclones/dendy-junior-v1.css)
- [For OBS Studio etc. (with mapping: LStick to DPad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/famiclones/dendy-junior-v1.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/famiclones/dendy-junior-v1.css)

### Dendy Junior (var. 2)

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/famiclones/dendy-junior/preview-v2.svg" width="40%"></p>

- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/famiclones/dendy-junior-v2.css)
- [For OBS Studio etc. (with mapping: LStick to DPad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/famiclones/dendy-junior-v2.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/famiclones/dendy-junior-v2.css)


## NEC

### NEC PC Engine PI-PD001

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/nec/pc-engine/preview-pd001.svg" width="40%">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/nec/pc-engine/preview-pd001-xy.svg" width="40%"></p>

Original
- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pd001.css)
- [For OBS Studio etc. (with mapping: X to A, A to B)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pd001.css&map={"mapping":[{"targetType":"buttons","target":"0","disabled":false,"choiceType":"buttons","choice":"2"},{"targetType":"buttons","target":"1","disabled":false,"choiceType":"buttons","choice":"0"},{"targetType":"buttons","target":"2","disabled":false,"choiceType":"buttons","choice":"3"},{"targetType":"buttons","target":"3","disabled":false,"choiceType":"buttons","choice":"1"}]})
- [For OBS Studio etc. (with mapping: LStick to DPad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pd001.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [For OBS Studio etc. (with mapping: LStick to DPad, X to A, A to B)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pd001.css&map={"mapping":[{"targetType":"buttons","target":"0","disabled":false,"choiceType":"buttons","choice":"2"},{"targetType":"buttons","target":"1","disabled":false,"choiceType":"buttons","choice":"0"},{"targetType":"buttons","target":"2","disabled":false,"choiceType":"buttons","choice":"3"},{"targetType":"buttons","target":"3","disabled":false,"choiceType":"buttons","choice":"1"},{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/nec/pd001.css)

With buttons X and Y
- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pd001-xy.css)
- [For OBS Studio etc. (with mapping: LStick to DPad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pd001-xy.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/nec/pd001-xy.css)

### NEC PC Engine PI-PD002

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/nec/pc-engine/preview-pd002.svg" width="40%">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/nec/pc-engine/preview-pd002-xy.svg" width="40%"></p>

Original
- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pd002.css)
- [For OBS Studio etc. (with mapping: X to A, A to B)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pd002.css&map={"mapping":[{"targetType":"buttons","target":"0","disabled":false,"choiceType":"buttons","choice":"2"},{"targetType":"buttons","target":"1","disabled":false,"choiceType":"buttons","choice":"0"},{"targetType":"buttons","target":"2","disabled":false,"choiceType":"buttons","choice":"3"},{"targetType":"buttons","target":"3","disabled":false,"choiceType":"buttons","choice":"1"}]})
- [For OBS Studio etc. (with mapping: LStick to DPad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pd002.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [For OBS Studio etc. (with mapping: LStick to DPad, X to A, A to B)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pd002.css&map={"mapping":[{"targetType":"buttons","target":"0","disabled":false,"choiceType":"buttons","choice":"2"},{"targetType":"buttons","target":"1","disabled":false,"choiceType":"buttons","choice":"0"},{"targetType":"buttons","target":"2","disabled":false,"choiceType":"buttons","choice":"3"},{"targetType":"buttons","target":"3","disabled":false,"choiceType":"buttons","choice":"1"},{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/nec/pd002.css)

With buttons X and Y
- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pd002-xy.css)
- [For OBS Studio etc. (with mapping: LStick to DPad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pd002-xy.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/nec/pd002-xy.css)

### NEC PC Engine PI-PD6

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/nec/pc-engine/preview-pd6.svg" width="40%">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/nec/pc-engine/preview-pd6-xy.svg" width="40%"></p>

Original
- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pd6.css)
- [For OBS Studio etc. (with mapping: X to A, A to B)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pd6.css&map={"mapping":[{"targetType":"buttons","target":"0","disabled":false,"choiceType":"buttons","choice":"2"},{"targetType":"buttons","target":"1","disabled":false,"choiceType":"buttons","choice":"0"},{"targetType":"buttons","target":"2","disabled":false,"choiceType":"buttons","choice":"3"},{"targetType":"buttons","target":"3","disabled":false,"choiceType":"buttons","choice":"1"}]})
- [For OBS Studio etc. (with mapping: LStick to DPad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pd6.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [For OBS Studio etc. (with mapping: LStick to DPad, X to A, A to B)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pd6.css&map={"mapping":[{"targetType":"buttons","target":"0","disabled":false,"choiceType":"buttons","choice":"2"},{"targetType":"buttons","target":"1","disabled":false,"choiceType":"buttons","choice":"0"},{"targetType":"buttons","target":"2","disabled":false,"choiceType":"buttons","choice":"3"},{"targetType":"buttons","target":"3","disabled":false,"choiceType":"buttons","choice":"1"},{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/nec/pd6.css)

With buttons X and Y
- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pd6-xy.css)
- [For OBS Studio etc. (with mapping: LStick to DPad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pd6-xy.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/nec/pd6-xy.css)

### NEC PC Engine PI-PD8

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/nec/pc-engine/preview-pd8.svg" width="40%">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/nec/pc-engine/preview-pd8-xy.svg" width="40%"></p>

Original
- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pd8.css)
- [For OBS Studio etc. (with mapping: X to A, A to B)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pd8.css&map={"mapping":[{"targetType":"buttons","target":"0","disabled":false,"choiceType":"buttons","choice":"2"},{"targetType":"buttons","target":"1","disabled":false,"choiceType":"buttons","choice":"0"},{"targetType":"buttons","target":"2","disabled":false,"choiceType":"buttons","choice":"3"},{"targetType":"buttons","target":"3","disabled":false,"choiceType":"buttons","choice":"1"}]})
- [For OBS Studio etc. (with mapping: LStick to DPad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pd8.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [For OBS Studio etc. (with mapping: LStick to DPad, X to A, A to B)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pd8.css&map={"mapping":[{"targetType":"buttons","target":"0","disabled":false,"choiceType":"buttons","choice":"2"},{"targetType":"buttons","target":"1","disabled":false,"choiceType":"buttons","choice":"0"},{"targetType":"buttons","target":"2","disabled":false,"choiceType":"buttons","choice":"3"},{"targetType":"buttons","target":"3","disabled":false,"choiceType":"buttons","choice":"1"},{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/nec/pd8.css)

With buttons X and Y
- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pd8-xy.css)
- [For OBS Studio etc. (with mapping: LStick to DPad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pd8-xy.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/nec/pd8-xy.css)

### NEC TurboGrafx 16

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/nec/pc-engine/preview-tg16.svg" width="40%">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/nec/pc-engine/preview-tg16-xy.svg" width="40%"></p>

Original
- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/tg16.css)
- [For OBS Studio etc. (with mapping: X to A, A to B)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/tg16.css&map={"mapping":[{"targetType":"buttons","target":"0","disabled":false,"choiceType":"buttons","choice":"2"},{"targetType":"buttons","target":"1","disabled":false,"choiceType":"buttons","choice":"0"},{"targetType":"buttons","target":"2","disabled":false,"choiceType":"buttons","choice":"3"},{"targetType":"buttons","target":"3","disabled":false,"choiceType":"buttons","choice":"1"}]})
- [For OBS Studio etc. (with mapping: LStick to DPad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/tg16.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [For OBS Studio etc. (with mapping: LStick to DPad, X to A, A to B)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/tg16.css&map={"mapping":[{"targetType":"buttons","target":"0","disabled":false,"choiceType":"buttons","choice":"2"},{"targetType":"buttons","target":"1","disabled":false,"choiceType":"buttons","choice":"0"},{"targetType":"buttons","target":"2","disabled":false,"choiceType":"buttons","choice":"3"},{"targetType":"buttons","target":"3","disabled":false,"choiceType":"buttons","choice":"1"},{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/nec/tg16.css)

With buttons X and Y
- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/tg16-xy.css)
- [For OBS Studio etc. (with mapping: LStick to DPad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/tg16-xy.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/nec/tg16-xy.css)

### NEC PC Engine Duo

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/nec/pc-engine/preview-pce-duo.svg" width="40%">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/nec/pc-engine/preview-pce-duo-xy.svg" width="40%"></p>

Original
- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pce-duo.css)
- [For OBS Studio etc. (with mapping: X to A, A to B)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pce-duo.css&map={"mapping":[{"targetType":"buttons","target":"0","disabled":false,"choiceType":"buttons","choice":"2"},{"targetType":"buttons","target":"1","disabled":false,"choiceType":"buttons","choice":"0"},{"targetType":"buttons","target":"2","disabled":false,"choiceType":"buttons","choice":"3"},{"targetType":"buttons","target":"3","disabled":false,"choiceType":"buttons","choice":"1"}]})
- [For OBS Studio etc. (with mapping: LStick to DPad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pce-duo.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [For OBS Studio etc. (with mapping: LStick to DPad, X to A, A to B)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pce-duo.css&map={"mapping":[{"targetType":"buttons","target":"0","disabled":false,"choiceType":"buttons","choice":"2"},{"targetType":"buttons","target":"1","disabled":false,"choiceType":"buttons","choice":"0"},{"targetType":"buttons","target":"2","disabled":false,"choiceType":"buttons","choice":"3"},{"targetType":"buttons","target":"3","disabled":false,"choiceType":"buttons","choice":"1"},{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/nec/pce-duo.css)

With buttons X and Y
- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pce-duo-xy.css)
- [For OBS Studio etc. (with mapping: LStick to DPad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pce-duo-xy.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/nec/pce-duo-xy.css)

### NEC TurboDuo

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/nec/pc-engine/preview-td.svg" width="40%">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/nec/pc-engine/preview-td-xy.svg" width="40%"></p>

Original
- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/td.css)
- [For OBS Studio etc. (with mapping: X to A, A to B)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/td.css&map={"mapping":[{"targetType":"buttons","target":"0","disabled":false,"choiceType":"buttons","choice":"2"},{"targetType":"buttons","target":"1","disabled":false,"choiceType":"buttons","choice":"0"},{"targetType":"buttons","target":"2","disabled":false,"choiceType":"buttons","choice":"3"},{"targetType":"buttons","target":"3","disabled":false,"choiceType":"buttons","choice":"1"}]})
- [For OBS Studio etc. (with mapping: LStick to DPad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/td.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [For OBS Studio etc. (with mapping: LStick to DPad, X to A, A to B)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/td.css&map={"mapping":[{"targetType":"buttons","target":"0","disabled":false,"choiceType":"buttons","choice":"2"},{"targetType":"buttons","target":"1","disabled":false,"choiceType":"buttons","choice":"0"},{"targetType":"buttons","target":"2","disabled":false,"choiceType":"buttons","choice":"3"},{"targetType":"buttons","target":"3","disabled":false,"choiceType":"buttons","choice":"1"},{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/nec/td.css)

With buttons X and Y
- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/td-xy.css)
- [For OBS Studio etc. (with mapping: LStick to DPad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/td-xy.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/nec/td-xy.css)

### NEC PC Engine PCE-TP2

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/nec/pc-engine/preview-duo-r.svg" width="40%">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/nec/pc-engine/preview-duo-r-xy.svg" width="40%"></p>

Original
- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/duo-r.css)
- [For OBS Studio etc. (with mapping: X to A, A to B)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/duo-r.css&map={"mapping":[{"targetType":"buttons","target":"0","disabled":false,"choiceType":"buttons","choice":"2"},{"targetType":"buttons","target":"1","disabled":false,"choiceType":"buttons","choice":"0"},{"targetType":"buttons","target":"2","disabled":false,"choiceType":"buttons","choice":"3"},{"targetType":"buttons","target":"3","disabled":false,"choiceType":"buttons","choice":"1"}]})
- [For OBS Studio etc. (with mapping: LStick to DPad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/duo-r.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [For OBS Studio etc. (with mapping: LStick to DPad, X to A, A to B)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/duo-r.css&map={"mapping":[{"targetType":"buttons","target":"0","disabled":false,"choiceType":"buttons","choice":"2"},{"targetType":"buttons","target":"1","disabled":false,"choiceType":"buttons","choice":"0"},{"targetType":"buttons","target":"2","disabled":false,"choiceType":"buttons","choice":"3"},{"targetType":"buttons","target":"3","disabled":false,"choiceType":"buttons","choice":"1"},{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/nec/duo-r.css)

With buttons X and Y
- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/duo-r-xy.css)
- [For OBS Studio etc. (with mapping: LStick to DPad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/duo-r-xy.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/nec/duo-r-xy.css)

### NEC PC Engine PCE-TP1 (Arcade Pad 6)

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/nec/pce-tp1/preview.svg" width="40%"></p>

- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pce-tp1.css)
- [For OBS Studio etc. (with mapping: LStick to DPad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pce-tp1.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/nec/pce-tp1.css)

### NEC PC-FX

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/nec/pc-fx/preview-pcfx.svg" width="40%"></p>

- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pc-fx.css)
- [For OBS Studio etc. (with mapping: LStick to DPad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pc-fx.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/nec/pc-fx.css)


## SNK

### Neo-Geo CD

<p><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/snk/neogeo-cd/preview-v1.svg" width="40%"></p>

- [For OBS Studio etc.](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/snk/neogeo-cd-v1.css)
- [For OBS Studio etc. (with mapping: LStick to DPad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/snk/neogeo-cd-v1.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Raw CSS file](https://frolovlife.github.io/gamepadviewer-skins/snk/neogeo-cd-v1.css)
