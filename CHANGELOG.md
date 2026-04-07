# Changelog - Week of April 06, 2026

## Recent Releases

### v1.462.1
Released: 2026-04-04T00:39:13Z



---

### v1.462.0
Released: 2026-04-03T21:35:46Z

## What's Changed

 *  Updated Autocomplete to new location

 *  Removed document validation functionality

 *  Added support for overriding patient status

 *  Extra support for duo/trio insurance testing

 *  Extra support for creating referrals



---

### v1.461.0
Released: 2026-04-02T22:48:07Z

## What's Changed

 * Insurance duo/trio recommended badge 

 * Removed review page 

 * Updated Textarea component

 * Update backend dependencies

 * Fix for PWN workflows not being found when appointments are cancelled  



---

### v1.460.0
Released: 2026-04-01T23:58:53Z

## What's Changed

 * Hharris/pro 9724 prime dragon autocomplete 

 * Add RadioGroup component to prime-dragon 

 * Migrate Checkbox component to prime-dragon 

 *  ProductOfferingStateService — Write Path 

 *  ProductOfferingStateService — Read Path 

 *  API endpoint — GET /v1/product-offerings/patients/{patient_id}/offering-state 

 *  Clear user data on sign out and more symptom assessment gate handling 

 * Re-enable duo-trio insurance page  

 * More backend/frontend updates 

 * Update Focus Styling 

 *  Event wiring, Django integration, E2E tests 



---

### v1.459.0
Released: 2026-04-01T18:09:22Z

## What's Changed

 *  Fixed issue with logged in email notification

 *  Removed facial file upload from review page

 *  Improved offerings for biopharma programs



---

### v1.458.0
Released: 2026-03-31T20:08:40Z

## What's Changed

 * Improved Button sizing

 * Changed color of link for physicians 

 * Improved offerings for insurace program0

 * Improved testing

 * Updated upstream dependencies

 * Updated progress bar to match brand



---

### v1.457.0
Released: 2026-03-30T21:48:15Z

## What's Changed

 * Stability improvments

 * Improved file upload

 * Improved conversation for rare genetic diseases



---


---

# Changelog - Week of March 30, 2026

## Recent Releases

### v1.456.2
Released: 2026-03-28T01:17:05Z

## What's Changed

 * Update Iterable variables
 * Update physician search

---

### v1.456.1
Released: 2026-03-28T00:09:44Z

## What's Changed

 *  Hotfix for PWN schedule event 

---

### v1.456.0
Released: 2026-03-27T22:13:16Z

## What's Changed

 * Eligibility scaffolding and updates
 * New E2E feature integration updates
 * Fix Mobile get started page
 * Add datetime utils, timezone aware scheduling event data
 * update intake flow header for mobile
 * Intake updates for button + heading sizing
 * Replace more instances of old user/me call

---

### v1.455.0
Released: 2026-03-26T21:03:28Z

## What's Changed

 * Use navigate instead of redirect 
 * Fixing duplicated fn in oaklib
 * Internal oaklib package updates
 * Format "get started" page
 * Fix bug where delting one diagnosis deletes all in selection
 * Update text component
 * Button updates, styling fixes
 * Disable screenshot on testing. Might fix.

---

### v1.454.1
Released: 2026-03-25T16:37:38Z

## What's Changed

 * Hotfix update BROAD_VCF_FILE_NAME 

---

### v1.454.0
Released: 2026-03-25T00:26:02Z

## What's Changed

 * Add badge component 
 * Update genetic history copy

---

### v1.453.0
Released: 2026-03-24T20:59:35Z

## What's Changed

 * Update e2e to match current frontend
 * Updating some styling on file upload page
 * Removing has_verified_genetic_test_history from patient type /me api
 * Insurance pathway updates
 * Add another React dep for query to avoid race condition on conversation gate

---

### v1.452.0
Released: 2026-03-24T17:54:29Z

## What's Changed

 * Doc Val prompt improvements 
 *  Hook for post submit navigation


---

### v1.451.0
Released: 2026-03-24T16:31:40Z

