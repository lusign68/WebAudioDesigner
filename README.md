WebAudioDesigner
================

WebAudioAPI GUI design tool

![](images/webaudiodesigner.png)

Available at :
[https://g200kg.github.io/WebAudioDesigner](https://g200kg.github.io/WebAudioDesigner)

### Sample patch

[Delay](http://g200kg.github.io/WebAudioDesigner/?p=%5B%7B%22type%22:%22destination%22,%22name%22:%22destination%22,%22x%22:694,%22y%22:116,%22params%22:%5B%5D,%22connect%22:%5B%5D%7D,%7B%22type%22:%22gain%22,%22name%22:%22gain1%22,%22x%22:572,%22y%22:199,%22params%22:%5B%7B%22name%22:%22gain%22,%22type%22:%22a%22,%22value%22:%221%22%7D%5D,%22connect%22:%5B%7B%22t%22:%22destination%22,%22o%22:0,%22i%22:0%7D%5D%7D,%7B%22type%22:%22bufsrc%22,%22name%22:%22bufsrc1%22,%22x%22:65,%22y%22:172,%22params%22:%5B%7B%22name%22:%22playbackRate%22,%22type%22:%22a%22,%22value%22:%221%22%7D,%7B%22name%22:%22loop%22,%22type%22:%22b%22,%22value%22:true%7D,%7B%22name%22:%22loopStart%22,%22type%22:%22n%22,%22value%22:0%7D,%7B%22name%22:%22loopEnd%22,%22type%22:%22n%22,%22value%22:0%7D,%7B%22name%22:%22buffer%22,%22type%22:%22ob%22,%22value%22:%22loop.wav%22%7D%5D,%22connect%22:%5B%7B%22t%22:%22delay1%22,%22o%22:0,%22i%22:0%7D,%7B%22t%22:%22gain1%22,%22o%22:0,%22i%22:0%7D%5D%7D,%7B%22type%22:%22delay%22,%22name%22:%22delay1%22,%22x%22:314,%22y%22:311,%22params%22:%5B%7B%22name%22:%22delayTime%22,%22type%22:%22a%22,%22value%22:%22.25%22%7D%5D,%22connect%22:%5B%7B%22t%22:%22gain2%22,%22o%22:0,%22i%22:0%7D,%7B%22t%22:%22gain3%22,%22o%22:0,%22i%22:0%7D%5D%7D,%7B%22type%22:%22gain%22,%22name%22:%22gain2%22,%22x%22:488,%22y%22:384,%22params%22:%5B%7B%22name%22:%22gain%22,%22type%22:%22a%22,%22value%22:%220.5%22%7D%5D,%22connect%22:%5B%7B%22t%22:%22gain1%22,%22o%22:0,%22i%22:0%7D%5D%7D,%7B%22type%22:%22gain%22,%22name%22:%22gain3%22,%22x%22:299,%22y%22:463,%22params%22:%5B%7B%22name%22:%22gain%22,%22type%22:%22a%22,%22value%22:%220.5%22%7D%5D,%22connect%22:%5B%7B%22t%22:%22delay1%22,%22o%22:0,%22i%22:0%7D%5D%7D%5D)

[Chorus](http://g200kg.github.io/WebAudioDesigner/?p=%5B%7B%22type%22:%22destination%22,%22name%22:%22destination%22,%22x%22:694,%22y%22:116,%22params%22:%5B%5D,%22connect%22:%5B%5D%7D,%7B%22type%22:%22gain%22,%22name%22:%22gain1%22,%22x%22:509,%22y%22:140,%22params%22:%5B%7B%22name%22:%22gain%22,%22type%22:%22a%22,%22value%22:%221%22%7D%5D,%22connect%22:%5B%7B%22t%22:%22destination%22,%22o%22:0,%22i%22:0%7D%5D%7D,%7B%22type%22:%22bufsrc%22,%22name%22:%22bufsrc1%22,%22x%22:65,%22y%22:172,%22params%22:%5B%7B%22name%22:%22playbackRate%22,%22type%22:%22a%22,%22value%22:%221%22%7D,%7B%22name%22:%22loop%22,%22type%22:%22b%22,%22value%22:true%7D,%7B%22name%22:%22loopStart%22,%22type%22:%22n%22,%22value%22:0%7D,%7B%22name%22:%22loopEnd%22,%22type%22:%22n%22,%22value%22:0%7D,%7B%22name%22:%22buffer%22,%22type%22:%22ob%22,%22value%22:%22loop.wav%22%7D%5D,%22connect%22:%5B%7B%22t%22:%22delay1%22,%22o%22:0,%22i%22:0%7D,%7B%22t%22:%22gain1%22,%22o%22:0,%22i%22:0%7D%5D%7D,%7B%22type%22:%22delay%22,%22name%22:%22delay1%22,%22x%22:365,%22y%22:247,%22params%22:%5B%7B%22name%22:%22delayTime%22,%22type%22:%22a%22,%22value%22:%220.02%22%7D%5D,%22connect%22:%5B%7B%22t%22:%22gain1%22,%22o%22:0,%22i%22:0%7D%5D%7D,%7B%22type%22:%22gain%22,%22name%22:%22gain3%22,%22x%22:270,%22y%22:412,%22params%22:%5B%7B%22name%22:%22gain%22,%22type%22:%22a%22,%22value%22:%220.002%22%7D%5D,%22connect%22:%5B%7B%22t%22:%22delay1.delayTime%22,%22o%22:0%7D%5D%7D,%7B%22type%22:%22osc%22,%22name%22:%22osc1%22,%22x%22:99,%22y%22:345,%22params%22:%5B%7B%22name%22:%22type%22,%22type%22:%22s%22,%22value%22:%22sine%22%7D,%7B%22name%22:%22frequency%22,%22type%22:%22a%22,%22value%22:%221.5%22%7D,%7B%22name%22:%22detune%22,%22type%22:%22a%22,%22value%22:%220%22%7D%5D,%22connect%22:%5B%7B%22t%22:%22gain3%22,%22o%22:0,%22i%22:0%7D%5D%7D%5D)

[Phaser](http://g200kg.github.io/WebAudioDesigner/?p=%5B%7B%22type%22:%22destination%22,%22name%22:%22destination%22,%22x%22:962,%22y%22:139,%22params%22:%5B%5D,%22connect%22:%5B%5D%7D,%7B%22type%22:%22gain%22,%22name%22:%22gain1%22,%22x%22:825,%22y%22:101,%22params%22:%5B%7B%22name%22:%22gain%22,%22type%22:%22a%22,%22value%22:%221%22%7D%5D,%22connect%22:%5B%7B%22t%22:%22destination%22,%22o%22:0,%22i%22:0%7D%5D%7D,%7B%22type%22:%22bufsrc%22,%22name%22:%22bufsrc1%22,%22x%22:68,%22y%22:97,%22params%22:%5B%7B%22name%22:%22playbackRate%22,%22type%22:%22a%22,%22value%22:%221%22%7D,%7B%22name%22:%22loop%22,%22type%22:%22b%22,%22value%22:true%7D,%7B%22name%22:%22loopStart%22,%22type%22:%22n%22,%22value%22:0%7D,%7B%22name%22:%22loopEnd%22,%22type%22:%22n%22,%22value%22:0%7D,%7B%22name%22:%22buffer%22,%22type%22:%22ob%22,%22value%22:%22loop.wav%22%7D%5D,%22connect%22:%5B%7B%22t%22:%22filt1%22,%22o%22:0,%22i%22:0%7D,%7B%22t%22:%22gain1%22,%22o%22:0,%22i%22:0%7D%5D%7D,%7B%22type%22:%22osc%22,%22name%22:%22osc1%22,%22x%22:52,%22y%22:435,%22params%22:%5B%7B%22name%22:%22type%22,%22type%22:%22s%22,%22value%22:%22sine%22%7D,%7B%22name%22:%22frequency%22,%22type%22:%22a%22,%22value%22:%223%22%7D,%7B%22name%22:%22detune%22,%22type%22:%22a%22,%22value%22:%220%22%7D%5D,%22connect%22:%5B%7B%22t%22:%22gain2%22,%22o%22:0,%22i%22:0%7D%5D%7D,%7B%22type%22:%22filt%22,%22name%22:%22filt1%22,%22x%22:266,%22y%22:285,%22params%22:%5B%7B%22name%22:%22type%22,%22type%22:%22s%22,%22value%22:%22allpass%22%7D,%7B%22name%22:%22frequency%22,%22type%22:%22a%22,%22value%22:%221000%22%7D,%7B%22name%22:%22detune%22,%22type%22:%22a%22,%22value%22:%220%22%7D,%7B%22name%22:%22Q%22,%22type%22:%22a%22,%22value%22:%221%22%7D,%7B%22name%22:%22gain%22,%22type%22:%22a%22,%22value%22:%220%22%7D%5D,%22connect%22:%5B%7B%22t%22:%22filt2%22,%22o%22:0,%22i%22:0%7D%5D%7D,%7B%22type%22:%22filt%22,%22name%22:%22filt2%22,%22x%22:426,%22y%22:263,%22params%22:%5B%7B%22name%22:%22type%22,%22type%22:%22s%22,%22value%22:%22allpass%22%7D,%7B%22name%22:%22frequency%22,%22type%22:%22a%22,%22value%22:%221000%22%7D,%7B%22name%22:%22detune%22,%22type%22:%22a%22,%22value%22:%220%22%7D,%7B%22name%22:%22Q%22,%22type%22:%22a%22,%22value%22:%221%22%7D,%7B%22name%22:%22gain%22,%22type%22:%22a%22,%22value%22:%220%22%7D%5D,%22connect%22:%5B%7B%22t%22:%22filt3%22,%22o%22:0,%22i%22:0%7D%5D%7D,%7B%22type%22:%22gain%22,%22name%22:%22gain2%22,%22x%22:263,%22y%22:561,%22params%22:%5B%7B%22name%22:%22gain%22,%22type%22:%22a%22,%22value%22:%22500%22%7D%5D,%22connect%22:%5B%7B%22t%22:%22filt1.frequency%22,%22o%22:0%7D,%7B%22t%22:%22filt2.frequency%22,%22o%22:0%7D,%7B%22t%22:%22filt3.frequency%22,%22o%22:0%7D,%7B%22t%22:%22filt4.frequency%22,%22o%22:0%7D%5D%7D,%7B%22type%22:%22filt%22,%22name%22:%22filt3%22,%22x%22:581,%22y%22:237,%22params%22:%5B%7B%22name%22:%22type%22,%22type%22:%22s%22,%22value%22:%22allpass%22%7D,%7B%22name%22:%22frequency%22,%22type%22:%22a%22,%22value%22:%221000%22%7D,%7B%22name%22:%22detune%22,%22type%22:%22a%22,%22value%22:%220%22%7D,%7B%22name%22:%22Q%22,%22type%22:%22a%22,%22value%22:%221%22%7D,%7B%22name%22:%22gain%22,%22type%22:%22a%22,%22value%22:%220%22%7D%5D,%22connect%22:%5B%7B%22t%22:%22filt4%22,%22o%22:0,%22i%22:0%7D%5D%7D,%7B%22type%22:%22filt%22,%22name%22:%22filt4%22,%22x%22:735,%22y%22:221,%22params%22:%5B%7B%22name%22:%22type%22,%22type%22:%22s%22,%22value%22:%22allpass%22%7D,%7B%22name%22:%22frequency%22,%22type%22:%22a%22,%22value%22:%221000%22%7D,%7B%22name%22:%22detune%22,%22type%22:%22a%22,%22value%22:%220%22%7D,%7B%22name%22:%22Q%22,%22type%22:%22a%22,%22value%22:%221%22%7D,%7B%22name%22:%22gain%22,%22type%22:%22a%22,%22value%22:%220%22%7D%5D,%22connect%22:%5B%7B%22t%22:%22gain1%22,%22o%22:0,%22i%22:0%7D%5D%7D%5D)

[FSU](http://g200kg.github.io/WebAudioDesigner/?p=%5B%7B%22type%22:%22destination%22,%22name%22:%22destination%22,%22x%22:568,%22y%22:205,%22params%22:%5B%5D,%22connect%22:%5B%5D%7D,%7B%22type%22:%22bufsrc%22,%22name%22:%22bufsrc1%22,%22x%22:85,%22y%22:178,%22params%22:%5B%7B%22name%22:%22playbackRate%22,%22type%22:%22a%22,%22value%22:%221%22%7D,%7B%22name%22:%22loop%22,%22type%22:%22b%22,%22value%22:true%7D,%7B%22name%22:%22loopStart%22,%22type%22:%22n%22,%22value%22:0%7D,%7B%22name%22:%22loopEnd%22,%22type%22:%22n%22,%22value%22:0%7D,%7B%22name%22:%22buffer%22,%22type%22:%22ob%22,%22value%22:%22loop.wav%22%7D%5D,%22connect%22:%5B%7B%22t%22:%22delay1%22,%22o%22:0,%22i%22:0%7D%5D%7D,%7B%22type%22:%22delay%22,%22name%22:%22delay1%22,%22x%22:396,%22y%22:154,%22params%22:%5B%7B%22name%22:%22delayTime%22,%22type%22:%22a%22,%22value%22:%220%22%7D%5D,%22connect%22:%5B%7B%22t%22:%22destination%22,%22o%22:0,%22i%22:0%7D%5D%7D,%7B%22type%22:%22osc%22,%22name%22:%22osc1%22,%22x%22:81,%22y%22:392,%22params%22:%5B%7B%22name%22:%22type%22,%22type%22:%22s%22,%22value%22:%22sawtooth%22%7D,%7B%22name%22:%22frequency%22,%22type%22:%22a%22,%22value%22:%220.5%22%7D,%7B%22name%22:%22detune%22,%22type%22:%22a%22,%22value%22:%220%22%7D%5D,%22connect%22:%5B%7B%22t%22:%22shaper1%22,%22o%22:0,%22i%22:0%7D%5D%7D,%7B%22type%22:%22shaper%22,%22name%22:%22shaper1%22,%22x%22:276,%22y%22:347,%22params%22:%5B%7B%22name%22:%22oversample%22,%22type%22:%22s%22,%22value%22:%22none%22%7D,%7B%22name%22:%22curve%22,%22type%22:%22tc%22,%22value%22:%22new%20Float32Array%28%5B%5Cn%5Cn0,%5Cn0,%5Cn0.1,%5Cn0.1,%5Cn0,%5Cn0,%5Cn0.3,%5Cn0.3,%5Cn0.2,%5Cn0.2,%5Cn0.4,%5Cn0.4,%5Cn0.2,%5Cn0.2,%5Cn%5Cn%5D%29%22%7D%5D,%22connect%22:%5B%7B%22t%22:%22delay1.delayTime%22,%22o%22:0%7D%5D%7D%5D)

[Wah](http://g200kg.github.io/WebAudioDesigner/?p=%5B%7B%22type%22:%22destination%22,%22name%22:%22destination%22,%22x%22:584,%22y%22:157,%22params%22:%5B%5D,%22connect%22:%5B%5D%7D,%7B%22type%22:%22bufsrc%22,%22name%22:%22bufsrc1%22,%22x%22:91,%22y%22:142,%22params%22:%5B%7B%22name%22:%22playbackRate%22,%22type%22:%22a%22,%22value%22:%221%22%7D,%7B%22name%22:%22loop%22,%22type%22:%22b%22,%22value%22:true%7D,%7B%22name%22:%22loopStart%22,%22type%22:%22n%22,%22value%22:0%7D,%7B%22name%22:%22loopEnd%22,%22type%22:%22n%22,%22value%22:0%7D,%7B%22name%22:%22buffer%22,%22type%22:%22ob%22,%22value%22:%22loop.wav%22%7D%5D,%22connect%22:%5B%7B%22t%22:%22filt1%22,%22o%22:0,%22i%22:0%7D%5D%7D,%7B%22type%22:%22filt%22,%22name%22:%22filt1%22,%22x%22:357,%22y%22:208,%22params%22:%5B%7B%22name%22:%22type%22,%22type%22:%22s%22,%22value%22:%22lowpass%22%7D,%7B%22name%22:%22frequency%22,%22type%22:%22a%22,%22value%22:%221000%22%7D,%7B%22name%22:%22detune%22,%22type%22:%22a%22,%22value%22:%220%22%7D,%7B%22name%22:%22Q%22,%22type%22:%22a%22,%22value%22:%2220%22%7D,%7B%22name%22:%22gain%22,%22type%22:%22a%22,%22value%22:%220%22%7D%5D,%22connect%22:%5B%7B%22t%22:%22comp1%22,%22o%22:0,%22i%22:0%7D%5D%7D,%7B%22type%22:%22osc%22,%22name%22:%22osc1%22,%22x%22:52,%22y%22:369,%22params%22:%5B%7B%22name%22:%22type%22,%22type%22:%22s%22,%22value%22:%22sine%22%7D,%7B%22name%22:%22frequency%22,%22type%22:%22a%22,%22value%22:%221.5%22%7D,%7B%22name%22:%22detune%22,%22type%22:%22a%22,%22value%22:%220%22%7D%5D,%22connect%22:%5B%7B%22t%22:%22gain1%22,%22o%22:0,%22i%22:0%7D%5D%7D,%7B%22type%22:%22gain%22,%22name%22:%22gain1%22,%22x%22:216,%22y%22:390,%22params%22:%5B%7B%22name%22:%22gain%22,%22type%22:%22a%22,%22value%22:%22500%22%7D%5D,%22connect%22:%5B%7B%22t%22:%22filt1.frequency%22,%22o%22:0%7D%5D%7D,%7B%22type%22:%22comp%22,%22name%22:%22comp1%22,%22x%22:504,%22y%22:279,%22params%22:%5B%7B%22name%22:%22threshold%22,%22type%22:%22a%22,%22value%22:%22-24%22%7D,%7B%22name%22:%22knee%22,%22type%22:%22a%22,%22value%22:%2230%22%7D,%7B%22name%22:%22ratio%22,%22type%22:%22a%22,%22value%22:%2212%22%7D,%7B%22name%22:%22attack%22,%22type%22:%22a%22,%22value%22:%220.003%22%7D,%7B%22name%22:%22release%22,%22type%22:%22a%22,%22value%22:%220.25%22%7D%5D,%22connect%22:%5B%7B%22t%22:%22destination%22,%22o%22:0,%22i%22:0%7D%5D%7D%5D)
