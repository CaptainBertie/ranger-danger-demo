# Ranger Danger: interactive demo

A one-page demo of the Ranger Danger check-in prototype (UTS Introduction to Engineering Projects, EWB Challenge 2026, Lama Lama Rangers). The ranger's phone is on the left and the base dashboard is on the right. Press the phone's buttons and watch the base react.

Everything runs in the browser from `index.html`. There is no server, no login and no stored data. The only network requests are for Leaflet (unpkg) and the Esri World Imagery map tiles.

Live page: https://captainbertie.github.io/ranger-danger-demo/

## Test walkthrough

`tests/` holds a click-through record of the prototype tests (buttons, connection, GPS, fall detection). `tests/clips/` has one short clip per row of the automated button test, cut from the phone's screen recording.

Live page: https://captainbertie.github.io/ranger-danger-demo/tests/