## What's Changed

 *  After review go to dashboard if has valid genetic doc 
 *  Fixing genetic test file upload page showing skip instead of continue
 * Fix missing / incorrectly styled back buttons
 *  Flake8 GH action
 *  Better organizing self reported tests in me api
 * Remove conversation page blocker

---

### v1.450.0
Released: 2026-03-23T16:31:21Z

## What's Changed

 *  Add flake8 to precommit + config 
 * chore(deps): bump docker/build-push-action from 6 to 7
 * chore(deps): bump aquasecurity/trivy-action from 0.34.1 to 0.35.0
 * chore(deps): bump codecov/codecov-action from 5.5.2 to 5.5.3
 *  /me api now includes flag if patient has valid genetic doc
 * chore(deps): bump pnpm/action-setup from 4 to 5

---

### v1.449.0
Released: 2026-03-19T21:32:54Z

## What's Changed

 * Check for informed consent 
 *  Update patient consent
 * chore(deps): bump docker/metadata-action from 5 to 6
 * chore(deps): bump actions/setup-node from 6.2.0 to 6.3.0
 * chore(deps): bump dopplerhq/cli-action from 3 to 4
 * chore(deps): bump docker/setup-buildx-action from 3.12.0 to 4.0.0
 *  Product offerings scaffold & core types
 * Remove NPI number requirement, disable pdf tampering check
 * Update tests for conversation respond, E2E
 * fix: validate person name before creating PWN insurance order

---

### v1.448.0
Released: 2026-03-18T21:06:16Z

## What's Changed

 * Remove multi-patient feature flag frontend 
 *  updating InterventionHistoryFreeTextQuestion copy
 *  Fix insurance import issue



---

### v1.447.0
Released: 2026-03-18T19:49:14Z

## What's Changed

 * Prime Dragon button sizes 
 * Add muscle weakness to hallmark phenotypes
 * style: Update insurance consent alert copy and design to match mockups
 *  Adding support for soft launch milestone
 *  Filter rare diseases from chat messages
 * Fix CNV status for Broad orders
 *  Fixing import bug
 *  adding set coockie to dev/staging intake page
 *  Fix pdf library regression, rollback manual error handling
 * White status card backgrounds
 *  Removing identity and incentive feature flags
 *  Chatpg condition filter list for aprah soft launch
 *  Mark apra soft launch eligible for payment
 *  Ensuring base disease ids are also included + adding log content
 * Add paid research copy to get started page
 * Allow Images for Document Validation

---


---

# Changelog - Week of March 16, 2026

## Recent Releases

### v1.446.0
Released: 2026-03-12T23:27:23Z

## What's Changed

 *  Internal changes



---

### v1.445.1
Released: 2026-03-12T01:54:34Z

## What's Changed

 * UI hotfix for infinite load on duo / trio testing


---

### v1.445.0
Released: 2026-03-11T21:33:43Z

## What's Changed

 * Fix Sequencing Service bug

 * API updates

 * Database changes

 * User feedback on file deletion



---

### v1.444.2
Released: 2026-03-11T00:20:11Z

## What's Changed

 * UI updates

 * API dependency changes



---

### v1.444.1
Released: 2026-03-10T23:45:15Z

 * Internal Updates

---

### v1.444.0
Released: 2026-03-10T16:43:16Z

## What's Changed

 * Database updates

 * Internal API changes



---


---

# Changelog - Week of March 09, 2026

## Recent Releases

### v1.443.1
Released: 2026-03-06T20:48:43Z

 * Bug fixes

---

### v1.443.0
Released: 2026-03-04T19:52:03Z

## What's Changed

 * Internal tooling updates

---

### v1.442.0
Released: 2026-03-04T00:18:46Z

## What's Changed 

 * Removing legacy code 

 * Reducing size of our docker builds 

 * Update dependency packages to address external vulnerabilities 

 * Fixing bug in PDF parsing 

 * Add keyboard navigation to dashboard sidebar 

---

### v1.441.0
Released: 2026-03-02T18:52:11Z

