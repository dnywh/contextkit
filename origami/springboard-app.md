| Inputs     | Description                                                                                                  |
| ---------- | ------------------------------------------------------------------------------------------------------------ |
| App Icon   | An image. Doesn’t need to be rounded—the component does that for you. Is displayed on SpringBoard (the home screen). |
| App Name   | The name of your app. Is displayed on SpringBoard (the home screen).                                  |
| App Tint   | The predominant colour of your App Icon and app contents. Helps blend the animation between App Icon and full-app.   |
| Open App   | Pulse to launch your app.                                                                             |
| Close App  | Pulse to close your app and return to SpringBoard.                                                    |
| Wallpaper  | An image. The default iOS water one if unspecified.                                                   |

| Outputs             | Description                                                                                  |
| ------------------- | -------------------------------------------------------------------------------------------- |
| App Icon Down       | Boolean for detecting when App Icon is being pressed.                                        |
| App Icon Pulse      | Pulses when App Icon is tapped.                                                              |
| App Launch Progress | Progress (between 0 and 1) of your app being animated open (and closed). 1 being fully open. |
| App Launched        | Boolean that returns true when App Launch Progress is 1.                                     |
