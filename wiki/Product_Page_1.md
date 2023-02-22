# App Update with Social Media Links

## Overview
Once a week, REQUESTOR has been manually exporting all location social media links from APP and importing all of it into APP to keep the system updated. She has requested assistance in automating this process.
We agreed upon updating only locations with changes, so our process will need to incorporate querying APP and comparing to APP before moving the data.
We have the power to edit a location’s name, active status, phone number, email, and all social media links. It has been decided we will only update the links for now.

### List of social media
<ul>
  <li>Facebook</li>
  <li>GoogleMyBusiness</li>
  <li>Instagram</li>
  <li>LinkedIn</li>
  <li>CustomURL</li>
</ul>

## Implementation
The following steps are done in Python nightly:
<ol>
  <li>Query APP for all locations and their social links</li>
  <li>Iterate through each location's list of links and compare with the links saved in APP</li>
  <li>Export to csv all location links that are different and need updating</li>
  <li>Send csv somewhere</li>
</ol>

## Data Model Description
Table A is the center of a star schema... See diagram...

### Diagram
![title](/assets/images/logical-data-model-diagram.svg)

## Validation

## Common Errors
<i>No known</i>

## Future Phases
<i>No known</i>
