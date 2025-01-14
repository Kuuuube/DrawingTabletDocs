# 7P notes: Wacom Pro Pen 3

## Overview

The tablet comes with the Wacom Pro Pen 3 (ACP50000DZ).&#x20;

### Pressure&#x20;

Before you continue, you should read this document because it clarifies what is meant by terms such as pressure, pressure, range, etc. [**Pen pressure**](../../guides/core-features/pen-pressure.md)  &#x20;

#### Pressure levels

* Pro Pen 3 supports 8192 pressure levels.
* Nothing special here. All modern tablets/pens say they support this number of pressure levels.

#### Pressure response for drawing

* Pressure response is how the pressure translates to drawing strokes in creative application
* Pressure response is EXCELLENT across the following scenarios:
  * Small pressure produces for light strokes&#x20;
  * It is easy to create many small slight strokes quickly (example: hatch lines)&#x20;
  * Varying pressure as you draw changes stroke width very smoothly&#x20;
  * It is easy to maintain even pressure and line width.
  * Nice tapering at beginning and end of strokes
    * How the beginning and ends of strokes look is highly depending on the app and the brush settings.
      * For example, sudden flicks to end a line in Clip Studio Paint look a little different than the same motion in Photoshop. But this seems normal.
    * For the Pro Pen 3 with the Wacom Cintiq Pro 27 the begging and ends of strokes felt as good as they always have.&#x20;

#### Pressure range&#x20;

* Background: Read this document to understand pressure range before you continue: [**Pen pressure**](../../guides/core-features/pen-pressure.md)
* The Pro Pen 3 has the typical wide pressure range from Wacom and is excellent.
  * Unfortunately there are no clear published specs from Wacom on other manufacturers on these pressure range values. So we have to evaluate it subjectively for now.
* Comparing pressure range to competitors (again this is subjective)
  * For the Huion PW517 pen I have to push a certain amount to get to max pressure
  * For the Pro Pen 3, I have to push I guess twice as hard to get to max pressure. In fact I have to push so hard that I'm almost worried I'm pushing too much. Again this is good.

#### Initial activation force

* The Pro Pen 3 has a typical low IAF for Wacom Pro pens - EXCELLENT.&#x20;

#### Comparing Initial Activation Force

* Wacom does not publish IAF numbers
* I don't know of any clear way to measure it.
* One benchmark used to evaluate IAF is whether the weight of the pen itself will trigger a pressure reading.
* I tried using this benchmark to get a feel for the IAF the Pro Pen 3 versus the Huion PW517
  * I dangled the pen on the surface from a piece of tape. This was to avoid my hand adding pressure.
  * I looked at the impact on the "pressure test region" of their respective driver apps
  * Result for Wacom Pro Pen 3: The weight of the Wacom pen itself consistently draws a stroke
  * Result for Huion PW517: The weight Huion pen itself the will inconsistently draw a stroke. Sometimes it draws. Sometimes it doesn't.

##

## Pro Pen 3

This is a very normal EMR pen that lives up to previous models in terms of quality. And may be slightly better than the Wacom Pro Pen 2.

### Customizability

* Unlike previous Wacom pens, the Pro Pen 3 is very modular and customizable
* Grip options
  * No grip
  * flared grip - gives it same basic shape as the pro pen 2
  * non-flared grip

### My pen configuration



<figure><img src="../../.gitbook/assets/pen disassembled-numbered.jpg" alt=""><figcaption><p>Components used in my pen configuration</p></figcaption></figure>

* 1 pen body with tip - the front
* 2 pen body rear
* 3 button strip with three buttons
* 4 metal weight. I placed the heavier end inside part 1
* 5 flared grip

When my pen is fully assembled it looks like this:

<figure><img src="../../.gitbook/assets/pen assembled.jpg" alt=""><figcaption></figcaption></figure>

### 3 button strip

* I like buttons on my pens so I installed the 3 button strip
* Wacom expects you'll map the topmost button to erase
* Personally I have difficult distinguishing three buttons from two and so I often press the third button when I meant to press the second.
* So, in Wacom driver, I simply disable the third button.
* I was afraid the button strip would easily come out of the pen. It is securely in there and hasn't popped out even when I have dropped the pen to the floor accidentally.

### The feeling of drawing with the pen

* NOTE: This relates to the physical feeling of holding, moving, pressing the pen against the glass. This has nothing to do with how pressure works or how it works with apps.
* SUMMARY: The feeling is EXCELLENT
* I think it is an improvement over the Wacom Pro Pen&#x20;
* However I think there is a lots of subjectivity to this. For example, I accidentally picked up the Pro Pen 2 and started drawing with it. And I thought I was using the Pro Pen 3 and remarked how good it felt. Only when I looked at the pen did I realize I was using the old pen.
* To me the differences between the Pro Pen 3 and the Pro Pen 2 are slight and subtle.&#x20;
* Other people feel that the difference is more obvious.

### Solidity

* Because the pen is very modular, I was afraid that it would feel unstable.
* Actually, it's incredibly solid feeling.

### Grip feeling

* The grip is made of two pieces. Inside it a shell of plastic which is surrounded by the rubber grip material.
* Overall it the grip is much more firm than the grip of the pro pen 2&#x20;
* The grip doesn't feel rubbery
* Very difficult to bend when the Grip is installed.
* **The grip can be damaged with sufficient force.** If you squeeze the grip when it is not on the pen, you will initially find it hard to bend however much if the rigidity is due to the plastic shell inside. If you keep exerting pressure you will break the plastic and it won't fit as well when you place it on the pen.

### Compatibility with older Wacom tablets

* Currently, the Pro Pen 3 can only be used with the Cintiq Pro 27.
* Possibility of future compatibility
  * Wacom mentioned on twitter and during their demo event they would release an update that would make the Pro Pen 3 work on select older tablets.
    * Twitter post: [https://twitter.com/wacom/status/1575250917687169024?s=20\&t=87CfqjwwpUs92waOpEkcvA](https://twitter.com/wacom/status/1575250917687169024?s=20\&t=87CfqjwwpUs92waOpEkcvA)\
      \
      ![](<../../.gitbook/assets/image (286).png>)
  * Wacom has not published that update
  * Wacom has not identified which older tablets will be updated to be compatible with the Pro Pen 3
* What happens when you try using the Pro Pen 3 with an older tablet
  * With Wacom's latest drivers
    * Nothing happens
    * The drivers don't reveal that the pen even exists.
  * With OpenTabletDriver
    * The tablet does sense the pens position - but the cursor is "bouncing around" many times a second- it is unusable for drawing

### Pressure features

* Pressure levels: 8192
* Nothing special here or different here. Every recently produced pen says it supports this many levels.
* I continue to maintain that 2048 levels is all you need for creative applications. Some say even fewer pressure levels are needed.
* Learn more: [**Pen pressure**](../../guides/core-features/pen-pressure.md)

### Barrel rotation

* The Pro Pen 3 does not support barrel rotation.
* This was very disappointing. Even though
* Learn more: [**Pen Barrel rotation**](../../guides/core-features/pen-barrel-rotation.md)  &#x20;

### Eraser

* The pen does not include an eraser at the other end. Instead, use one of the 3 buttons as the eraser.

##

