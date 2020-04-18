# WeatherWeb
The website show current weather and forecast weather by enter the city name.
+ Using jsp, servlet.
+ Using OpenWeatherAPI 

#Environment:
+ jdk 8
+ Kotlin/Java Library for OpenWeatherMap.org Weather APIs: owm-japis-2.5.3.0.jar
+ Some dependencies: 
	<dependencies>

		<dependency>
			<groupId>org.jetbrains.kotlin</groupId>
			<artifactId>kotlin-runtime</artifactId>
			<version>1.2.0</version>
		</dependency>
		<dependency>
			<groupId>org.jetbrains.kotlin</groupId>
			<artifactId>kotlin-stdlib</artifactId>
			<version>1.2.0</version>
		</dependency>
		<dependency>
			<groupId>com.squareup.okhttp3</groupId>
			<artifactId>okhttp</artifactId>
			<version>3.8.1</version>
		</dependency>
		<dependency>
			<groupId>com.google.code.gson</groupId>
			<artifactId>gson</artifactId>
			<version>2.8.1</version>
		</dependency>
		<dependency>
			<groupId>com.squareup.retrofit2</groupId>
			<artifactId>retrofit</artifactId>
			<version>2.3.0</version>
		</dependency>
		<dependency>
			<groupId>com.squareup.retrofit2</groupId>
			<artifactId>converter-gson</artifactId>
			<version>2.3.0</version>
		</dependency>
		
	</dependencies>
# Use open weather map api:
+ we must get a API Key from: https://openweathermap.org/ (free/pro)
+ Write your code as such:
Create and initialize object {obj1} of "OWM" class or "OWMPro" class
Call this object's {obj1} functions to get the desired weather data (such as current weather, daily forecast, etc.).
The data is returned as a new object {obj2} of a compatible class based on the type of asked/retrieved weather data (current weather data comes in a different class's object than daily forecast data).
Call this returned object's {obj2} functions to get the required information from the collective weather data (like humidity, temperature, pressure, wind speed, etc.).
