# Animate.MIT.css

This is a fork of the original animate.css project; it was forked from the point where it was last updated as an MIT-licenced project, after which the licence changed to become non-compatible with open-source projects.

Given the original project has also not been maintained in over a year, Jul 2022 to Nov 2023, I'll be pushing security updates and patches to this repository going forward instead, unless the original project owner choose to continue it. I'm renaming things a bit to animate.mit.css v5, to help me avoid confusing the original project with this one.

## Documentation
https://steveseguin.github.io/animate.mit.css/

| Attention Seekers || Back Entrances   | Back Exits       | Bouncing Entrances | Bouncing Exits    |
|-------------------|------------------|------------------|------------------|--------------------|-------------------|
| bounce            |heartBeat| backInDown       | backOutDown      | bounceIn           | bounceOut         |
| flash             |jello| backInLeft       | backOutLeft      | bounceInDown       | bounceOutDown     |
| pulse             |wobble| backInRight      | backOutRight     | bounceInLeft       | bounceOutLeft     |
| rubberBand        |tada| backInUp         | backOutUp        | bounceInRight      | bounceOutRight    |
| shakeX            |swing|                  |                  | bounceInUp         | bounceOutUp       |
| shakeY            |headShake|                  |                  |                    |                   |

| Fading Entrances    | Fading Exits       | Flippers       | Lightspeed        | Rotating Entrances  |
|---------------------|--------------------|----------------|-------------------|---------------------|
| fadeIn              | fadeOut            | flip           | lightSpeedInRight | rotateIn            |
| fadeInDown          | fadeOutDown        | flipInX        | lightSpeedInLeft  | rotateInDownLeft    |
| fadeInDownBig       | fadeOutDownBig     | flipInY        | lightSpeedOutRight| rotateInDownRight   |
| fadeInLeft          | fadeOutLeft        | flipOutX       | lightSpeedOutLeft | rotateInUpLeft      |
| fadeInLeftBig       | fadeOutLeftBig     | flipOutY       |                   | rotateInUpRight     |
| fadeInRight         | fadeOutRight       |                |                   |                     |
| fadeInRightBig      | fadeOutRightBig    |                |                   |                     |
| fadeInUp            | fadeOutUp          |                |                   |                     |
| fadeInUpBig         | fadeOutUpBig       |                |                   |                     |
| fadeInTopLeft       | fadeOutTopLeft     |                |                   |                     |
| fadeInTopRight      | fadeOutTopRight    |                |                   |                     |
| fadeInBottomLeft    | fadeOutBottomRight |                |                   |                     |
| fadeInBottomRight   | fadeOutBottomLeft  |                |                   |                     |

| Rotating Exits      | Specials         | Zooming Entrances | Zooming Exits     | Sliding Entrances | Sliding Exits   |
|---------------------|------------------|-------------------|-------------------|-------------------|-----------------|
| rotateOut           | hinge            | zoomIn            | zoomOut           | slideInDown       | slideOutDown    |
| rotateOutDownLeft   | jackInTheBox     | zoomInDown        | zoomOutDown       | slideInLeft       | slideOutLeft    |
| rotateOutDownRight  | rollIn           | zoomInLeft        | zoomOutLeft       | slideInRight      | slideOutRight   |
| rotateOutUpLeft     | rollOut          | zoomInRight       | zoomOutRight      | slideInUp         | slideOutUp      |
| rotateOutUpRight    |                  | zoomInUp          | zoomOutUp         |                   |                 |

## Installation

Install with npm:

```shell
npm install animate.css --save
```

Install with yarn:

```shell
yarn add animate.css
```

## Original Core Team

| ![Daniel Eden](https://avatars2.githubusercontent.com/u/439365?s=460&u=512b4cc5324938ae40bbb8f3b7769d335953cd3a&v=4) | ![Elton Mesquita](https://avatars2.githubusercontent.com/u/5007208?s=460&u=418401ee605824272e5dcb955fd64ea24546a857&v=4) | ![Waren Gonzaga](https://avatars1.githubusercontent.com/u/15052701?s=460&u=9e58364978379536d3f26c4ce5cae1a2a449a0e4&v=4) |
| --- | --- | --- |
| [Daniel Eden](https://github.com/daneden) | [Elton Mesquita](https://github.com/eltonmesquita) | [Waren Gonzaga](https://github.com/WarenGonzaga) |
| Animate.css Creator | Maintainer | Core Contributor |

## License

This project is licensed under the MIT license. <https://opensource.org/licenses/MIT>

## Code of Conduct

This project and everyone participating in it is governed by the [Contributor Covenant Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code.