## What's Changed

 * Updates to front-end to follow Web Content Accessibility Guidelines (WCAG) standard  

 * Dependency updates

 * Internal tooling updates 

---

### v1.440.0
Released: 2026-02-28T01:40:54Z

## What's Changed

 * Internal Update 

---

### v1.439.0
Released: 2026-02-28T00:18:59Z

## What's Changed

 * Add get started intro page at the begining of intake 

 * Fix user state not getting resolved properly 

 * Update dependencies to address external vulnerabilities 

 * update insurance completion pricing experiment UI 


---

### v1.438.1
Released: 2026-02-27T07:19:17Z

 * Internal updates

---

### v1.438.0
Released: 2026-02-26T22:58:17Z

## What's Changed

 * Adding UI component for Document Validation status card 

 * Fixing bug where genetic history was sometimes deleted when new changes came in

 * Fix state management in insurance to prepare for multi-patient per user support  

 * Fix sequencing service bug



---

### v1.437.0
Released: 2026-02-26T00:38:07Z

## What's Changed

 * Update dependencies to address external vulnerabilities    

 * Backend improvements to support Document Validation 


---

### v1.436.0
Released: 2026-02-25T00:00:29Z

## What's Changed

 * Updates to front-end to follow Web Content Accessibility Guidelines (WCAG) standard 

 * Bug fix to get the correct patient now that a single user can have multiple patients 

 * Update dependencies to address external vulnerabilities  


---

### v1.434.0
Released: 2026-02-23T19:37:24Z

## What's Changed

 * Updates to front-end to follow Web Content Accessibility Guidelines (WCAG) standard

 * Small UI updates for the identity verification feature

 * Improving address autocommplete styling   



---


---

# Changelog - Week of February 23, 2026

## Recent Releases

### v1.433.0
Released: 2026-02-20T21:11:24Z

## What's Changed

 * Updating hydra tooling to better support async
 * Updates to identity verification service
 * Incentive updates
 * Bugfixes for patient deletes
 * New address lookup component

---

### v1.432.0
Released: 2026-02-19T23:50:59Z

## What's Changed

 * Component UI/UX update for new questions and accessibility
 * Removing trailing slash from identity forwarding symptom-checker api 
 * New question API integration
 * New events
 * Bugfixes for identity and add patient features
 * Sequencing updates
 * chore(deps): bump aquasecurity/trivy-action from 0.33.1 to 0.34.0 
 * Bugfix for hallmark phenotypes
 * Collapsible dashboard menu on mobile 

---

### v1.431.2
Released: 2026-02-19T21:54:44Z

- Removing trailing slash from identity forwarding symptom-checker api — @probably-thomas  
- Refactoring and improving errors in identity service — @probably-thomas  
-  Identity fix ups 1 — @probably-thomas  
-  Identity loading button — @probably-thomas  


---

### v1.431.1
Released: 2026-02-18T04:17:57Z



---

### v1.431.0
Released: 2026-02-17T21:31:08Z

## What's Changed

 *  Identity additional error handling 

 *  Identity account page section 

 *  Adding test data to test stripe identity in dev/staging 

 *  Fix for patient age in chat summary 

---

### v1.430.1
Released: 2026-02-14T00:45:22Z

## What's Changed

 * Update docker actions 



---

### v1.430.0
Released: 2026-02-13T22:45:24Z

## What's Changed

 * Event handling upgrades 
 * Incentives analytics 
 * Incentive payment history updates
 * New component updates

---

### v1.429.0
Released: 2026-02-13T17:19:12Z

## What's Changed

 * UX/UI Design updates
 * Adding new model for inentive payments 

---

### v1.428.0
Released: 2026-02-12T17:16:23Z

## What's Changed

 * Updates to add multiple patients 
 * Update E2E testing
 * Frontend query logic updates
 * User file upload event handling 
 * Login fixes
 *  Identity metrics 
 * Sentry and internal tooling updates
 * Adjust settings for temporal tasks 
 *  Adding identity verification section component for account page 
 *  Fix unexpected `None` on EHR 
 * Incentives integration updates
 * Async bugfixes

