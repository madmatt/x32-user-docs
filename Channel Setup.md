# Channel Setup
1.  Plug in your mic/instrument into the X32 Rack, or the S16 digital snake.

2.  By default, inputs #1 - #16 are on the back of the X32 Rack, and #17 - #32 are on the S16 Digital snake.

3.  Find the appropriate channel # in X32, and click on the 'Ch##' button (just above the fader).

4.  If this doesn't change you to the 'Home' section, then click the 'Home' button (see instruction #1 in the screenshot below):
    ![Home screen][1]

5.  Set the channel gain (if needed) - see #2 in the above screenshot.

6.  If needed, click '48V' to turn phantom power on for that channel - see #3 in the above screenshot.

7.  Quickly adjust the EQ settings, or quickly enable/disable the EQ by clicking the 'EQ' button - see #4 in the above screenshot.

8.  Quickly enable/disable the Compressor by clicking the 'Comp' button - see #5 in the above screenshot.

9.  Quickly adjust the level of signal being sent to mix buses (in this case, Bus 1 is our left foldback speaker, and Bus 2 is our right foldback speaker) - see #6 in the above screenshot.

# Mute Groups
You can mute individual channels by clicking the appropriate 'Mute' button for the channel. However, often you'll want to mute a group of channels at the same time (e.g. the band at the end of a song set). That's where mute groups come in handy.

It's important to note that the mute group buttons that you use to turn on/off mute for a channel range are themselves their own 'Mute' button. In other words, they have their own toggle state. For example, if you added Inputs #1 - #5 to Mute Group #1, and channels #1 and #2 were already muted, when you hit the 'Mute Group 1' button, all 5 channels will be muted (so the status of channels #1 and #2 doesn't change). When you unmute Mute Group 1, then all channels become un-muted, regardless of their state before they were muted. In the same way, if you hit 'Mute Group 1' to mute all 5 channels, then un-muted a couple of channels, it doesn't affect the Mute Group - but those channels will become unmuted. So muting a channel is still a single toggle at the channel level, but Mute Groups help you quickly enable or disable that button for all channels in a group - and ensure they are all set to the same state when you toggle the mute group.

1.  First, select the channel you want to add to the mute group, navigate to the 'Home' section, and then select the Mute Group you want to add the channel to (e.g. Mute Group 1 in this case). See screenshot below.
    ![Mute Group setup][3]
    
2.  Then, once you have your mute groups setup, you can quickly mute or unmute an entire group by clicking on the appropriate Mute Group button in the far-right of the interface, just under the L/R output meters. Here is what the interface looks like when Mute Group #1 has been enabled, and I've added inputs #1 - #5 to the mute group:
    ![Mute Group enabled][4]

# Compressor Setup for a channel
The compressor is a setting that can be used for each individual channel often used to stop hard sounds (e.g the letters 'B', 'P' etc.) from popping in the mix.

1.  Select the channel, navigate to the 'Home' screen, and click the 'Dyn' tab.
2.  Active the compressor for the channel by clicking the 'Active' button under the threshold gain knob so that it turns orange.
3.  Adjust the ratio of compression (a ratio of 3 (also known as 3:1) means for everything over the threshold, two-thirds of the overall level will be removed from the mix. This is visualised on the curve graph, showing how much is removed and at what point.
4.  Next, adjust the threshold. This is the volume level at which the compressor will begin compressing sound. This should be adjusted so that the compressor is just above normal speaking volume, but below any harsh sounds you want to compress. Experimentation with this is needed to figure out the level you need.
5.  Attack, Hold and Release are all generic concepts that can be explained by other sources, but are fine for vocals/speech when left at their defaults.
6.  Note that you can see the level of compression active at any time on the channel by the input level meters on either side of the graph. On the left is the original input signal, and on the right is the amount of compression being applied by the current settings. Note that this graph is upside-down - indicating that it is removing signal, not adding it.

![Compressor setup][7]

# Resetting the equalizer for a channel
Sometimes you'll come across a channel that has previously had EQ settings applied to it, which could be very custom. There's a quick way to reset the EQ state for a channel back to the default settings.

1.  Select the channel, navigate to the 'Home' screen, and click the 'EQ' tab.

2.  You'll see a bunch of settings in place. Click the 'Reset' button, then click 'OK' (see screenshot below). The EQ will be instantly reset. **Note that this means the channel gets dramatically louder if there was a lot of cutting - be careful!**
    ![EQ Reset][5]

# Setup the EQ for a channel
The EQ in this unit is very powerful. There are a lot of different options, and the one I'm going to show you here is the standard 'Gain' setting. This is the default, and is the best one for when you are trying to balance an input, because it doesn't just cut/boost one frequency, but all the surrounding ones in proportionate amounts (so the signal doesn't appear 'fake').

You can have individual EQ settings for every channel in the X32, and for each EQ you get 4 bands to use, as well as a 'Low Cut' to remove hum/noise from the low end of the spectrum. The EQ is visualised for you, so you can see what frequencies you're affecting, and how much you're affecting them. Just remember that the orange sections are where you're cutting the frequency (if it's below the mid-line) or boosting the frequency (if it's above the mid-line). The farther away the peak of each orange segment is from the mid-line, the more you are affecting that frequency (and the surrounding frequencies).

1.  Click the channel you want to edit, navigate to the 'Home' screen, and click the 'EQ' tab (see screenshot below).
2.  Click the 'EQ' button (#2 in screenshot) to activate/deactivate the EQ. Activated = orange.
3.  There are two ways to adjust this - either using the graph itself or the faders under the graph.
    1.  Drag the numbers on the graph left/right to adjust the frequency you're editing, and up/down to adjust the level of cut/boost you're applying to that frequency. Notice how it adjusts the cut/boost of the frequencies around the one you're editing as well.
    2.  You can achieve the same thing by changing the frequency in the 'Freq' box for each of the four sections, and then adjusting the 'Gain' knob underneath the graph.

![EQ active][6]

# Channel Grouping
1.  By default, all channels should output directly to L/R mains. Mixing desks had the concept of 'sub-groups', where you map your first 4 inputs to Group 1 for example, and then you could control the overall level of group 1 with a separate fader. In the X32, these are known as 'DCA' channels.

2.  Click on a channel's button (e.g. Ch01), and then select the DCA group to add it to (see #1 in screenshot below). This will immediately remove the signal from the L/R main mix, and add it to the DCA group you selected instead.

3.  Bring up the DCA fader (see #2 in screenshot below) to adjust the volume level for the entire group.
![DCA Groups][2]


  [1]: https://raw.github.com/madmatt/x32-user-docs/master/img/x32-chan-home.png
  [2]: https://raw.github.com/madmatt/x32-user-docs/master/img/x32-chan-dca-set.png
  [3]: https://raw.github.com/madmatt/x32-user-docs/master/img/x32-mutegrp-set.png
  [4]: https://raw.github.com/madmatt/x32-user-docs/master/img/x32-mutegrp-on.png
  [5]: https://raw.github.com/madmatt/x32-user-docs/master/img/x32-chan-eq-reset.png
  [6]: https://raw.github.com/madmatt/x32-user-docs/master/img/x32-chan-eq-active.png
  [7]: https://raw.github.com/madmatt/x32-user-docs/master/img/x32-chan-compressor-active.png