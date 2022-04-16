| Name                                                         | Catagory              | Meraki SM          | Jamf                                                                      | Kandji                                                                                                  | Mosyle                                                                       |
|--------------------------------------------------------------|-----------------------|--------------------|---------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------|
| Agent/local binary                                           | Agent                 | :white_check_mark: | :white_check_mark:                                                        | :white_check_mark:                                                                                      | :white_check_mark:                                                           |
| Slack Integration                                            | Alerts                | :x:                | :x:                                                                       | :white_check_mark:                                                                                      | :x:                                                                          |
| Email Alerts - Requires additional infrastructure            | Alerts                | :x:                | :grey_exclamation: Needs SMTP relay server setup                          | :x:                                                                                                     | :x:                                                                          |
| Outgoing Webhook                                             | Alerts                | :x:                | :white_check_mark: JSON format not natively configured for Slack or Teams | :x:                                                                                                     | :x:                                                                          |
| Outgoing Webhook - Requires additional infra for Slack       | Alerts                | :x:                | :white_check_mark:                                                        | :x:                                                                                                     | :x:                                                                          |
| Email Alerts - Native                                        | Alerts                | :white_check_mark: | :x:                                                                       | :white_check_mark:                                                                                      | :white_check_mark:                                                           |
| In-House AV                                                  | Antivirus             | :x:                | :white_check_mark: Additional cost                                        | :x:                                                                                                     | :white_check_mark: Included with Fuse                                        |
| Self Service App - macOS                                     | App Delivery          | :x:                | :white_check_mark:                                                        | :white_check_mark:                                                                                      | :white_check_mark:                                                           |
| Custom Apps - Content Distribution                           | App Delivery          | :white_check_mark: | :white_check_mark:                                                        | :x:                                                                                                     | :white_check_mark:                                                           |
| ABM Apps (fka VPP)                                           | App Delivery          | :white_check_mark: | :white_check_mark:                                                        | :white_check_mark:                                                                                      | :white_check_mark:                                                           |
| App Configure - app settings (force SSO, etc)                | App Delivery          | :white_check_mark: | :white_check_mark:                                                        | :white_check_mark:                                                                                      | :white_check_mark:                                                           |
| Custom Apps                                                  | App Delivery          | :white_check_mark: | :white_check_mark:                                                        | :grey_exclamation: Custom apps need external blob storage                                               | :white_check_mark:                                                           |
| Self Service App - iOS                                       | App Delivery          | :white_check_mark: | :white_check_mark:                                                        | :white_check_mark:                                                                                      | :white_check_mark:                                                           |
| App Updates - macOS - Notifications without 3rd party script | App Update            | :x:                | :x: Use Nudge app                                                         | :white_check_mark:                                                                                      | :white_check_mark:                                                           |
| App Updates - iOS - Forced                                   | App Update            | :x:                | :white_check_mark:                                                        | :white_check_mark:                                                                                      | :white_check_mark:                                                           |
| App Updates - iOS - Self Service                             | App Update            | :x:                | :white_check_mark:                                                        | :white_check_mark:                                                                                      | :white_check_mark:                                                           |
| App Updates - macOS - Forced                                 | App Update            | :x:                | :white_check_mark:                                                        | :white_check_mark:                                                                                      | :white_check_mark:                                                           |
| App Updates - macOS - Self Service                           | App Update            | :x:                | :white_check_mark:                                                        | :white_check_mark:                                                                                      | :white_check_mark:                                                           |
| App Updates - iOS - Scheduled or Maintenance Window          | App Update            | :white_check_mark: | :white_check_mark:                                                        | :white_check_mark:                                                                                      | :white_check_mark:                                                           |
| App Updates - macOS - Scheduled or Maintenance Window        | App Update            | :white_check_mark: | :white_check_mark:                                                        | :white_check_mark:                                                                                      | :white_check_mark:                                                           |
| API                                                          | Automation            | :white_check_mark: | :white_check_mark:                                                        | :white_check_mark:                                                                                      | :white_check_mark: Unconventional setup - all PUT methods; Limited Endpoints |
| Offline mode (cached enforcement)                            | Configuration         | :x:                | :x:                                                                       | :white_check_mark: Keeps local cache of configs for continuous enforcement while offline                | :x:                                                                          |
| Pre-Built Configs/Policies                                   | Configuration         | :x:                | :x:                                                                       | :white_check_mark:                                                                                      | :white_check_mark:                                                           |
| Device Groups - Attribute-based automatic membership         | Configuration         | :x:                | :white_check_mark:                                                        | :x:                                                                                                     | :white_check_mark:                                                           |
| Shared iPad support                                          | Configuration         | :x:                | :white_check_mark:                                                        | :white_check_mark:                                                                                      | :x:                                                                          |
| App Lock - iPad single mode app                              | Configuration         | :x:                | :white_check_mark:                                                        | :white_check_mark:                                                                                      | :white_check_mark:                                                           |
| Custom Scripts (without pkg workaround)                      | Configuration         | :x:                | :white_check_mark:                                                        | :white_check_mark:                                                                                      | :white_check_mark:                                                           |
| Remediate Configurations                                     | Configuration         | :x:                | :white_check_mark:                                                        | :white_check_mark:                                                                                      | :white_check_mark:                                                           |
| App Block List                                               | Configuration         | :white_check_mark: | :white_check_mark:                                                        | :white_check_mark:                                                                                      | :white_check_mark:                                                           |
| Configuration Profiles                                       | Configuration         | :white_check_mark: | :white_check_mark:                                                        | :white_check_mark:                                                                                      | :white_check_mark:                                                           |
| Supervise Device                                             | configuration         | :white_check_mark: | :white_check_mark:                                                        | :white_check_mark:                                                                                      | :white_check_mark:                                                           |
| Role-Based Apps, Controls, Automations (Blueprints)          | Enrollment            | :x:                | :x:                                                                       | :white_check_mark:                                                                                      | :x:                                                                          |
| ABM Integration                                              | Enrollment            | :white_check_mark: | :white_check_mark:                                                        | :white_check_mark:                                                                                      | :white_check_mark:                                                           |
| DEP/ADE                                                      | Enrollment            | :white_check_mark: | :white_check_mark:                                                        | :white_check_mark:                                                                                      | :white_check_mark:                                                           |
| Zero-Touch Deployment                                        | Enrollment            | :white_check_mark: | :white_check_mark:                                                        | :white_check_mark:                                                                                      | :white_check_mark:                                                           |
| Directory Integration - Okta                                 | Identity              | :x:                | :x:                                                                       | :x:                                                                                                     | :white_check_mark:                                                           |
| Directory Integration - Google Workspace                     | Identity              | :x:                | :x:                                                                       | :white_check_mark:                                                                                      | :white_check_mark:                                                           |
| Admin Portal - SSO Login                                     | Identity              | :x:                | :white_check_mark:                                                        | :white_check_mark:                                                                                      | :white_check_mark:                                                           |
| macOS - Password Sync IdP (Okta)<->Local User Account        | Identity              | :x:                | :white_check_mark:                                                        | :white_check_mark:                                                                                      | :white_check_mark:                                                           |
| macOS - SSO Login                                            | Identity              | :x:                | :white_check_mark:                                                        | :white_check_mark:                                                                                      | :white_check_mark:                                                           |
| Extension Attributes or equivalent                           | Inventory             | :x:                | :white_check_mark:                                                        | :white_check_mark:                                                                                      | :white_check_mark:                                                           |
| macOS - Migration agent from old MDM                         | Migration             | :x:                | :white_check_mark:                                                        | :white_check_mark:                                                                                      | :x:                                                                          |
| OS Updates - iOS/mobile                                      | OS Update             | :x:                | :x:                                                                       | :white_check_mark:                                                                                      | :x:                                                                          |
| OS Updates - mac                                             | OS Update             | :x:                | :x:                                                                       | :white_check_mark:                                                                                      | :x:                                                                          |
| OS Updates - mac - Managed (pre-configured)                  | OS Update             | :x:                | :x:                                                                       | :white_check_mark:                                                                                      | :x:                                                                          |
| AppleTV (tvOS) support                                       | Other                 | :white_check_mark: | :white_check_mark:                                                        | :white_check_mark:                                                                                      | :white_check_mark:                                                           |
| Auditor access                                               | RBAC - Roles          | :x:                | :white_check_mark:                                                        | :white_check_mark:                                                                                      | :white_check_mark:                                                           |
| Reporting - Built-In                                         | Reporting             | :x:                | :white_check_mark:                                                        | :x:                                                                                                     | :white_check_mark:                                                           |
| Reporting - Custom                                           | Reporting             | :x:                | :white_check_mark:                                                        | :x:                                                                                                     | :white_check_mark:                                                           |
| Built-In - Local Admin Password Solution (LAPS)              | Security & Compliance | :x:                | :x: have to use macOSLAPS                                                 | :x: pw can be manually changed, but no way to retrieve pw without custom script to write pw to log file | :white_check_mark:                                                           |
| Baselines (Hardening) Pre-built configs                      | Security & Compliance | :x:                | :white_check_mark:                                                        | :white_check_mark:                                                                                      | :white_check_mark:                                                           |
| Compliance Control                                           | Security & Compliance | :x:                | :white_check_mark:                                                        | :white_check_mark:                                                                                      | :white_check_mark:                                                           |
| Security Templates                                           | Security & Compliance | :x:                | :white_check_mark:                                                        | :white_check_mark:                                                                                      | :white_check_mark:                                                           |