## New Contributors

 * @eng-probably-genetic made their first contribution in https://github.com/Probably-Genetic/Phenotyper/pull/3964


---

# Changelog - Week of February 09, 2026

## Recent Releases

### v1.427.1
Released: 2026-02-05T17:28:34Z



---

### v1.427.0
Released: 2026-02-04T22:14:33Z

## What's Changed

 * Fix insurance tracking 

 * Fix Sentry sourcemaps, optimize bundle sizes 

 *  Add patient to existing user backend 

 *  Update dependencies

 *  Sentry testing updates

 *  Fix node tooling

 *  Reverting front-end update to fix some styling issues



---

### v1.426.0
Released: 2026-02-03T17:13:39Z

## What's Changed

 *  1-many patient switcher on dashboard 


---

### v1.425.0
Released: 2026-02-03T01:22:43Z

## What's Changed

 * Identity webhook in progress status 

 * fix:  scroll to top on insurance interstitial 

 *  Updating copy of identity validation cards 

 *  Updating urllib3 

 *  Bugfix: NPC Smart Filter not firing 



---


---

# Changelog - Week of February 02, 2026

## Recent Releases

### v1.424.0
Released: 2026-01-31T02:51:19Z

## What's Changed

 * Internal tooling updates
 * Front-end updates to prepare for multi patient per user support
 * add insurance interstitial that conditionally appears after new user complete the intake processes

---

### v1.423.2
Released: 2026-01-30T19:02:37Z

## What's Changed

 *  Disabling stripe in front-end since it isn't used yet and is causing some errors to pop-up 

---

### v1.423.1
Released: 2026-01-30T17:17:37Z

## What's Changed

 * Fix bug in EHR search 

---

### v1.423.0
Released: 2026-01-29T19:47:50Z

## What's Changed

 *  Adding support for stripe identity validation in front-end 
 *  Adding support for new disease program 

---

### v1.422.0
Released: 2026-01-28T18:59:16Z

## What's Changed

 * Fix PWN management command 

 *  Adding new models and apis for creating identity verification 
 *  Remove panel analysis from WGS tests 
 *  Backend changes to support a user being able to manage multiple patients  

---

### v1.421.0
Released: 2026-01-27T18:00:46Z

## What's Changed

 * Switch to use pnpm 
 * Update internal tooling
 * Fix bug with supplying to proper shipping address to Broad institute
 * Fix bugs in insurance workflow  

---

### v1.420.0
Released: 2026-01-26T20:10:36Z

## What's Changed

 * Internal Updates and tooling bug fixes
 * Fixing changelog ask time to be 9am PST not UTC  

---


---

# Changelog - Week of January 26, 2026

## Recent Releases

### v1.419.0
Released: 2026-01-24T08:25:49Z

## What's Changed

 * Internal updates


---

### v1.418.0
Released: 2026-01-23T23:30:35Z

## What's Changed

 * Backend integration updates

 * Internal updates

 * UI bug fixes


---

### v1.417.3
Released: 2026-01-23T00:39:11Z

## What's Changed

 * Internal updates


---

### v1.417.2
Released: 2026-01-22T23:32:11Z

## What's Changed

 * Internal updates


---

### v1.417.1
Released: 2026-01-22T21:13:59Z

## What's Changed

 * Internal updates


---

### v1.417.0
Released: 2026-01-21T23:34:38Z

## What's Changed

 * UI updates


---

### v1.416.0
Released: 2026-01-21T19:46:41Z

## What's Changed

 * Internal updates

 * Rollback UI changes

 * UI updates

 * Update package versions



---

### v1.415.1
Released: 2026-01-21T06:28:47Z

## What's Changed

 * Internal updates


---

### v1.415.0
Released: 2026-01-16T21:55:35Z

## What's Changed

 * Bug fixes

 * Remove depricated services

 * UI updates


---

### v1.414.1
Released: 2026-01-14T19:57:33Z

## What's Changed

 * Internal updates


---

