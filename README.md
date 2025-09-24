# Project 1 - Wordle

Submitted by: Eric Nguyen

Wordle is an iOS app that lets users play a simplified version of the popular Wordle game.  
The user can type letters using a custom on-screen keyboard, see them appear on the board, delete letters, and try to guess a random word chosen each time the app runs.  
I also customized the app by adding a **launch screen** and a **custom app icon**.

Time spent: 8 hours spent in total

## Required Features

The following **required** functionality is completed:

- [x] App displays a keyboard on the screen
- [x] When tapping on the keyboard, a letter is shown or deleted (letter selected)
- [x] User can play a basic version of Wordle, with different goal words each time

The following **optional** features are implemented:

- [x] Improve and customize the user interface by adding a launch screen and app icon
- [ ] Run the app on a device rather than in the simulator

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app functionality!

## Video Walkthrough

Here is a reminder on how to embed Loom videos on GitHub. Feel free to remove this reminder once you upload your README. 

[Guide](https://www.youtube.com/watch?v=GA92eKlYio4) .


## Notes

### Challenges I encountered:
- Understanding how `section` and `row` work in `UICollectionView`.
- Getting closures (`didSelectString`) connected properly between the keyboard and the board.
- Remembering to use `self.property = parameter` (not the other way around).
- Adding the launch screen and app icon:
  - Added the icon images generated from Apple’s Icon Deposer into **Assets.xcassets → AppIcon**.
  - Updated **LaunchScreen.storyboard** with a centered logo and background color.
  - Verified in the simulator that the app icon shows on the home screen and the launch screen displays before the game.


## License

    Copyright [2025] [Eric Nguyen]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.