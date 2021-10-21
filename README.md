# velociraptor-misp
Artifacts for integrating MISP with Velociraptor

### Intel.MISP.Upload
Pull down threat intel from MISP and store it for Velociraptor clients to grab.

### Intel.MISP.Client.Process
Monitor DNS, TCP/IP, and USN, pulls down intel from server and checks to see if values match indicators from MISP.

### Server.Enrichment.MISP
Look up MISP events from an indicator.

### TBD
Other artifacts are in progress to move the matching from the client to the server if users are concerned with distributing intel to the client.

After enough testing, I will submit these artifacts to the Velociraptor Artifact Exchange to make them easier to leverage.
