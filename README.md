# AR Project - Group 53: Mini Car Showroom

A marker-based AR scene (A-Frame + AR.js, Hiro marker): a car on a rotating showroom floor.

## Features

- **Hiro marker scene:** cylinder, torus, sphere, box, glTF car model and `<a-text>` labels
- **Animations:** car spin (rotation), ring spin (rotation), ball bobbing (position), box grow (scale)
- **Interaction:**
  - Tap the ball to change its colour (`colour-change` component)
  - Tap the yellow box to grow it and show/hide a label (`grow-toggle`, our own custom component)
- **Status banner:** red "Searching for Marker..." / green "Marker Found!"

## Live Demo

Hosted over HTTPS: https://mhbpwijerathne.github.io/Group-53-AR/

## How to Use

1. Open the live demo link on a phone and allow camera access.
2. Point the camera at the Hiro marker.
3. Tap the ball to change its colour.
4. Tap the yellow box to make it grow and show a label. Tap again to shrink it and hide the label.

## Technologies

- [A-Frame](https://aframe.io/) 1.3.0
- [AR.js](https://github.com/AR-js-org/AR.js) 3.4.5

## Credits

3D model: "Cartoon Car" by Benjamin Aubert (@bainjamaing), https://sketchfab.com/3d-models/cartoon-car-a5f6a99597d34c06832e7cc07e4a6c69, licensed under CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/).

## Group 53

