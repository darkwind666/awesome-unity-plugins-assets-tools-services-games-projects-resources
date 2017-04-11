# Awesome unity plugins, assets, tools, services, games, projects, resources and more.

# Development

[DOTween](http://dotween.demigiant.com) Great plugin for animation. Usage logic is similar to [actions](http://www.cocos2d-x.org/wiki/Actions) in cocos2dx. I used it for player tutorial animation, sprites animation.

[TSTableView](https://www.assetstore.unity3d.com/en/#!/content/27615) Good plugin for work with tables. Usage is similar to the TableViewController in ios development: create a prefab cell and table is filled with cells dynamically during scrolling.

[Unity-QuickSheet](https://github.com/kimsama/Unity-QuickSheet) Plugin for working with tables. Can transform table in ScriptableObject. Allows data from xlsl, csv, google tables. It is very convenient for working with data for the game balance, levels and game objects characteristics.

# Localization

[SmartLocalization](https://github.com/NiklasBorglund/Smart-Localization-2) Good plugin for localization. You can easily localize the text. It's easy to use with Label - just add a new component to the text and specify the key identifier. Unfortunately, in March 2017, the author stopped development. Plugin now available on free access on github. I used it in two of my games, there were no complaints.

# Leaderboards

[Google Play Games plugin](https://github.com/playgameservices/play-games-plugin-for-unity) plugin for leaderboards on android and ios. Unity has a Social interface. It is has implementation for ios, but has not on android. This plugin help for android leaderboard. There were several compatibility issues with other android plugins, they were solved by removing duplicates of aar and jar files, re-importing the Unity Jar Resolver folder, clicking the Resolve client jars button, downgrading the android build tools.

[Gamesparks](https://www.gamesparks.com) Good backend for games. I used it in my first game. I make a global leaderboard for the desktop game version and for windows phone.

# Push notifications

[OneSignal](https://documentation.onesignal.com/docs#section-how-do-i-get-started-) Service for push notifications. Allows you to send global push notifications. Easy to integrate and use.

# Social networks

[Native share plugin](https://github.com/ChrisMaire/unity-native-sharing) Good tool for implementing share buttons (Share in social networks) You can send screenshots and messages.

[Facebook](https://developers.facebook.com/docs/unity/) Plugin for working with social network. Plugin provides many functions: login, invite friends, join a group, etc. There is also analytics from Facebook, which is useful in tracking installation from advertising companies in social network.

[Vkontakte](https://www.assetstore.unity3d.com/en/#!/content/20127) Paid plugin. I could not find any free solutions :) The plugin allows login, inviting friends, joining a game group, etc. Works for ios, android and windows phone. The developer of the plugin answers any questions and fix the bugs. Great support.

# Analytics

[Firebase](https://firebase.google.com/docs/unity/setup) backend. I used only for additional analytics in the game. It also useful when setting up ad words campaigns for promotion. Game installation tracked based on the firebase calls.

# Crash reports

[Fabric](https://docs.fabric.io/unity/fabric/overview.html) Good platform for bugs tracking. Also it include a tool for analytics. There is also a real-time analytics.

# Monetization

[Appodeal](https://appodeal.com/+93797709d3ce9bbb08b1c065076274e4) Good service for advertising mediation. Support answers questions quickly and solves problems. I used it in two of my games.

# Game projects

[Space Beaver](https://github.com/darkwind666/BeaverAndFairies) (ios, android) It is endless arcade game on unity engine. Game based on swipes and taps control. Use TSTableView, Appodeal, Fabric, Firebase, Vkontakte, Facebook.

[Beaver Time](https://github.com/darkwind666/BeaverTetris) (ios, android, windows phone, desktop) It is tetris based game. Game has levels and bosses.
