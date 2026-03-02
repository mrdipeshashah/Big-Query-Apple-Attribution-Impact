I have created a Big Query code using Google Analytics raw data to understand the impact that Apple and IOS is having on Attributon data with a high % of returning visitors on Apple are being tracked as Direct. The looker studio dashboard (https://lookerstudio.google.com/reporting/04b51c90-c830-4cf2-b4f0-8c5015315471) looks at the impact that Apple is having on the data by comparing Tracking Group (Apple/ITP) against a Control Group (Other).

If Google Analytics is already connected to Big Query, then it's a pretty quick to set-up 
  - copy and paste the BQ code - remember to udpate line 45 with the right project + table and save the view 
  - ths looker studio dashboard (using dummy data) visualsing how the data should look.
      - Make a copy of the dashboard and go to Resources > Managed added data source > find the saved view > for each scorecard, table and chart select the saved view 
