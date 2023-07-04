# Online_Radio
Multicasting-media-over-IP-for-internet-based-Radio

The project will function as described below:
To join the multicast group, the client must first send a join request to the server. The client will then get a station list and site information from the server through TCP. It then connects to the station that it chooses from the list of stations. Whether a client is connected or not, all stations are sending data. This feature was added to better reflect real-world situations, such as when a TV or radio transmits data even when no receiver is plugged in. When a receiver connects to a certain station, it begins to receive videos that are being streamed live from that station. Using a thread, the receiver can pause, resume, switch stations, or even terminate at any time via the GUI.
