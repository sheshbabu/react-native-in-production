# How React Native Helps Companies Build Better Mobile Apps

[Link to video](https://developers.facebook.com/videos/f8-2018/how-react-native-helps-companies-build-better-mobile-apps/)

## Why was it chosen

### Facebook
* Platform specific codebases result in
  * Developers hitting different snags
  * Each platform moving in different speeds
  * Getting out of sync
  * Doing same things twice
  * Polish/optimization doesn’t get done uniformly in both platforms

### Skype
* Platforms: iOS, Android, Windows, Mac, Linux - Using ReactNative or Electron+React
* Before ReactNative
  * 7 devs and 7 product owners for each platform across multiple timezones
  * Main issue was communication between different platforms in different timezones
* After ReactNative
  * Moved from platform specific teams to feature squads that focus on delivering features across different platforms
  * Feature squads reduce the communication challenges and improve development velocity
  * Reduces implementation discrepancies in different platforms
  * Got transferable knowledge as all the teams speak the same language
  * Easy to ramp up squads for new features and ramp down squads for other features
  * Ramp up time is almost zero as there’s a single language used
  * Lost good developers
  * Focus on hiring generalists
  * React - Same UI description language and layout semantics for all platforms
  * React - Everything is encapsulated in a component as opposed to code scattered across different layers
* Uses ReactXP

### TaskRabbit
* Before ReactNative
  * 3 devs on each mobile platform
* After ReactNative
  * 2 person team moving faster than the 6 person team
  * Business logic lives in a single place and bugs gets fixed for both platforms at same time
  * Helps in hiring

### Postlight
* Postlight has React (web) experience
* 1.5 devs, completed before deadline and under budget

### CondeNast
* CondeNast is a JS shop, so using ReactNative to leverage that experience
* Why replace Swift with JS?
  * Declarative layouts with JSX
  * Writing layouts in Swift is hard
  * Iterate very rapidly
  * Lower the barrier to create layouts
  * Frees developers from working on “pixel pushing”
  * Gives them time to focus on harder and interesting things


## Lessons learned

### Postlight
* Was able to do performance tuning for low-end devices targetting Indian market
* ReactNative is not prescriptive and makes it possible to drop out of ReactNative and use native modules when needed
* Ran into performance issues when you don’t expect the same with native modules (long scrolling lists etc)

### CondeNast
* Being early adopter
  * Going through multiple ReactNative version bumps is tough
  * Better suited for apps that are under active development as batching several updates at once is painful
