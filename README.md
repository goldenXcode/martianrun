# Martian Run!

A 2D running game built with [libGDX](http://libgdx.badlogicgames.com).

<a href="https://play.google.com/store/apps/details?id=com.gamestudio24.cityescape.android">
  <img alt="Get it on Google Play"
       src="https://developer.android.com/images/brand/en_generic_rgb_wo_60.png" />
</a>

You can find a tutorial on how this project started here:

* [Part 1: Project and World Setup](http://williammora.com/a-running-game-with-libgdx-part-1)
* [Part 2: Main Character and Controls](http://williammora.com/a-running-game-with-libgdx-part-2)
* [Part 3: Enemies](http://williammora.com/a-running-game-with-libgdx-part-3)
* [Part 4: Background Animation](http://williammora.com/a-running-game-with-libgdx-part-4)
* [Part 5: Character Animations](http://williammora.com/a-running-game-with-libgdx-part-5)

**Please, DO NOT publish this same game to Google Play. Use it as a blueprint for your game development**

## Features
* Runs on Android and desktop
* On Android, uses [Google Play Game Services](https://developers.google.com/games/services/) and
[AdMob](https://www.google.com/admob/)

## Setup
You need to add the following string resources to your Android project in order for the module to
compile:

```xml

    <!-- Google Analytics: Replace placeholder ID with your tracking ID -->
    <string name="ga_trackingId">UA-XXXXXXXX-X</string>

    <!--
        App ID generated by Google Play Game Services. Replace placeholder ID with yours
    -->
    <string name="app_id">XXXXXXXXXXX</string>

    <!--
        Google Play Game Services IDs (achievements, leaderboards). These are the IDs configured
        for this particular game and you don't need to set any values for them. For your game you
        would have your own achievements, leaderboards, quests and put those strings instead
    -->
    <string name="achievement_getting_started"></string>
    <string name="achievement_like_a_rover"></string>
    <string name="achievement_spirit"></string>
    <string name="achievement_curiosity"></string>
    <string name="achievement_5k_club"></string>
    <string name="achievement_10k_club"></string>
    <string name="achievement_25k_club"></string>
    <string name="achievement_50k_club"></string>
    <string name="achievement_10_jump_street"></string>
    <string name="achievement_100_jump_street"></string>
    <string name="achievement_500_jump_street"></string>
    <string name="leaderboard_high_scores"></string>

    <!-- Google AdMob Unit ID. Place your ad unit ID here -->
    <string name="ad_unit_id"></string>
```

## Credits
Developed by [William Mora](http://williammora.com)

Powered by [libGDX](http://libgdx.badlogicgames.com)

Graphics by [Kenney](http://www.kenney.nl/)

Music by [Kevin MacLeod](http://incompetech.com)

## License
    Copyright 2015 William Mora

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
