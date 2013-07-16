systemd-config
==============

Systemd config files with user units.

Works with LXDM and Awesome WM.
Sound is connected like this: Hardware USB Audio -> Alsa -> Jack2 DBus -> PulseAudio.
You may be asking why the hell would I use such construction. The answer is, I use Chromium/Flash which works with Pulse and for music composition I use primarily Jack.
Suspend and resume should work. I've included an unit for explicit resuming of USB sound card.

Feel free to comment and improve these unit files. :)
