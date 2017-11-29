# CVplugins
JS plugins for Reaper to generate CV (control voltage) from DC-coupled sound card to your modular synth

## WARNING
These plugins will create DC voltage through your sound card outputs. They are intented for DC-coupled sound card and they are intended for CV control of modular synthesis. THEY WILL NOT PRODUCE SOUND PER SE AND THEY SHOULD NOT BE ROUTED TO SPEAKERS OR AMPLIFIERS. I am not responsible of any damage related to the use of these plugins. If you don't know about CV, this is a sign that you should not use these plugins. 

## Getting Started
Download these files and place them in your Reaper JS plugin folder. On Mac OS, you find the plugin folder in Application Support/Reaper/Effects. You can place them in a folder. 

### Prerequisites
These plugins are for REAPER, an affordable and powerful DAW (Digital Audio Workstation): https://www.reaper.fm/. You will need a DC-coupled sound card to create the actual CV for your modular synths. Exemple of DC-coupled sound cards are numerous and can be found on www.modulargrid.net in Utility, or controller category. Exemple include Expert Sleeper ES-8: https://www.modulargrid.net/e/expert-sleepers-es-8. You will also need some sort of modular synthesizer. 

The plugins are written in JS (Jesusonic). JS is a scripting language evaluated on the fly by REAPER.

## Usage
Load one of the plugin in your FX track. Automate them to create CV. Few of the plugins are creating either unipolar or bipolar CV in 1-chn or 8-chn version. This is for simple automation. Other plugins are converting midi note to gate, and CV (velocity + note). 

## Future development
1. Midi note to simple CV Decay envelop for and percussion.
2. Midi note with full ADSR envelop.
3. CV processing utilities: slew rate limiter, invert, scale, clip, split, etc.

## Authors
Philippe-Aubert Gauthier, 2017, philippe_aubert_gauthier@hotmail.com, www.st-pierre-gauthier.com

## License
Use them, mod them, harder, better, faster, stronger ...

