# Changelog - Week of October 06, 2025

## Recent Releases

### v1.359.1
Released: 2025-10-03T23:52:37Z

## What's Changed

 *  Frontend for create a conversation for a form response API 

 * Remove EHR from few pages for now (to test CVR impact) 

 * Fix modal showing up (briefly) when navigating to new gate page 



---

### v1.359.0
Released: 2025-10-03T22:29:33Z

## What's Changed

 *  Updating django 4.2.24 -> 4.2.25 

 *  updating h11, python-multipart, and setuptools 

 * : Navigation Guardrails for SymptomAssessment 

 *  Don't lazy load PHProvider 

 *  Fix tier not needed on analytics call 

 * Remove loader after form response complete 

 *  Endpoint to create conv for form response 



---

### v1.358.0
Released: 2025-10-02T18:12:04Z

## What's Changed

 *  - Move pg-prod-test to stg-sequencing-service in stg-environment. 

 * Update python dependencies for compliance 

 * Add events for flow 3 endpoint 

 * Update dependencies for high vulns round 3 

 * Remove a brain func for outdated dependency 

 * : Update Repo for Onboarding 

 *  Adding selection for resources to test in restore testing 

 * GM Flow1 dynamic missing data fields 

 * More dependency updates  

 *  Removing aws inspector from cloudwatch sentry forwarder 

 * Fabric report validation fix 

 *  Removing eventbridge connection for inspector events 

 *  Updating symptom checker and sequencing service to be easier to change admin 

 *  Adjust csv script to include tier 5 form_responses 

 * Send docuseal emails 

 * SS stable DB connections for temporal 

 * Bug buster permissions to only run on prd 

## New Contributors

 * @hharris-pg made their first contribution in https://github.com/Probably-Genetic/Phenotyper/pull/3494


---

### v1.357.0
Released: 2025-09-30T17:04:24Z

## What's Changed

 *  Added mondo search with injected priority items for GM 



---

### v1.356.0
Released: 2025-09-29T23:09:28Z

## What's Changed

 * Add tagging to CAN zip code SF action, backfill 

 * Vulnerability slack webhook 

 * Flow 1 missing data feature 

 * Fix CAN zip code script 

 *  - Move to stg-environment 

 * chore(deps): bump actions/setup-node from 4.4.0 to 5.0.0 

 * chore(deps): bump actions/setup-python from 5.6.0 to 6.0.0 

 * chore(deps): bump actions/checkout from 4 to 5 

 *  updating axios version to fix vulnerability 

 * GM Validation error display 

 *  - move pg prod test to stg sequencing service 

 * Fix extra comma in diagnoses API 



---

### v1.355.2
Released: 2025-09-29T18:37:12Z



---

### v1.355.1
Released: 2025-09-29T16:48:06Z

## What's Changed

 * Adding slack message for github action complete sast scan 

 *  - Add environment creation in Terraform 

 * Adding security scan before front-end deploy 

 * Allow trivy report to create artifact before failing workflow 



---

### v1.355.0
Released: 2025-09-26T19:54:22Z

## What's Changed

 *  Add aws s3 inventory for restore testing 

 * Remove unused task 

 * GM other sex value 

 *  remove unused update_llm_prediction_status task 

 * Addresses optional on GM referral create 

 *  Close submissions notification 

 * Adding semgrep github actions for SAST code scanning (compliance) 

 * Rename security scan github action 



---

### v1.354.3
Released: 2025-09-25T23:05:07Z

## What's Changed

 * Add consent_to_treat=not_consented 



---

### v1.354.2
Released: 2025-09-25T03:12:41Z

## What's Changed

 * Feat/add address 

 * Added address check for GM csv script 



---

### v1.354.1
Released: 2025-09-25T02:16:13Z

## What's Changed

 * Added logging for GM API 



---

### v1.354.0
Released: 2025-09-25T00:22:13Z

## What's Changed

 * Update copy for insurance reimbursement 

 * Increase mondo search limit 

 * Add fields to serializer, use those fields 

 * Generate patient doc for GM 

 *  Changelog automation 

 * Adding kms permissions to app-bucket module 

 * Fix tests, relationship to patient on doc 

 * Fix/flow 2 insurance reimbursement 

 * Remove return to home from schedule page 

 * Added logic and enums for GM specialty values 

 *  Changelog auto fix 

 *  Re-adding orphanced celery function 

 * GM referral program uuid 

 * Fix guardian=True 

 * Update GM flow copy 

 *  Adding monthly aws backup restore plan 

 * Fix guardian pydantic field value 

 * Feat/gm events 



