# O'Reilly AI Pokemon (Android)
This repo has the code for the Android app used to recognize pokemons at the O'Reilly AI Conf London, 2018. A lot of this code has been adapted from the sample Tensorflow Image recognition app. The custom model was trained and deployed, with some minor changes in the params and hyperparams.

To run this repo, one needs to install Android Studio, and the Android SDK along with the build tools. Tensorflow recommends Bazel, their build tools however in my personal experience, building with none is slower, however less error prone, since there are lesser dependencies to manage.

An important point to note here, is the size of the trained model, which is close to 5M, and it can do the classification in an average of 30ms, resulting in a very comfortable 30 FPS refresh rate.
