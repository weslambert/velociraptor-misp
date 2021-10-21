# velociraptor-misp
Artifacts for integrating MISP with Velociraptor

NOT intended for use in production at this time -- this needs more testing :)

### Intel.MISP.Upload
Pull down threat intel from MISP and store it for Velociraptor clients to grab.

### Intel.MISP.Client.Process
Monitor DNS and TCP/IP ETW providers, as well as USN. Pulls down intel from server and checks to see if values match indicators from MISP.

### Server.Enrichment.MISP
Look up MISP events from an indicator.

### TBD
Other artifacts are in progress to move the matching from the client to the server if users are concerned with distributing intel to the client, as well as to create events in MISP from Velociraptor.

Additionally, CSV-formatted indicators may be moved to sqlite.

After enough testing, I will submit these artifacts to the Velociraptor Artifact Exchange to make them easier to leverage.
