---
name: Atlassian
x-slug: atlassian
description: Millions of users globally rely on Atlassian products every day for improving
  software development, project management, collaboration, and code quality.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
x-kinRank: "8"
x-alexaRank: "1656"
tags: Data
created: "2018-08-26"
modified: "2018-08-26"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/atlassian/apis.md
specificationVersion: "0.14"
apis:
- name: The Confluence Cloud REST API - Update attachment data
  x-api-slug: contentidchildattachmentattachmentiddata-post
  description: "Updates the binary data of an attachment, given the attachment ID,
    and \noptionally the comment and the minor edit field.\n\nThis method is essentially
    the same as [Create or update attachments](#api-content-id-child-attachment-put),
    \nexcept that it matches the attachment ID rather than the name.\n\nNote, you
    must set a `X-Atlassian-Token: nocheck` header on the request \nfor this method,
    otherwise it will be blocked. This protects against XSRF \nattacks, which is necessary
    as this method accepts multipart/form-data.\n\nThe media type 'multipart/form-data'
    is defined in [RFC 1867](https://www.ietf.org/rfc/rfc1867.txt). \nMost client
    libraries have classes that make it easier to implement \nmultipart posts, like
    the [MultiPartEntity](http://hc.apache.org/httpcomponents-client-ga/httpmime/apidocs/org/apache/http/entity/mime/MultipartEntity.html)
    \nJava class provided by Apache HTTP Components.\n\nExample: This curl command
    updates an attachment (id='att456') that is attached  \nto a piece of content
    (id='123') with a comment and `minorEdits`=true. \n\n``` bash\ncurl -D- \\\n  -u
    admin:admin \\\n  -X POST \\\n  -H \"X-Atlassian-Token: nocheck\" \\\n  -F \"file=@example.txt\"
    \\\n  -F \"minorEdit=true\" \\\n  -F \"comment=Example attachment comment\" \\\n
    \ http://myhost/rest/api/content/123/child/attachment/att456/data\n```\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
    required**: \nPermission to update the content."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/691-atlassian.jpg
  humanURL: http://atlassian.com/
  baseURL: https:////
  tags: Coding, Programming, Wiki, Issues, Code Issues, Stack Network, SaaS, Technology,
    Enterprise, API Provider, API Service Provider, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/atlassian/contentidchildattachmentattachmentiddata-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/data/master/_listings/atlassian/contentidchildattachmentattachmentiddata-post-openapi.md
x-common:
- type: x-openapi
  url: https://developer.atlassian.com/cloud/jira/platform/swagger.v3.json
- type: x-openapi
  url: https://developer.atlassian.com/cloud/confluence/swagger.v3.json
- type: x-openapi
  url: https://developer.atlassian.com/cloud/jira/software/swagger.v3.json
- type: x-openapi
  url: https://developer.atlassian.com/cloud/jira/service-desk/swagger.v3.json
- type: x-website
  url: http://atlassian.com/
- type: x-website
  url: http://www.atlassian.com
- type: x-api-gallery
  url: http://att.dev.program.api.gallery.streamdata.io
- type: x-api-stack
  url: http://atlassian.stack.network
- type: x-blog
  url: http://blogs.atlassian.com/
- type: x-crunchbase
  url: https://crunchbase.com/organization/atlassian
- type: x-crunchbase
  url: http://www.crunchbase.com/company/atlassian
- type: x-email
  url: copyright@atlassian.com
- type: x-email
  url: trademarks@atlassian.com
- type: x-email
  url: sales@atlassian.com
- type: x-email
  url: ar_enterprise@atlassian.com
- type: x-email
  url: privacy@atlassian.com
- type: x-email
  url: eudatarep@atlassian.com
- type: x-email
  url: experts@atlassian.com
- type: x-email
  url: remittance@atlassian.com
- type: x-email
  url: ap@atlassian.com
- type: x-email
  url: procurement@atlassian.com
- type: x-github
  url: https://github.com/atlassian
- type: x-privacy-policy
  url: https://www.atlassian.com/legal/privacy-policy?_ga=2.188884514.868776184.1519225620-845241124.1519225620
- type: x-twitter
  url: https://twitter.com/atlassian
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---