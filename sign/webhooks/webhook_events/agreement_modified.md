# Payload template: AGREEMENT\_MODIFIED

```json
{  
   "webhookId":"",
   "webhookNotificationId":"",
   "webhookUrlInfo":{  
      "url":""
   },
   "webhookScope":"",
   "event":"",
   "subEvent":"",
   "eventResourceType":"",
   "participantUserId":"",
   "participantUserEmail":"",
   "actingUserId":"",
   "actingUserEmail":"",
   "initiatingUserId":"",
   "initiatingUserEmail":"",
   "agreement":{  
      "id":"",
      "name":"",
      "signatureType":"",
      "status":"",
      "ccs":[  
         {  
            "email":"",
            "label":"",
            "visiblePages":[  
               ""
            ]
         }
      ],
      "deviceInfo":{  
         "applicationDescription":"",
         "deviceDescription":"",
         "location":{  
            "latitude":"",
            "longitude":""
         },
         "deviceTime":""
      },
      "documentVisibilityEnabled":"",
      "createdDate":"",
      "expirationTime":"",
      "externalId":{  
         "id":""
      },
      "postSignOption":{  
         "redirectDelay":"",
         "redirectUrl":""
      },
      "firstReminderDelay":"",
      "locale":"",
      "message":"",
      "reminderFrequency":"",
      "senderEmail":"",
      "vaultingInfo":{  
         "enabled":""
      },
      "workflowId":"",
      "participantSetsInfo":{  
         "participantSets":[  
            {  
               "memberInfos":[  
                  {  
                     "id":"",
                     "email":"",
                     "company":"",
                     "name":"",
                     "privateMessage":"",
                     "status":""
                  }
               ],
               "order":"",
               "role":"",
               "status":"",
               "id":"",
               "name":"",
               "privateMessage":""
            }
         ],
         "nextParticipantSets":[  
            {  
               "memberInfos":[  
                  {  
                     "id":"",
                     "email":"",
                     "company":"",
                     "name":"",
                     "privateMessage":"",
                     "status":""
                  }
               ],
               "order":"",
               "role":"",
               "status":"",
               "id":"",
               "name":"",
               "privateMessage":""
            }
         ]
      },
      "documentsInfo":{  
         "documents":[  
            {  
               "id":"",
               "label":"",
               "numPages":"",
               "mimeType":"",
               "name":""
            }
         ],
         "supportingDocuments":[  
            {  
               "displayLabel":"",
               "fieldName":"",
               "id":"",
               "mimeType":"",
               "numPages":""
            }
         ]
      }
   }
}
```