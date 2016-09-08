# Builds
A collection of various small projects and games I've worked or am working on

;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;
;;---THE THERENECT--------------;;;;;;;
;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;

A kinect enabled Theremin. 

Only a manual build is currently availible (Mac + Windows)

CONTROLS:

  UP arrow- move a half step up in pitch
  DOWN arrow- move a half step down in pitch
  1 - Decrease Volume
  2 - increase volume
  
  A, W, S, E, D, F, T, G, Y, H, U, J, K, O, I, P, :, ' - keys acting like a keyboard, starting on a C key. can be offset by halfsteps
  
Visualisation:

   W E   T Y U   O P 
  A S D F G H J K L ; '
  
  c d e f g a b c d e f
  
  MODULATION - a wave that causes a held pitch to waver. can control the depth and the speed
  LOWPASS - used to make the saw wave not sound like an eargrater. only allows lower frequency sounds to get through. the lower the value, 
            the lesser the sound.
  ECHO - echo delay time, echo amount, echo volume, original volume.
  Chorus - Chorus effect. can control speed of chorus and depth
  Waves - sets waves of main ocillator and modulator. Availible in Sin, saw, triangle, and square.
  Pitch Shift - shifts the entire theremin range up a half step per value. 
  keyboard shift - moves keyboard keys up and down availible range in half steps
  Glide speed- time it takes to settle from changing notes. the higher, the faster the transition.
  
