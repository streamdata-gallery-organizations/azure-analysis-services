---
name: Azure Analysis Services
x-slug: azure-analysis-services
description: Use Azure Resource Manager to create and deploy an Azure Analysis Services
  instance within seconds, and use backup restore to quickly move your existing models
  to Azure Analysis Services and take advantage of the scale, flexibility and management
  benefits of the cloud. Scale up, scale down, or pause the service and pay only for
  what you use.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transform-complex-data.png
x-kinRank: "10"
x-alexaRank: ""
tags: Azure Analysis Services
created: "2018-05-21"
modified: "2018-05-21"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-analysis-services/master/_listings/azure-analysis-services/apis.md
specificationVersion: "0.14"
apis:
- name: Azure Analysis Services API Get Server
  x-api-slug: azure-analysis-services-api
  description: Gets details about the specified Analysis Services server.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transform-complex-data.png
  humanURL: https://azure.microsoft.com/en-us/services/analysis-services/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.AnalysisServices/servers/{serverName}
  tags: Servers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-analysis-services/master/_listings/azure-analysis-services/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftanalysisservicesserversservername-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-analysis-services/master/_listings/azure-analysis-services/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftanalysisservicesserversservername-get-openapi.md
- name: Azure Analysis Services API Create Server
  x-api-slug: azure-analysis-services-api
  description: Provisions the specified Analysis Services server based on the configuration
    specified in the request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transform-complex-data.png
  humanURL: https://azure.microsoft.com/en-us/services/analysis-services/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.AnalysisServices/servers/{serverName}
  tags: Servers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-analysis-services/master/_listings/azure-analysis-services/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftanalysisservicesserversservername-put-openapi.md
- name: Azure Analysis Services API Delete Servers
  x-api-slug: azure-analysis-services-api
  description: Deletes the specified Analysis Services server.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transform-complex-data.png
  humanURL: https://azure.microsoft.com/en-us/services/analysis-services/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.AnalysisServices/servers/{serverName}
  tags: Servers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-analysis-services/master/_listings/azure-analysis-services/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftanalysisservicesserversservername-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-analysis-services/master/_listings/azure-analysis-services/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftanalysisservicesserversservername-delete-openapi.md
- name: Azure Analysis Services API Update Server
  x-api-slug: azure-analysis-services-api
  description: Updates the current state of the specified Analysis Services server.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transform-complex-data.png
  humanURL: https://azure.microsoft.com/en-us/services/analysis-services/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.AnalysisServices/servers/{serverName}
  tags: Servers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-analysis-services/master/_listings/azure-analysis-services/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftanalysisservicesserversservername-patch-openapi.md
- name: Azure Analysis Services API Suspend Server
  x-api-slug: azure-analysis-services-api
  description: Supends operation of the specified Analysis Services server instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transform-complex-data.png
  humanURL: https://azure.microsoft.com/en-us/services/analysis-services/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.AnalysisServices/servers/{serverName}/suspend
  tags: Servers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-analysis-services/master/_listings/azure-analysis-services/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftanalysisservicesserversservernamesuspend-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-analysis-services/master/_listings/azure-analysis-services/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftanalysisservicesserversservernamesuspend-post-openapi.md
- name: Azure Analysis Services API Resume Server
  x-api-slug: azure-analysis-services-api
  description: Resumes operation of the specified Analysis Services server instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transform-complex-data.png
  humanURL: https://azure.microsoft.com/en-us/services/analysis-services/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.AnalysisServices/servers/{serverName}/resume
  tags: Servers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-analysis-services/master/_listings/azure-analysis-services/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftanalysisservicesserversservernameresume-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-analysis-services/master/_listings/azure-analysis-services/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftanalysisservicesserversservernameresume-post-openapi.md
- name: Azure Analysis Services API List Servers By Group
  x-api-slug: azure-analysis-services-api
  description: Gets all the Analysis Services servers for the given resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transform-complex-data.png
  humanURL: https://azure.microsoft.com/en-us/services/analysis-services/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.AnalysisServices/servers
  tags: Servers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-analysis-services/master/_listings/azure-analysis-services/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftanalysisservicesservers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-analysis-services/master/_listings/azure-analysis-services/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftanalysisservicesservers-get-openapi.md
- name: Azure Analysis Services API List Servers
  x-api-slug: azure-analysis-services-api
  description: Lists all the Analysis Services servers for the given subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transform-complex-data.png
  humanURL: https://azure.microsoft.com/en-us/services/analysis-services/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/providers/Microsoft.AnalysisServices/servers
  tags: Servers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-analysis-services/master/_listings/azure-analysis-services/subscriptionssubscriptionidprovidersmicrosoftanalysisservicesservers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-analysis-services/master/_listings/azure-analysis-services/subscriptionssubscriptionidprovidersmicrosoftanalysisservicesservers-get-openapi.md
- name: Azure Analysis Services API
  x-api-slug: azure-analysis-services-api
  description: Use Azure Resource Manager to create and deploy an Azure Analysis Services
    instance within seconds, and use backup restore to quickly move your existing
    models to Azure Analysis Services and take advantage of the scale, flexibility
    and management benefits of the cloud. Scale up, scale down, or pause the service
    and pay only for what you use.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/transform-complex-data.png
  humanURL: https://azure.microsoft.com/en-us/services/analysis-services/
  baseURL: ://management.azure.com//
  tags: Azure Analysis Services
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-analysis-services/master/_listings/azure-analysis-services/openapi.md
x-common:
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/analysis-services/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/analysis-services/
- type: x-service-level-agreements
  url: https://azure.microsoft.com/en-us/support/legal/sla/analysis-services/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/analysis-services/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---