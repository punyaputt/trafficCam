# trafficCam
This project developed locally, will be uploaded very soon, within 21/1/2023 15:00
index.html gather Traffic-Cam from BMAtraffic.com
However, BMAtraffic have CORC protection. So, proxy API is needed.
Medium server is used(local for here) to receive request endpoint, and repeat the request to the target.
After server receive response from target, server repeat the response to our origin request, index.html here.
Completely eliminate CORS.
