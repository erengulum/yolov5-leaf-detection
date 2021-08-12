# yolo-plant-detection
Feel free to check detailed source code for the full version of Plant Classification Web-app Project: https://github.com/erengulum/plantcare
Web app on Heroku: https://bbm416-plant.herokuapp.com/


Yolo V5S & V5M and V5L are used to detect leaf types

  **Results for Leaf Detection (Yolo v5)**
We decided to use the Yolo method for the Leaf Detection. We conducted experiments with three different implementations of Yolo v5 (v5S, v5M and v5L), which is the latest version. Epoch value is set to 200 and PlantDoc was used as the dataset. The success rates of Yolo v5M and v5L were comparable, but the v5L has slightly better results. Although it is a bit slower than v5M, we chose it because it doesn’t change the user experience that much.

