# direct-msg-monitor
The message monitoring module is aggregating tracked message in a HISP and determining if failure notification messages need to be sent to a message originator based on specific conditions. The default implementation of this module implements a generic condition algorithm for messages that do not conform to the [implementation guide](http://wiki.directproject.org/w/images/a/a1/Implementation_Guide_for_Delivery_Notification_in_Direct_v1.0.pdf) for delivery notification of the Direct Project. It also implements the monitoring conditions as specified by the the reliable and timely messaging implementation guidance of the Direct Project.

Full documentation can be found [here](https://directprojectjavari.github.io/direct-msg-monitor/)
