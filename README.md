# IBM-NHS-UCL_DespatchDrone
UCL IXN Drone Navigation dashboard project

This is a proof of concept for a drone navigation system. The drone used for this dashboard is the DJI Ryze Tello EDU. The dashboard utilises flows in the Node-RED library.

An assumption is made that the user knows how to use Node-RED and can add to the dashboard; this is especally the case with the pre-set flight plans in the pre-set controller tab where uses can hardcode their own popular flight plans.

BMI hospital to Mile End hospital was chosen as a pre-set flight plan due to the short distance between the two hospitals within the London area. Theoretically, with no wind the Tello EDU could make the distance with a battery life of 13mins flying at 1 m/sec for a distance of 676m (calcualted by traingualting the distance using google maps). The drone lacks GPS therefore, the drone would have to be pointed in the direction of the final location.
