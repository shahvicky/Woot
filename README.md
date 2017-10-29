# Woot

WOOT! relies on T-Mobile's fast and reliable cellular network and the security and scale-ability of the AWS IoT to create a robust, off-the-shelf IoT solution for businesses. In addition to helping businesses with their IoT needs, this solution provides an opportunity for T-Mobile to showcase the robustness of their cellular network and acquire new customers.

We used a Raspberry Pi to interface with two temperature and humidity sensors. We registered the Raspberry Pi on AWS IoT platform and created a robust, secure and thorough data stream from the sensors, all the way to a web user interface. We used MQTT protocol to transfer the sensor data to AWS and used a Lambda function to store the values in the DynamoDB. Finally, we added a beautiful web-base user interface as well as rulers that notify the user based on pre-defined triggers.
