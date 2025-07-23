This repository is to manage the current and former versions for the Circles v2 whitepaper. There is a simple workflow in place that anybody with write access can manually trigger to update the file that will be accessible at whitepaper.aboutcircles.com. 

To trigger this workflow, go to https://github.com/aboutcircles/whitepaper-public/actions/workflows/sync-whitepaper-gcpbucket.yml -> Click on Promote PDF to GCS workflow (left tab) -> Run Workflow -> In the dropdown file the filename (as path from root dir).

Everywhere else references to the whitepaper should always point to whitepaper.aboutcircles.com