### v1.414.0
Released: 2026-01-13T22:45:02Z

## What's Changed

 * Additional metrics

 * Backend updates

 * Upgrade internal tooling


---


---

# Changelog - Week of January 12, 2026

## Recent Releases

### v1.413.2
Released: 2026-01-10T05:00:01Z

## What's Changed

 * Insurance updates



---

### v1.413.1
Released: 2026-01-10T03:53:53Z

## What's Changed

 * Insurance updates



---

### v1.413.0
Released: 2026-01-09T22:59:09Z

## What's Changed

 * Insurance updates



---

### v1.412.0
Released: 2026-01-09T21:17:11Z

## What's Changed

 * Broad integration updates

 * Dashboard Status Cards 
 
 * Update Dockerfiles

 * Update logic for PWN contact scheduled 



---

### v1.411.4
Released: 2026-01-09T05:20:16Z

## What's Changed

 * Internal updates


---

### v1.411.3
Released: 2026-01-09T01:42:25Z

## What's Changed

 * Internal updates


---

### v1.411.2
Released: 2026-01-08T22:54:14Z

## What's Changed

 * Resolve vulnerabilities

 * UI bug fixes and enhancements

 * Update insurance checks

 * Docker changes


---

### v1.411.1
Released: 2026-01-07T06:04:12Z

## What's Changed

 * Internal updates


---

### v1.411.0
Released: 2026-01-06T18:06:52Z

## What's Changed

 *  Disabling legacy service 



---

### v1.410.0
Released: 2026-01-06T00:31:54Z

## What's Changed

 * CI/CD Updates

 * Bug Fixes

 * Update packages

 * Backend integration updates


---

# Changelog - Week of January 05, 2026

## Recent Releases

### v1.409.2
Released: 2026-01-03T05:49:02Z

 * Fix bug in accepting form consent feature

---

### v1.409.1
Released: 2025-12-25T01:27:43Z

## What's Changed

 *  Release dynamic file upload feature 



---

### v1.409.0
Released: 2025-12-24T23:33:53Z

## What's Changed

 *  Preparing for dynamic file upload request feature release 

 *  Improving dynamic file upload request text wording

 *  Add reply-to email to Docuseal submission creation



---

### v1.408.0
Released: 2025-12-23T17:45:53Z

## What's Changed

 *  Update pre & post genetic counseling scheduling links 


---

### v1.407.1
Released: 2025-12-23T02:00:21Z

## What's Changed

 * Fxing upload file bug 



---

### v1.407.0
Released: 2025-12-22T22:09:02Z

## What's Changed

 *  Updating date of birth input  

 *  Updating malware scanning for uploaded files 

 *  Update Metabase image 

 *  Patient Consent Frontend 

 *  Preparing for dynamic file upload request release



---


---

# Changelog - Week of December 15, 2025

## Recent Releases

### v1.406.0
Released: 2025-12-12T22:23:10Z

## What's Changed

 *  Internal changes

 *  Migrate functionality to new backend

 *  Tooling updates for compliance

 *  UI enhancements to support new functionality


---

### v1.405.2
Released: 2025-12-12T04:41:33Z

 * Internal changes


---

### v1.405.1
Released: 2025-12-12T03:33:33Z

 * Internal changes


---

### v1.405.0
Released: 2025-12-11T01:26:22Z

## What's Changed

 * Adding functionality to new backend

 * Backend versioning changes

 * Internal changes


---

### v1.404.0
Released: 2025-12-09T23:29:16Z

## What's Changed

 * Internal changes

 * Improved error tracking

 * Linting updates
   
 * Migrate functionality to new backend

 * Package versioning for compliance

 * Request forwarding for inter-service communication

 * Setup integrations in new backend
  
 * Trainer enhancements

 * UI bug fixes




---


---

# Changelog - Week of December 08, 2025

## Recent Releases

### v1.403.0
Released: null

## What's Changed

 * Updating Frontend tests in CI/CD 

 * Internal Updates

---

### v1.402.1
Released: 2025-12-06T00:49:41Z

 * Interal updates

---

