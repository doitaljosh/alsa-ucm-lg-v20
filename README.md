ALSA Use-Case Configuration Files for the LG V20 Smartphone

Place the folder called `msm8996-tasha-snd-card` into `/usr/share/alsa/ucm` to use the audio hardware found on the LG V20.
This should work with GNU/Linux chroots or native installs that have `alsa-utils` and `pulseaudio` installed.

## The following features are working with these files on the LG V20:

#### Playback devices:
- Internal Bottom Speaker (24 bit enabled)
- Non-HiFi Headset (24 bit enabled)
#### Capture devices:
- Top Microphone
- Bottom Microphone
- Front Microphone
- Headset Microphone
- Stereo Microphones (24 bit enabled)

## TODO:
- Bring up HiFi DAC (Should be very easy. Was able to do so manually using `alsa cset` commands.)
- Low latency playback
- HDMI audio
- Earpiece speaker
- Stereo speakers using earpiece in conjunction with bottom firing speaker.