---

### v1.353.0
Released: 2025-09-23T22:06:34Z

## What's Changed

 * Fix GM validation logic 



---

### v1.352.0
Released: 2025-09-23T18:48:15Z

## What's Changed

 *  Remove all email later experiment code 

 * Fixed s3 save and insurance referral 

 * Flow 2 + frontend refactor 



---

### v1.351.0
Released: 2025-09-22T20:59:28Z

## What's Changed

 *  Fixing missing data in retool cloudwatch dashboard 

 *  Removing the business logic from the smart filter v1 app 

 * Re-add task function to clear out retries 

 *  Updating phenotyper queue age to avoid false alarm from noise 



---

### v1.350.0
Released: 2025-09-22T17:02:18Z

## What's Changed

 * Adding trivy ignore to acknowledge risks 

 *  Insurance Reimbursement Flow 1 improvements 

 *  Adding alerts from aws inspector to sentry lambda 



---

### v1.349.0
Released: 2025-09-18T18:00:43Z

## What's Changed

 * pinning the version of setuptools on the python base image 

 *  Updating README for ehr package 

 *  - Update Consent and ToS 

 * Adding hipaa agreements bucket & refactoring a little 



---

### v1.348.1
Released: 2025-09-17T20:41:45Z

 - Update Consent and ToS (#3420) @jmsalcido 


---

### v1.348.0
Released: 2025-09-16T22:09:49Z

## What's Changed

 *  Making sure trainers aren't given qualify/offer/offerable actions 

 *  -  -  - SS -> generate variant json file for `{matrixId}/report.json` and `{matrixId}/report.pdf` 

 *  -  -  - Add bucket for MatrixShare 

 * chore(deps): bump aquasecurity/trivy-action from 0.28.0 to 0.33.1 

 *  Hella cloudwatch metrics 

 *  - Use the module MatrixShare Bucket correctly in the Sequencing Service 

 *  Updating openai to fix h11 vulnerability 

 *  Removing unused packages with vulnerabilities 

 *  One up health 504 fix 



---

### v1.347.1
Released: 2025-09-11T23:20:29Z

## What's Changed

 *  Removing hyphan in physician last name broad order 

 * Handle "X-linked Recessive" case 



---

### v1.347.0
Released: 2025-09-11T22:40:44Z

## What's Changed

 *  -  - fix search for is_pre_approved 



---

### v1.346.0
Released: 2025-09-11T21:11:30Z

## What's Changed

 *  Fixing save location for ehr data 



---

### v1.345.1
Released: 2025-09-11T19:29:12Z

## What's Changed

 *  Fixing save location for ehr data 



---

### v1.345.0
Released: 2025-09-11T16:59:15Z

## What's Changed

 * Adding retool auth class to ehr api 

 *  Adding to readme info on how to see who has logged in 



---

### v1.344.1
Released: 2025-09-11T16:27:38Z

## What's Changed

 *  Adding s3 logging 

 * Add fabry to list, missing lysosomal on facial photo required 

 * Fix adblockers from breaking site on first load 



---

### v1.344.0
Released: 2025-09-10T21:12:13Z

## What's Changed

 * Update boxsdk, cryptography libs 

 *  Removing unused caprover port for compliance 

 * Update cryptography even more 

 * Update cryptography more pt2  

 *  SS -> SC HTTP query FormResponse return query_tags 

 * Add exclusion rule for STX, SYN, Alpha-Mann 

 *  Trivy vulnerability scanner 

 * Ehr retool use 

 *   -  - SS -> Django Signal -> enqueue report ready orders when status changes to it. 

 * Fixing rpa workflow breaking from trivy accessing env 



---

### v1.343.0
Released: 2025-09-09T20:26:57Z

## What's Changed

 * Update more deps 

 *  Adding better logging for 1upHealth http request error 

 *    Update list and fix dropdown for previous tests 



---

### v1.342.1
Released: 2025-09-08T23:42:12Z

## What's Changed

 *  Fix jwt encode not working 



---

### v1.342.0
Released: 2025-09-08T22:16:31Z

## What's Changed

 * Update python dependencies to resolve critical + high issues 

 *  Removing graphql and smart filter specific api 

 *  Removing public ssh, using session manager instead 

 * Don't run actions for trainers 



---

### v1.341.2
Released: 2025-09-05T23:44:46Z

## What's Changed

 * Fix RPA better logging when adding HPOs 



---


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