### v1.402.0
Released: 2025-12-04T21:33:30Z

## What's Changed

 * Internal updates

 * Fixing typo in ChatPG Chat question 


---

### v1.401.0
Released: 2025-12-04T19:43:58Z

## What's Changed

 *  Updating Alpha Mannosidosis predictor logic to include developmental delay

---

### v1.400.0
Released: 2025-12-04T17:10:58Z

## What's Changed

 * Updating packages and running audit fix for front-end 

 * Fix e2e test 

 * Adding new internal APIs

 * Fix for medicare/medicaid getting required for trainer intake



---

### v1.399.2
Released: 2025-12-04T01:50:40Z

 * Internal updates


---

### v1.399.1
Released: 2025-12-02T23:07:48Z

## What's Changed

 *  Update intake form text 

---

### v1.399.0
Released: 2025-12-02T22:16:23Z

## What's Changed

 * Fixed custom modal bug where close button did nothing

 * Fix EHR error on patient dashboard page

 * Configure new front-end theme with correct font-family 

 * Adding JWT auth via email otp 

 * Package updates

 * Add new flow to insurance testing

 * Fixing database url in staging envrionment 

 * Updating auto E2E tests



---

### v1.398.0
Released: 2025-11-26T22:27:34Z

## What's Changed

 * Configuring new react component library for front-end 

 * Release new patient dashboard design 

 * Fix issue where the PG logo is not visible in some emails

 * Created new UTM campaign



---


---

# Changelog - Week of November 24, 2025

## Recent Releases

### v1.397.0
Released: 2025-11-22T00:46:17Z

## What's Changed

 *  Insurance updates
 *  Internal update to frontend libraries
 *  Fix bug in Fabric integration
 *  Fix bugs in Broad integration
 *  Fix bug with internal ordering service
 *  Fix bug with testing in New York State
 

---

### v1.396.0
Released: 2025-11-19T23:05:20Z

## What's Changed

 *  Internal update for Fabric integration


---

### v1.395.1
Released: 2025-11-19T00:21:32Z

## What's Changed

 *  Update requests library to address vulnerabilities
 *  Internal infra configuration


---

### v1.395.0
Released: 2025-11-18T22:23:39Z

## What's Changed

 *  Prevent insurance referral deletion on form response deletion for audit purposes
 *  Changes to PWN integration
 *  Internal tooling updates
 *  Event log for insurance referrals 
 *  Updating certifi, joserfc, idna to address vulnerabilities 
 *  Expose docker port for new backend service 
 *  management command to backfill amended reports


---

### v1.394.0
Released: 2025-11-17T22:01:05Z

## What's Changed

 *  Upload HIPAA and patient history to PWN
 *  Fix internal issue with patient files 


---


---

# Changelog - Week of November 17, 2025

## Recent Releases

### v1.393.0
Released: 2025-11-14T22:59:31Z

## What's Changed

 *  Local development VSCode improvements
 *  Support for multiple signers on documents
 *  Released multi-modal file upload service
 *  Add production docuseal template ids 



---

### v1.392.0
Released: 2025-11-13T19:07:24Z

## What's Changed

 *  Adding aws alarms in preparation to launch multi-modal file upload service
 *  Adding delete patient file API 
 *  Adding PDF Document Verify 
 *  Adding HIPAA request logging 
 *  Fixed PWN consult report type 
 *  Extension fix patient files 
 *  Adding support for new insurance flow pathway



---

### v1.391.2
Released: 2025-11-11T04:18:54Z

## What's Changed

 *  Adding PWN Analytics script 
 *  Increase user info api call timeout 


---

### v1.391.1
Released: 2025-11-11T00:35:29Z

## What's Changed

 *  Upgrading django to 4.2.26 to fix vulnerability 
 *  Update brotli and fonttools to address vulnerabilities 
 *  Removing tagging for alpha mann condition
 *  Fix insurance flow login issues


---


---

# Changelog - Week of November 10, 2025

## Recent Releases

### v1.390.0
Released: 2025-11-07T23:57:29Z

