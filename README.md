# LinkedIn API & MCP Sandbox
This is an API sandbox for the LinkedIn API & MCP Sandbox, using an OpenAPI specification with examples, Microcks and Bruno as the sandbox interface, and this GitHub repository as the vehicle for delivering a localized sandbox.

## OpenAPI
This sandbox uses OpenAPI as the definition, providing [a complete definition of all available paths for the LinkedIn API & MCP Sandbox. The OpenAPI for this sandnbox uses examples and Microcks extensions to mock the requests and responses for each API operation, something we will iterate and expand upon with richer examples as we move forward.

## Microcks
This sandbox uses Microcks to deliver the mock API. [You just install Microcks, with the Docker extension being the easiest](https://microcks.io/documentation/guides/installation/docker-desktop-extension/), [import the OpenAPI as a service](openapi/notion-openapi.yml), and you have a mocked API for all APIs, available via REST and MCP APIs--providing a multi-protocol sandbox.

## Bruno
This sandbox [uses Bruno as the client](https://www.usebruno.com/), leveraging Bruno Collections pre-generated from the OpenAPI and Bruno environments that uses the localhost and port of Microcks to work with the mocked API. You just have to install Microcks, then open the collection provided in this repository, select the available environment, and begin calling the LinkedIn API & MCP Sandbox via the sandbox.

## Summary
This is a summary of this sandbox, breaking down the available paths, operations, and other relevant detail regarding the scope of this sandbox, designed to support development and testing against the LinkedIn API & MCP Sandbox.

- Number of Paths: 113
- Number of Operations: 148
- Number of Read Operations: 86
- Number of Write Operations: 62
- Number of Schemas: 206
- Number of Responses: 0
- Number of Parameters: 32
- Number of Examples: 72
- Number of Request Bodies: 0
- Number of Headers: 0

## OpenAPIs
These are the OpenAPIs available for the LinkedIn API & MCP Sandbox, which are made available via this sandbox API, which can be imported into Microcks and deployed as a sandbox using their mock feature.

  - [Linkedin Compliance Events Api](openapi/linkedin-compliance-events.yml)
  - [Linkedin Learning Activity Reports Api](openapi/linkedin-learning-activity-reports.yml)
  - [Linkedin Marketing Audience Insights Api](openapi/linkedin-marketing-audience-insights.yml)
  - [Linkedin Marketing Audiences Api](openapi/linkedin-marketing-audience.yml)
  - [Linkedin Marketing Campaign Management Api](openapi/linkedin-marketing-campaigns.yml)
  - [Community Management](openapi/linkedin-marketing-community.yml)
  - [Content Apis](openapi/linkedin-marketing-content.yml)
  - [Conversions Api](openapi/linkedin-marketing-conversions.yml)
  - [Lead Sync](openapi/linkedin-marketing-leads.yml)
  - [Media Planning](openapi/linkedin-marketing-media-planning.yml)
  - [Reporting & Roi](openapi/linkedin-marketing-reporting-roi.yml)
  - [Linkedin Pages Data Portability Api](openapi/linkedin-regulations-data-portability.yml)
  - [Linkedin Ads Transparency Api](openapi/linkedin-regulatory-ads-transparency.yml)
  - [Linkedin Sales Navigator Api](openapi/linkedin-sales-navigator.yml)
  - [Linkedin Job Posting Api](openapi/linkedin-talent-job-posting.yml)
  - [Linkedin Parent Application Management Api](openapi/linkedin-talent-learning-parent-application.yml)
  - [Linkedin Recruiter System Connect Api](openapi/linkedin-talent-recruiter-system-connect.yml)

## Resources
These are the resources available via the LinkedIn API & MCP Sandbox, which are made available via this sandbox API, which are applied as tags to each operation in the OpenAPI.

  - Access Control
  - Account Management
  - Ad Accounts
  - Ad Targeting Entities
  - Advertiser Transparency
  - Application Retrieval
  - Application Synchronization
  - Application Updates
  - Apply Connect Jobs
  - Audience Counts
  - Audience Insights
  - Authentication
  - Business Manager
  - Campaign Group Management
  - Campaign Management
  - Candidate Synchronization
  - Child Application Provisioning
  - Company Streaming
  - Compliance Authorization
  - Compliance Events
  - Conversion Events Streaming Workflow
  - Creative Management
  - Crm Data Validation
  - Customer Integrations
  - Data Deletion
  - Data Retrieval
  - Dmp Segments
  - Events
  - Feed Content
  - Fetch Media Plan
  - Integration Configuration
  - Job Lifecycle Management
  - Lead Generation
  - Learning Activity Reports
  - List Uploads
  - Organization Access Control
  - Organizations
  - Page Analytics
  - Profile Associations
  - Sales Access Tokens
  - Sales Analytics Export
  - Sales Contracts
  - Use Cases > B2b Templates > Conversions Deep Dive
  - Use Cases > Conversation Ad > Sponsored Conversations
  - Use Cases > Conversation Ad > Sponsored Message Contents
  - Use Cases > Creatives
  - Use Cases > Document Ad
  - Use Cases > Image Ad
  - Use Cases > Inmail Content
  - Use Cases > Organization Access Controls
  - Use Cases > Organization Followers
  - Use Cases > Organization Lookup > Organization Brands
  - Use Cases > Organization Lookup > Organizations
  - Use Cases > Posts
  - Use Cases > Social Actions Notifications > Organization Social Actions Notifications - Pull Workflow
  - Use Cases > Social Actions Notifications > Organization Social Actions Notifications - Push Workflow
  - Use Cases > Sponsored
  - Use Cases > Spotlight Ad
  - Use Cases > Statistics Apis > Organization Follower Statistics
  - Use Cases > Statistics Apis > Organization Page Statistics
  - Use Cases > Statistics Apis > Organization Share Statistics
  - Use Cases > Video Ad
  - User Access
  - User Streaming

## Operations
These are all of the available operations in this sandbox, providing a complete view of what you can do within this sandbox using the mocked LinkedIn API & MCP Sandbox.

  - 10. Stream Multiple Conversion Events To The Conversion Rule
  - 2. Create A Share With A Company Mention
  - 2. Get The User's Sponsored Accounts (ad Accounts)
  - 2. Retrieve Authenticated User's Sponsored Ad Accounts
  - 3. Create A Subscription Request
  - 3. Retrieve Notifications For The Authenticated Member's Organization
  - 4. Fetch Existing Conversion Rules For Capi In The Selected Ad Account
  - 4. Validate The User's Organization Role
  - 5. Get Forms For The Chosen Sponsored Account
  - 5. Retrieve Subscription By Key
  - 6. Create A New Conversion Rule
  - 6. Remove A Subscription
  - 7. Fetch Active Campaigns
  - 8. Associate Campaigns To Conversion Rule
  - 8. Schedule Periodic Form Response (lead) Pulls
  - 8. Subscribe For Lead Notification Webhooks
  - 9. Fetch Full Lead Data After A Lead Notification Is Received
  - Archive Campaign
  - Attach Uploaded List To Dmp Segment
  - Batch Fetch Profile Associations
  - Batch Get On Administered Organization Brands
  - Batch Get On Non-administered Organization Brands
  - Batch Get Inmail Content
  - Batch Get Organizations
  - Batch Create Sponsored Message Content
  - Batch Delete Sponsored Message Content
  - Batch Get Sponsored Message Content
  - Batch Update Sponsored Message Content
  - Check Job Posting Task Status
  - Check Member Regulation Status
  - Conversions By Member Company Size
  - Create Ad Account User
  - Create Crm Data Validation Export Job
  - Create Creative
  - Create Dmp Segment
  - Create Inmail Content
  - Create New Sales Analytics Export Job
  - Create Or Update Apply Connect Job Posting
  - Create Resume Upload Url
  - Create Test Ad Account
  - Create A Dynamic Spotlight Ad
  - Create A Sponsored Conversation
  - Create Document Content
  - Delete Ad Account User
  - Delete Campaign Group
  - Delete Entity Acl
  - Delete Multiple Campaign Groups
  - Delete Synced Applications
  - Delete Synced Candidates
  - Delete A Creative
  - Delete A Dynamic Spotlight Ad
  - Delete A Post
  - Fetch Ad Account By Id
  - Fetch Ad Account User
  - Fetch Audience Insights By Targeting Criteria
  - Fetch Authenticated User Ad Accounts
  - Fetch Authenticated User Organization Roles
  - Fetch Campaign By Id
  - Fetch Campaign Group By Id
  - Fetch Profile Association By Key
  - Fetch Sales Analytics Export Job By Id
  - Fetch Multiple Image Content
  - Fetch Multiple Document Content
  - Find Administered Organization Brands By Parent Org
  - Find All Contracts Where User Has Active Seat
  - Find Non-administered Organization
  - Find Organization Access Control
  - Forecast Avg Lifetime Frequency
  - Get Ad Targeting Entities Using Typeahead Search
  - Get Advertiser Transparency Data
  - Get Audience Count By Targeting Criteria
  - Get Bing Geo Locations Using Search Typeahead
  - Get Business Manager Account Relationships
  - Get Crm Data Validation Export Job Status
  - Get Child Application
  - Get Comments
  - Get Customer Ats Integration Details
  - Get Customer Application Access Token
  - Get Events
  - Get Exported Candidate Profile
  - Get Image Content
  - Get Inmail Content
  - Get Integration Status Change Notification
  - Get Lead Generation Responses
  - Get Learning Activity Reports
  - Get List Of Available Ad Targeting Facets
  - Get Multiple Sponsored Conversations
  - Get Multiple Videos
  - Get Organization
  - Get Organization Acls
  - Get Page Content Analytics
  - Get Posts
  - Get Posts By Urn
  - Get Reactions
  - Get Sponsored Message Content
  - Get A  Sponsored Creative
  - Get A Dynamic Spotlight Ad
  - Get A Sponsored Conversation
  - Get A List Of Available Ad Targeting Facets
  - Get A Single Image
  - Get A Single Document
  - Get A Single Video
  - Get Multiple Documents
  - Initialize Document Upload
  - Initialize Image Upload
  - Initialize Video Upload
  - Lifetime Page Statistics
  - Lookup By Organization Primary Type
  - Monitor Dmp Segment Status
  - Opt In Member For Compliance Monitoring
  - Opt Out Member From Compliance Monitoring
  - Provision Child Application
  - Retrieve Candidate Matches
  - Retrieve Compliance Events For Regulated Member
  - Retrieve Entity Acl
  - Retrieve Organization Follower Count
  - Retrieve Recruiter Seatholders
  - Retrieve Sales Access Token For Authenticated Iframe Sessions
  - Retrieve User Ad Accounts
  - Retrieve An Administered Organization Brand
  - Search Ad Accounts By Type
  - Search By Keyword
  - Search By Vanity Url
  - Search Campaign Groups
  - Search Campaigns
  - Search For Creative
  - Send Test Inmail
  - Stream Company Data To Segment
  - Stream User Data To Segment
  - Sync Candidates To Linkedin
  - Sync Job Applications
  - Time Bound Share Statistics
  - Time-bound Follower Statistics
  - Update Ad Account Name
  - Update Ad Account User
  - Update Campaign Group
  - Update Customer Ats Integration
  - Update Customer Ats Integrations
  - Update Inmail Content
  - Update Oauth 2.0 Callback Urls For Child Application
  - Update Sponsored Message Content
  - Update A Creative
  - Update A Dynamic Spotlight Ad
  - Update A Post
  - Update A Sponsored Conversation
  - Upload The Document File (select A Document File In The Body For Postman To Use)
  - Upsert Entity Acl
  - [push] Delete A Registered Webhook By Id

## Backstage
We provide a Backstage software catalog entity for the LinkedIn API & MCP Sandbox, allowing this sandbox to be registered with any catalog, making it discoverable by team and across an organization--allowing anyone to fork and deploy locally within the enterprise.

  - [Linkedin Compliance Events API](backstage/linkedin-compliance-events.yml)
  - [Linkedin Learning Activity Reports API](backstage/linkedin-learning-activity-reports.yml)
  - [Linkedin Marketing Audience Insights API](backstage/linkedin-marketing-audience-insights.yml)
  - [Linkedin Marketing Audiences API](backstage/linkedin-marketing-audience.yml)
  - [Linkedin Marketing Campaign Management API](backstage/linkedin-marketing-campaigns.yml)
  - [Community Management](backstage/linkedin-marketing-community.yml)
  - [Content APIs](backstage/linkedin-marketing-content.yml)
  - [Conversions API](backstage/linkedin-marketing-conversions.yml)
  - [Lead Sync](backstage/linkedin-marketing-leads.yml)
  - [Media Planning](backstage/linkedin-marketing-media-planning.yml)
  - [Reporting & Roi](backstage/linkedin-marketing-reporting-roi.yml)
  - [Linkedin Pages Data Portability API](backstage/linkedin-regulations-data-portability.yml)
  - [Linkedin Ads Transparency API](backstage/linkedin-regulatory-ads-transparency.yml)
  - [Linkedin Sales Navigator API](backstage/linkedin-sales-navigator.yml)
  - [Linkedin Job Posting API](backstage/linkedin-talent-job-posting.yml)
  - [Linkedin Parent Application Management API](backstage/linkedin-talent-learning-parent-application.yml)
  - [Linkedin Recruiter System Connect API](backstage/linkedin-talent-recruiter-system-connect.yml)
## Support
Please provide any questions or feedback via GitHub issues, or just email kinlane@naftiko.io with feedback. The goal is to keep iterating upon this sandbox using existing OpenAPI, Microcks, and Bruno features, offering value out of the box via this forkable third-party LinkedIn API & MCP Sandbox.

