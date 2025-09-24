# Changelog - Week of September 24, 2025

## Recent Releases

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

### v1.341.1
Released: 2025-09-05T23:30:59Z

## What's Changed

 *  Adjust rpa missing percent, fix error output 



---

### v1.341.0
Released: 2025-09-05T22:19:57Z

## What's Changed

 *  - Adding a percentage vs actual HPOs 



---

### v.115.0
Released: 2025-09-05T20:31:46Z

## What's Changed

 * Care Action Network (CAN) zip code notification 

 * Update node dependencies to resolve critical + high issues 

 *  Remove feature flag for conversation variant 

 *  - FTD auto offers 

 *  Adding GI issues to hallmark symptoms questions 



---

### v1.340.0
Released: 2025-09-04T18:36:26Z

## What's Changed

 *  Fix Fabric Broad test id 



---

### v1.339.1
Released: 2025-09-03T21:37:36Z

## What's Changed

 * Fix indexing on message lookup 

 * Fix 



---

### v1.339.0
Released: 2025-09-03T20:38:35Z

## What's Changed

 *  Move tagging action, add trainer:form:end, add celery task 

 *  ChatPG Chat updates 

 * fix 



---

### v1.338.1
Released: 2025-09-03T18:51:05Z



---

### v1.338.0
Released: 2025-09-03T16:27:04Z

## What's Changed

 *  Updating user multiselect transcript 

 *   Fix issues 



---

### v1.337.0
Released: 2025-08-30T00:02:56Z

## What's Changed

 * Fixed activity that had >1mb payload to update DB directly 

 * Fix md5 check 

 * Add Pitt-Hopkins to list 



---

### v1.336.4
Released: 2025-08-29T22:25:12Z



---

### v1.336.3
Released: 2025-08-29T20:14:30Z

## What's Changed

 * Comment out insurance reimbursement status 

 * Fix get bool env var 



---

### v1.336.2
Released: 2025-08-29T16:36:16Z

## What's Changed

 *  Fix logger failing 

 *  Add underscore versions  to allowed strings list 



---


---

# Phenotyper Changelog