## What's Changed

 *  Update internal documentation
 *  Run early the insurance check and prevent running again if a referral was already created

---

### v1.389.1
Released: 2025-11-07T21:54:57Z

## What's Changed

 * Remove WHIM - last update missed something 

---

### v1.389.0
Released: 2025-11-07T21:11:32Z

## What's Changed

 * Updating auto offer service to no longer include whim syndrome
 * Add chromatic back to frontend 

---

### v1.388.0
Released: 2025-11-06T23:04:15Z

## What's Changed

 * Exclude insurance reinbursement if proband had a WES/WGS testing in the past 3 years. 
 * reduce fields on insurance intake form flow

---

### v1.387.0
Released: 2025-11-05T23:18:27Z

## What's Changed

 * Add a timeout for user info API call 
 * Updating PWN Consult scheduled event name
 * Improving build times 
 * Updating Insurance Flow

---

### v1.386.0
Released: 2025-11-05T20:00:02Z

## What's Changed
 
 * Fix PWN consult complete check 

---

### v1.385.2
Released: 2025-11-05T17:19:45Z

## What's Changed

 * Fix intro screen getting skipped on insurance 

---

### v1.385.1
Released: 2025-11-05T00:08:32Z

## What's Changed



---

### v1.385.0
Released: 2025-11-04T23:42:43Z

## What's Changed

 * Updating internal documentation

 * Allow unauth users to go back to insurance pathway with a `redirectTo`  

 * Consult log parsing fix 

---

### v1.384.0
Released: 2025-11-04T00:25:18Z

## What's Changed

 * Setting up service for new file upload service
 * Fix patient status card 

---

### v1.383.0
Released: 2025-11-03T22:55:53Z

## What's Changed

 * Setting infrastructure for up new file upload service 
 * Updating insurance flow



---


---

# Changelog - Week of November 03, 2025

## Recent Releases

### v1.382.0
Released: 2025-10-30T17:01:09Z

## What's Changed

 * E2E tests for insurance flow  

 * Fix PWN Webhook types 

---

### v1.381.0
Released: 2025-10-29T22:17:51Z

## What's Changed

 * Add support for multiple signatures in Docuseal 

 * Update playwright npm deps  

 * PWN Referral Workflow Follow ups 

 * Setup for PWN launch 

 * Logging bug fix 

 * Updating feature flag implementation 

 * Updating prediction marketing events 



---

### v1.380.1
Released: 2025-10-29T19:18:42Z

 * Internal Changes


---

### v1.380.0
Released: 2025-10-28T22:17:44Z

## What's Changed

 *  Updating prediction system 


---

### v1.379.0
Released: 2025-10-28T20:59:10Z

## What's Changed

 * Pin local Temporal DB image version 

 * Updating PWN referral webhooks 

 * Internal tooling improvements

 * Adding Dynamic Intro Page 

 * logging and failure imrovements 

---

# Changelog - Week of October 27, 2025

## Recent Releases

### v1.378.0
Released: 2025-10-24T22:34:01Z

## What's Changed

 *  Update insurance flow


---

### v1.377.0
Released: 2025-10-24T18:21:02Z

## What's Changed

 * Update text copy for insurance flow
 * Internal tooling bug fix



---

### v1.376.1
Released: 2025-10-24T00:03:51Z

## What's Changed

 * Bug Fix


---

### v1.376.0
Released: 2025-10-23T23:31:28Z

## What's Changed

 * Updating internal tooling 


---

### v1.375.0
Released: 2025-10-23T20:42:11Z

## What's Changed

 *  Improving analytics identification 

 *  Updating insurance flow 

 * Add medicare/medicaid to main chatpg flow 

 * Updating internal tooling  



---

### v1.374.1
Released: 2025-10-23T00:42:27Z

 * Internal Update

---

### v1.374.0
Released: 2025-10-21T22:22:10Z

## What's Changed

 * Fix generate changelog auto versioning  


---

### v1.373.4
Released: 2025-10-21T17:56:49Z

## What's Changed

 * Update insurance flow

---

