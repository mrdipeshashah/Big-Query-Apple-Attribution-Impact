This repository contains Big Query code using Google Analytics raw data to understand the impact that Apple and IOS is having on Attributon data with a high % of returning visitors on Apple are being tracked as Direct. I have developed a looker studio dashboard (https://lookerstudio.google.com/reporting/04b51c90-c830-4cf2-b4f0-8c5015315471) looks at the impact that Apple is having on the data by comparing Tracking Group (Apple/ITP) against a Control Group (Other).

If Google Analytics is already connected to Big Query, then it's a pretty quick to set-up 
  1) Google Analytics is connected to Big Query
  2) The Big Query code provided, create and save the views in Big Query
  3) Make a copy of the looker studio dashboard and connect it to the saved view
