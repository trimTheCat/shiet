# shiet
 Should I Eat This? The app will use Raspberry PI to scan an image output using an AI model and recommend the calories and nutrients.

User story

GIVEN

A home user has access to home-cooked and industrial food.

WHEN

Considering the benefits of food/ beverage consumption.

THEN

1. A DIY (using a Raspberry PI 5 as an example, you can offer other alternatives)system should use a wifi camera (possibly ESP32-CAM) and scale to identify the food or beverage to be consumed.
2. The system should scale the food and, using a dedicated AI model, output the number of calories and nutrients to be consumed.
3. The system should compare the to-be-consumed food and beverages and propose healthier, similar alternatives.
4. The system should prompt the user if he/she will approve the consumption. Once approved, the calorie and nutrient values should be announced on an Alexa-enabled Sonos speaker.
5. If approved for consumption, the system should track the food and beverage consumed and adjust the daily calorie balance accordingly. 
6. The user should be able to define the daily calorie target goal and the system should reset it daily at midnight to the initial setup.
7. If the daily consumption goal is breached, a hardware LED light bulb should be turned on, and the LED should be red.


Your goal is to:
1. Provide the technical hardware specifications to build such a system.It will be ordered from the https://piitel.co.il/shop/ website. Provide a list of components that should be ordered from the website, including links and compare those to other alternatives on the web. 
2. Provide the technical software specifications to build such a system. 
3. Image recognition should use a free AI model.
4. Food consumption data should be stored and maintained via APIs in ServiceNow.
5. Provide step-by-step instructions to assemble and deploy the hardware components.
6. Provide the required code to run this system. The primary code for this project should be JavaScript, use Python if JavaScript isn’t supported or sufficient. Explain each step in depth.
7. Provide step-by-step instructions to test the system
8. Provide step-by-step instructions to make the system production-ready.
