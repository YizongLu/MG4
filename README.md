# MG4
## Devlog
When the game starts, _timer will be set as _switchSpeed in function Start. The float variable _timer is used for calculating when the fish food will change direction. The fish food will change direction when _timer is less or equal to 0. And in every frame, it will check whether the fish food go up or not go up. The bool variable _up is used to indicate the direction of the fish food movement. When _up is true, fish food goes up. When _up is false, fish food goes down. When the fish food will go up, it will add a positive distance, which is equal to _moveSpeed * Time.deltaTime, to the y-axis of the fish food so that it will go up. When the fish food will go down, it will add a negative distance, which means minus a distance, to the y-axis of the fish food so that it will go down. In every frame, the _timer will become less as the time goes. When the _timer is less or equal to 0, _timer will reset to _switchSpeed for next direction change, and _up = !up to change current direction. 


## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [City 3D models](https://assetstore.unity.com/packages/3d/environments/simplepoly-city-low-poly-assets-58899)
- [Bite sound effect](https://freesound.org/people/Jofae/sounds/353067/)