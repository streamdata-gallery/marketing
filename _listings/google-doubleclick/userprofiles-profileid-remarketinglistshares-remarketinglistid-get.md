---
swagger: "2.0"
info:
  title: Google Doubleclick API Get Remarketing List Shares
  version: 1.0.0
  description: Gets one remarketing list share by remarketing list ID.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /userprofiles/{profileId}/remarketingListShares/{remarketingListId}:
    get:
      summary: Get Remarketing List Shares
      description: Gets one remarketing list share by remarketing list ID
      operationId: dfareporting.remarketingListShares.get
      parameters:
      - in: path
        name: profileId
        description: User profile ID associated with this request
      - in: path
        name: remarketingListId
        description: Remarketing list ID
      responses:
        200:
          description: OK
      tags:
      - advertising
      - remarketing list
definitions: []
x-collection-name: Google Doubleclick
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---