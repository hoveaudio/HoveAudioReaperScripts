I use this script as the final step of a cycle action to toggle my tuner. This script just ensures that I never delete any track that isn't named "Tuner" by accident.

This setup was inspired by the Reaper Tips video https://www.youtube.com/watch?v=V6Lhvkhd3tk

Although, I think my method is much better. You get a full screen tuner instead of a tiny ui embedded into your track.

The action itself:

-Show/Hide Tuner-
1. SWS: Create and select first track
2. Apply track template to selected tracks, slot 1 (slot one for me at least)
3. -Step-
4. Script: DeleteTuner

I set the Tuner FX to a floating window in my template.
