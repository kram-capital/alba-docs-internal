# Configuration

Internal Ranges Analysis has a plethora of settings enabling you to configure not only the look and feel of the indicator, but also the functionality so that you can tailor your experience to your exact needs. Internal Ranges Analysis aims to be unopinionated about the way that you trade so that it can be moulded around you and the elements of the strategy that you use. Let's start by opening up the configuration options.
## View the settings
Please take a look at the official Tradingview documentation if you are unsure on how to view the configuration settings for the indicators that are applied to your chart and the return to this page for the Internal Ranges Analysis specific configuration options.
[!ref target="blank" text="Official Docs"](https://shorturl.at/isyY6)
# Settings Overview
## Inputs Tab

=== Initialisation
![](/assets/img/alba-docs-internal-1-init.png)

Starting 
:   Set the date the algorithm should begin

===

### Internal Zigzag
=== Click to expand

Internal Zigzag
:   Plot the line of price action

Zigzag attributes
:   In order from left to right
    - Colour of the plotted line
    - Width of the plotted line

===

### Single Candle Order Block

==- Click to expand 

![](/assets/img/alba-docs-internal-2-scob.png)

SCOBs must sweep previous candle high/low
:   Single candle order blocks must sweep the previous candle to become valid

SCOBs must sweep a previous pullback
:   Single candle order blocks must sweep a previous pullback to become valid

Label on SCOB
:   In order from left to right
    - Label colour of bullish SCOB
    - Label colour of bearish SCOB

Colour confirmation candles
:   In order from left to right
    - Candle colour of bullish SCOB
    - Candle colour of bearish SCOB

Alerts when a SCOB is formed
:   Fire an alert when a valid SCOB is printed

!!!
Triggering alerts requires an additional step that will be explained in the alerts section 
!!!

===

### Single Candle Mitigation

==- Click to expand 

![](/assets/img/alba-docs-internal-3-scm.png)

SCMs must sweep previous candle high/low
:   Single candle order mitigations must sweep the previous candle to become valid

SCMs must sweep a previous pullback
:   Single candle order mitigations must sweep a previous pullback to become valid

Label on SCM
:   In order from left to right
    - Label colour of bullish SCM
    - Label colour of bearish SCM

Colour candles
:   In order from left to right
    - Candle colour of bullish SCM
    - Candle colour of bearish SCM

Alerts when a SCM is formed
:   Fire an alert when a valid SCM is printed

!!!
Triggering alerts requires an additional step that will be explained in the alerts section 
!!!

Demand / Supply zone on candle wick
:   Allow wicks to be used as valid demand / Supply zones

Colour Pickers
:   In order from left to right
    - Colour of bullish SCM (Demand)
    - Colour of bearish SCM (Supply)

Filter demand/supply by ATR
:   Set the minimum ATR allowed to confirm wick S&D zones

ATR length
:   Set the ATR length

ATR multiplier
:   Set the ATR multiplier

===
### Show Demand and Supply Zones
=== Click to expand

![](/assets/img/alba-docs-internal-4-d-s.png)

Show demand/supply zones
:   Toggle demand/supply zone visibility

Extend Bars
:   In order from left to right
    - Set the length of the D&S zones
    - Set the length of the D&S zones to be continuous until mitigation

Colour Pickers
:   In order from left to right
    - Colour of demand zones
    - Colour of supply zones

===

## Style Tab
![](/assets/img/alba-docs-style-1.png)
The three setting within the style tab are to globally toggle the visibility of the drawings created by OptiStruct.

Bar Colour
:   Configure the colour for the different candle states

Style settings
:   &nbsp;
    - Display or hide all indicator boxes
    - Display or hide all indicator labels
    - Display or hide all indicator lines


## Visibility Tab
This is outside of the scope of our software but below is a link where you will find the official documentation.
[!ref target="blank" text="Official Docs"](https://shorturl.at/rGSUZ)

<!-- TODO Remove -->
Add a prefix to historical OBs 
:   Specify some text to prepend order block label

Label attributes
:   In order from left to right
    - Size of the text label
    - Border of the rectangle style
    - Width of the rectangle border