### v1.373.3
Released: 2025-10-21T17:41:30Z

## What's Changed

 * Update insurance flow 

---

### v1.373.2
Released: 2025-10-21T17:11:52Z

## What's Changed

 * chore(deps): bump actions/setup-node from 5.0.0 to 6.0.0 

 * Add insurance referrals to django admin 


---

### v1.373.1
Released: 2025-10-20T19:06:37Z

## What's Changed

 * Fix rename insurancereferral service

---


---

# Changelog - Week of October 20, 2025

## Recent Releases

### v1.373.0
Released: 2025-10-17T22:57:48Z

## What's Changed

 * Updating automatic restore testing configuration
 * Bug Fixes
 * Added required address input for insurance flow
 * Internal updates


---

### v1.372.0
Released: 2025-10-14T19:30:18Z

## What's Changed

 * Added duo/trio/proband genetic testing input page for insurance flow
 * Fix bug with Fabric integration
 * Removing extra fields from genome medical referral 
 * Testing program updates


---

# Changelog - Week of October 13, 2025

## Recent Releases

### v1.371.1
Released: 2025-10-09T22:23:06Z

## What's Changed

 * Internal changes

---

### v1.371.0
Released: 2025-10-09T21:47:59Z

## What's Changed

 *  Internal updates
 *  Removing WHIM auto offers



---

### v1.370.0
Released: 2025-10-08T21:01:57Z

## What's Changed

 * Internal improvements and bug fixes

---

### v1.360.0
Released: 2025-10-08T17:33:52Z

## What's Changed

 * Cleaning up unused infrastructure
 * Upgrading internal tooling
 * Improving internal alarms

---

# Changelog - Week of October 06, 2025

## Recent Releases

### v1.359.1
Released: 2025-10-03T23:52:37Z

## What's Changed

 * Remove EHR login from few-questions page. It will now only be in the review page.

 * Fix modal showing up (briefly) when navigating to new gate page 



---

### v1.359.0
Released: 2025-10-03T22:29:33Z

## What's Changed

 *  Updating django 4.2.24 -> 4.2.25 

 *  updating packagges to address dependency vulnerabilities 

 * Internal updates

---

### v1.358.0
Released: 2025-10-02T18:12:04Z

## What's Changed

 * Compliance related internal updates 

 * Update dependencies 

 * Documentation update  


---

### v1.357.0
Released: 2025-09-30T17:04:24Z

## What's Changed

 *  Internal Update 

---

### v1.356.0
Released: 2025-09-29T23:09:28Z

## What's Changed

 * Small bug fixes
 * Dependency updates

---

### v1.355.2
Released: 2025-09-29T18:37:12Z

  * Internal updates 

---

### v1.355.1
Released: 2025-09-29T16:48:06Z

## What's Changed

 * Improved vulnerability scanning

---

# Changelog - Week of September 29, 2025

## Recent Releases

### v1.355.0
Released: 2025-09-26T19:54:22Z

## What's Changed

 * Improved data recovery testing
 * Adding additional security scanning
 * Internal update

---

### v1.354.3
Released: 2025-09-25T23:05:07Z

## What's Changed

 * Internal update

---

### v1.354.2
Released: 2025-09-25T03:12:41Z

## What's Changed

 * Internal update

---

### v1.354.1
Released: 2025-09-25T02:16:13Z

## What's Changed

 * Internal update 


---

### v1.354.0
Released: 2025-09-25T00:22:13Z

## What's Changed

* Copy updates
* Internal Updates

---

# Changelog - Week of September 24, 2025

## Recent Releases

### v1.353.0
Released: 2025-09-23T22:06:34Z

## What's Changed

 * Internal bug fixes

---

### v1.352.0
Released: 2025-09-23T18:48:15Z

## What's Changed

 * Internal Bug fixes

---

### v1.351.0
Released: 2025-09-22T20:59:28Z

## What's Changed

 *  Improved internal monitoring

---

### v1.350.0
Released: 2025-09-22T17:02:18Z

## What's Changed

 * Improve security scanning

























