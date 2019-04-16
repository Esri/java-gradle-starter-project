# arcgis-java-gradle-starter-project
Starter project for the ArcGIS Runtime SDK for Java with Gradle. 

The project includes the Gradle wrapper, so there is no need to install Gradle to run the app.

The app launches a window displaying a map.

![screenshot](screenshot.png)

### IntelliJ IDEA

1. Open IntelliJ IDEA and select _File > Open..._.
2. Choose the arcgis-java-gradle-starter-project directory and click _OK_.
3. Select _File > Project Structure..._ and ensure that the Project SDK and language level are set to use Java 11.
4. Open the Gradle view with _View > Tool Windows > Gradle_.
5. Refresh the Gradle project by clicking the _Refresh all Gradle projects_ button in the Gradle view toolbar. This will cause the ArcGIS Runtime SDK Gradle plugin to download the native libraries.
6. In the Gradle view, double-click `run` under _Tasks > application_ to run the app.

### Eclipse

1. Open Eclipse and select _File > Import_.
2. In the import wizard, choose _Gradle > Existing Gradle Project_, then click _Next_.
3. Select the arcgis-java-gradle-starter-project directory directory as the project root directory.
4. Click _Finish_ to complete the import.
5. Right-click the project in the Project Explorer or Package Explorer and choose _Gradle > Refresh Gradle project_. This will cause the ArcGIS Runtime SDK Gradle plugin to download the native libraries.
6. Open the Gradle Tasks view with _Window > Show View > Other... > Gradle > Gradle Tasks_.
7. In the Gradle Tasks view, double-click `run` under _arcgis-java-gradle-starter-project > application_ to run the app.

### Command Line

1. `cd` into the project's root directory.
2. Run `./gradlew clean build` on Linux/Mac or `gradlew.bat clean build` on Windows once to make sure the dependencies are fetched.
3. Run `./gradlew run` on Linux/Mac or `gradlew.bat run` on Windows to run the app.

## Licensing

Copyright 2019 Esri

Licensed under the Apache License, Version 2.0 (the "License"); you may not 
use this file except in compliance with the License. You may obtain a copy 
of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software 
distributed under the License is distributed on an "AS IS" BASIS, WITHOUT 
WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the 
License for the specific language governing permissions and limitations 
under the License.

A copy of the license is available in the repository's license.txt file.
