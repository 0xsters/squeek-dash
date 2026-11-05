# Squeek Dash

A one-button runner game paced by a real hamster.

Squeek Dash reads Squeektoshi's live wheel telemetry from the public
Squeekchain status API (wheel state, RPM, rim speed, Squeek block height)
and turns it into gameplay:

- His rim speed sets the speed of your world. Zoomies means a fast run,
  a nap means a gentle jog.
- The wheel in the corner of the screen spins at his real RPM.
- Race bars compare your distance against the distance his wheel covers
  during the same run.
- No wallet, no signup, no gas. Scores live in the browser only.
- If the API signal drops, the game keeps the last known pace and says so.

## Play

Open `index.html` in a browser, or visit the deployed site.
Press SPACE or tap to jump. One file, no build step, no dependencies.

## Category

Built for the Squeekchain Genesis Code board as a game powered by
Squeekchain's live rounds and wheel data. Fan-made, not affiliated with
the Squeekchain team. Test network only.

## Tech

Plain HTML, CSS and JavaScript in a single file. Data source:
https://api.squeekchain.com/v1/status
