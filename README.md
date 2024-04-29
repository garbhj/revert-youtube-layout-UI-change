# Revert-YT-UI-Change
A userscript that aims to revert Youtube's recent UI change, with extensive attention to detail. 
I am fairly certain that V4 is the **most accurate** script for reverting back to the pre-2024 layout, at least out of the ones that I could find.

To use it, install Tampermonkey or some other similar userscript extension, click "Create New Script", and copy and paste in the code.

V4 is much more extensive than V3, with detailed adjustments for font size, the clipped off control bar, video window size, and I fixed the rate limiting.
V3 might be more lightweight, so try that out if you encounter any performance issues (though I really don't think that should be an issue). Or, try adjusting the rate limit.

Future version (Possibly): easier customization with instructions and easily settable variables.

If you encounter any problems, feel free to open an issue, and I may or may not ever come around to checking it 

# Other Notes
For an easier (partial) solution, try simply adding the following line to whichever adblocker you already have that allows you to run your own filters (like UBlock Origin):

  youtube.com##+js(set, yt.config_.EXPERIMENT_FLAGS.kevlar_watch_grid, false)
