# [Download v4.3](https://github.com/oJumpy/BOIII-T7-Zombies-AutoTimers/releases/download/v4.3/Black-Ops-3_v4.3.asl)

# Livesplit-AutoTimers-BOIII
A multi-functional LiveSplit script for Call of Duty: Black Ops 3 Zombies.

### [DOA Version download v3.4](https://github.com/oJumpy/Livesplit-AutoTimers-BOIII/releases/download/v3.4/Black-Ops-3-Master.DOA.asl)
#### Recommended DOA Splits
- For optimal functionality with the DOA version, please use the [DOA Splits file](https://github.com/oJumpy/Livesplit-AutoTimers-BOIII/releases/download/v3.4/DOA.Splits.lss). This ensures the timer follows DOA's specific splitting logic. See [Setting up Splits](#setting-up-splits) for installation instructions.

## Setup
1. Download Livesplit [Site](https://livesplit.org/downloads/) or [Direct Link](https://github.com/LiveSplit/LiveSplit/releases/download/1.8.33/LiveSplit_1.8.33.zip)
1. Right Click LiveSplit → Edit Layout → `+` button → Control → Scriptable Auto Splitter → Browse to `Black-Ops-3-Master.asl` and select it.

   <img width="171" height="408" alt="image" src="https://github.com/user-attachments/assets/6c73bba6-de80-47d0-baf6-23e54746fb8e" />
   <img width="546" height="352" alt="image" src="https://github.com/user-attachments/assets/a2646ab6-2bc3-42c2-aaff-b701996d242b" />



3. If you want splits, refer to [Setting up Splits](#setting-up-splits) at this point.
1. Right Click LiveSplit → Compare Against → Select `Game Time`, Look down to where it says: *Best Segments*, *Average Segments*...
1. If you are using BOIII Client, you need to use a specific version of it. [BOIII Community GitLab](https://gitlab.com/boiii-community/BOIII-Community) and make sure that you have the .exe named to just `boiii` in order to make the timer work!

## Setting up Splits
- Download [Blank Splits to 255](https://github.com/oJumpy/IW7-Zombies-AutoTimers/releases/download/v1/Blank.to.255.lss).
- Right Click LiveSplit → `Open Splits` → `From File...` → Browse to the splits file and select it.

## AutoSplitter Recommendations
- [LiveSplit Components](https://github.com/oJumpy/Livesplit-AutoTimers-BOIII/releases/download/V3.0/Useful.zip)
- [My Layout](https://github.com/oJumpy/IW7-Zombies-AutoTimers/releases/download/v1/recommended_layout.lsl)
- [Useful stuff, like round times in solo, 2p, 3p and 4p](https://github.com/oJumpy/Livesplit-AutoTimers-BOIII/releases/download/V3.0/Useful.rar)

  ![image](https://github.com/user-attachments/assets/ab38b042-d2d3-4ef8-8501-487a74515c08)


## Custom Layouts
If you are going to make your own layout, make sure your LiveSplit is comparing against `Game Time` for everything. This includes `Subsplits`, `Splits`, `Timer`, `Detailed Timer`, etc.

For `Timing Method`, I recommend using `Current Timing Method`.

## Coming Soon
- Box hit tracker for all maps, I already got all the addresses, just need to apply the logic.

## Credits
- [Scrappy](https://github.com/Joshr520): Previous auto splitter script for coops.
- [Riot](https://twitch.tv/riot) and Chris4a4: Old Game Timer, Round Timer, Reset Timer, and Trap Timer, which served as base for many of the previous scripts.
- [ROFLailXGOD](https://github.com/ROFLailXGOD/TimerPause): For Livesplit Timer Pause Component

# From Version 4.2+

# [Download v4.2-Beta](https://github.com/oJumpy/Livesplit-AutoTimers-BOIII/releases/download/v4.2-Beta/Black-Ops-3_v4.2-Beta.asl)
# 4.2 BETA VERSION

- Fixed main layout saving issue: Resolved the problem where saving layouts with certain settings enabled would cause duplicate Text components and timer size issues.
> [!NOTE]
> **Although it might not be perfect still, as it has still some "issue" with having to do things manually, i think this is a much better approach compared to how it was before, as now you can actually save your layouts.**
>
> - When disabling a setting, the text component may remain visible with an empty value
> - You WILL need to manually remove these empty text components from your layout
> This is still a major improvement over previous versions where layout saving was essentially broken.

# From Versions 4.1 and below

## Known Issues
> [!CAUTION]
> These are some known issues with the timer, and will be fixed in the future.
> ### Saving layouts
> If you save your layout, with some settings enable you will encounter unexpected behavior. Example:
> - Duplicates Reset options and or other settings if enabled.
> - Timer size will get smaller
> ### Solution
> Save your layout only when you first loaded the script or click on `Reset to default` in the bottom right in `Scriptable Auto Splitter`, then save.
> I recommend to never save your layout whenever you enable additional settings.


