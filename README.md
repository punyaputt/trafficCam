# trafficCam
index.html gather Traffic-Cam from BMAtraffic.com<br />
However, BMAtraffic have CORS protection. So, proxy API is needed.<br />
Medium server is used(local for here) to receive request endpoint, and repeat the request to the target.<br />
After server receive response from target, server repeat the response to our origin request, index.html here.<br />
Completely eliminate CORS.
