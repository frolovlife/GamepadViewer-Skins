# General

These are custom skins of various controllers for [GamepadViewer](https://gamepadviewer.com/). You can use them to display the buttons that are being pressed on your stream as an overlay.

> [!IMPORTANT]
> GamepadViewer works with XInput controllers. Work with DirectInput controllers is not guaranteed.

## How to use with OBS Studio, StreamLabs etc.

1. Choose the controller skin you want to display on your stream below.
2. Copy the link for OBS Studio with or without mapping, as needed.<br>*Some controllers, such as the 8BitDo M30, don't have analog sticks, but their D-pad functions as the left stick. To ensure proper operation with these controllers, use the link with mapping.*
3. Create a Browser source on the scene in OBS Studio.
4. Paste the copied link into the Browser source URL field and click «OK».
> [!NOTE]
> All links for OBS Studio are designed for the first player's controller. To display the second, third, or fourth player's controller, replace `p=1` in the link with `p=2`, `p=3`, or `p=4` respectively.

## How to use with GamepadViewer's URL generator

1. Choose the controller skin you want to display on your stream below.
2. Copy the raw CSS link of these skin.
3. Go to [GamepadViewer URL Generator](https://gamepadviewer.com/#generate).
4. Paste the copied link into the «Custom CSS URL» field.
5. Configure the remaining parameters as desired and copy the generated link.
6. Paste the generated link into the Browser source address bar in OBS Studio and click «OK».

# Controller skins

- [8BitDo](#8bitdo)
  - [8BitDo M30 (black)](#8bitdo-m30-black)
  - [8BitDo M30 (white)](#8bitdo-m30-white)
- [**Sega**](#sega)
  - [Sega Saturn (model 2 black)](#sega-saturn-model-2-black)
  - [Sega Saturn (model 2 white)](#sega-saturn-model-2-white)
- [**Dendy**](#dendy)
  - [Dendy Classic](#dendy-classic)
  - [Dendy Junior (var. 1)](#dendy-junior-var-1)
  - [Dendy Junior (var. 2)](#dendy-junior-var-2)
  - [Famiclone](#famiclone)
- [**NEC**](#nec)
  - [NEC PC Engine (var. 1)](#nec-pc-engine-var-1)
  - [NEC PC Engine (var. 2)](#nec-pc-engine-var-2)
  - [NEC PC Engine CoreGrafx](#nec-pc-engine-coregrafx)
  - [NEC PC Engine CoreGrafx II](#nec-pc-engine-coregrafx-ii)
  - [NEC TurboGrafx 16](#nec-turbografx-16)
  - [NEC TurboDuo](#nec-turboduo)
  - [NEC PC-FX](#nec-pc-fx)

## 8BitDo

### 8BitDo M30 (black)

<p align="left"><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/preview/8bitdo-m30-black.svg" width="50%"></p>

- [Link for OBS Studio etc. (with mapping: LStick to DPad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/8bitdo/m30-black.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Link for OBS Studio etc. (without mapping)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/8bitdo/m30-black.css)
- [Link to raw CSS file for URL generator](https://frolovlife.github.io/gamepadviewer-skins/8bitdo/m30-black.css)

### 8BitDo M30 (white)

<p align="left"><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/preview/8bitdo-m30-white.svg" width="50%"></p>

- [Link for OBS Studio etc. (with mapping: LStick to DPad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/8bitdo/m30-white.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Link for OBS Studio etc. (without mapping)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/8bitdo/m30-white.css)
- [Link to raw CSS file for URL generator](https://frolovlife.github.io/gamepadviewer-skins/8bitdo/m30-white.css)

## Sega

### Sega Saturn (model 2 black)

<p align="left"><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/preview/sega-saturn-m2-black.svg" width="50%"></p>

- [Link for OBS Studio etc. (with mapping: LStick to DPad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/sega/saturn-model2-black.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Link for OBS Studio etc. (without mapping)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/sega/saturn-model2-black.css)
- [Link to raw CSS file for URL generator](https://frolovlife.github.io/gamepadviewer-skins/sega/saturn-model2-black.css)

### Sega Saturn (model 2 white)

<p align="left"><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/preview/sega-saturn-m2-white.svg" width="50%"></p>

- [Link for OBS Studio etc. (with mapping: LStick to DPad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/sega/saturn-model2-white.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Link for OBS Studio etc. (without mapping)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/sega/saturn-model2-white.css)
- [Link to raw CSS file for URL generator](https://frolovlife.github.io/gamepadviewer-skins/sega/saturn-model2-white.css)


## Dendy

### Dendy Classic

<p align="left"><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/preview/dendy-classic.svg" width="50%"></p>

- [Link for OBS Studio etc. (with mapping: LStick to DPad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/dendy/classic.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Link for OBS Studio etc. (without mapping)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/dendy/classic.css)
- [Link to raw CSS file for URL generator](https://frolovlife.github.io/gamepadviewer-skins/dendy/classic.css)

### Dendy Junior (var. 1)

<p align="left"><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/preview/dendy-junior-v1.svg" width="50%"></p>

- [Link for OBS Studio etc. (with mapping: LStick to DPad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/dendy/junior-v1.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Link for OBS Studio etc. (without mapping)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/dendy/junior-v1.css)
- [Link to raw CSS file for URL generator](https://frolovlife.github.io/gamepadviewer-skins/dendy/junior-v1.css)

### Dendy Junior (var. 2)

<p align="left"><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/preview/dendy-junior-v2.svg" width="50%"></p>

- [Link for OBS Studio etc. (with mapping: LStick to DPad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/dendy/junior-v2.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Link for OBS Studio etc. (without mapping)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/dendy/junior-v2.css)
- [Link to raw CSS file for URL generator](https://frolovlife.github.io/gamepadviewer-skins/dendy/junior-v2.css)

### Famiclone

<p align="left"><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/preview/famiclone.svg" width="50%"></p>

- [Link for OBS Studio etc. (with mapping: LStick to DPad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/dendy/famiclone.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Link for OBS Studio etc. (without mapping)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/dendy/famiclone.css)
- [Link to raw CSS file for URL generator](https://frolovlife.github.io/gamepadviewer-skins/dendy/famiclone.css)


## NEC

### NEC PC Engine (var. 1)

<p align="left"><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/preview/nec-pce-1.svg" width="50%"></p>

- [Link for OBS Studio etc. (with mapping: LStick to DPad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pce-v1.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Link for OBS Studio etc. (without mapping)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pce-v1.css)
- [Link to raw CSS file for URL generator](https://frolovlife.github.io/gamepadviewer-skins/nec/pce-v1.css)

### NEC PC Engine (var. 2)

<p align="left"><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/preview/nec-pce-2.svg" width="50%"></p>

- [Link for OBS Studio etc. (with mapping: LStick to DPad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pce-v2.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Link for OBS Studio etc. (without mapping)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pce-v2.css)
- [Link to raw CSS file for URL generator](https://frolovlife.github.io/gamepadviewer-skins/nec/pce-v2.css)

### NEC PC Engine CoreGrafx

<p align="left"><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/preview/nec-pce-cg.svg" width="50%"></p>

- [Link for OBS Studio etc. (with mapping: LStick to DPad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pce-cg.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Link for OBS Studio etc. (without mapping)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pce-cg.css)
- [Link to raw CSS file for URL generator](https://frolovlife.github.io/gamepadviewer-skins/nec/pce-cg.css)

### NEC PC Engine CoreGrafx II

<p align="left"><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/preview/nec-pce-cg2.svg" width="50%"></p>

- [Link for OBS Studio etc. (with mapping: LStick to DPad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pce-cg2.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Link for OBS Studio etc. (without mapping)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pce-cg2.css)
- [Link to raw CSS file for URL generator](https://frolovlife.github.io/gamepadviewer-skins/nec/pce-cg2.css)

### NEC TurboGrafx 16

<p align="left"><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/preview/nec-tg16.svg" width="50%"></p>

- [Link for OBS Studio etc. (with mapping: LStick to DPad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/tg16.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Link for OBS Studio etc. (without mapping)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/tg16.css)
- [Link to raw CSS file for URL generator](https://frolovlife.github.io/gamepadviewer-skins/nec/tg16.css)

### NEC TurboDuo

<p align="left"><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/preview/nec-td.svg" width="50%"></p>

- [Link for OBS Studio etc. (with mapping: LStick to DPad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/td.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Link for OBS Studio etc. (without mapping)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/td.css)
- [Link to raw CSS file for URL generator](https://frolovlife.github.io/gamepadviewer-skins/nec/td.css)

### NEC PC-FX

<p align="left"><img src="https://raw.githubusercontent.com/frolovlife/gamepadviewer-skins/refs/heads/main/preview/nec-pcfx.svg" width="50%"></p>

- [Link for OBS Studio etc. (with mapping: LStick to DPad)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pc-fx.css&map={"mapping":[{"targetType":"buttons","target":"14","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"15","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"0"},{"targetType":"buttons","target":"12","disabled":false,"choiceOperand":"-","choiceType":"axes","choice":"1"},{"targetType":"buttons","target":"13","disabled":false,"choiceOperand":"%2B","choiceType":"axes","choice":"1"}]})
- [Link for OBS Studio etc. (without mapping)](https://gamepadviewer.com/?p=1&css=https://frolovlife.github.io/gamepadviewer-skins/nec/pc-fx.css)
- [Link to raw CSS file for URL generator](https://frolovlife.github.io/gamepadviewer-skins/nec/pc-fx.css)
