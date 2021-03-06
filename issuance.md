---
layout: default
title: NPFS Issuance Training
---

# Issuance Application

## Contents

## 1.Introduction

The National Pandemic Flu Service (NPFS) Issuance Application has three areas of functionality which are as follows:

* URN Lookup
* Recover URN
* Issue with Prescription,FP10SS or Voucher.

**[Getting Started](#getting-started)**

  * [Login Screen](#login-screen)
  * [Select Your User Role](#select-your-user-role)
  * [Initial Encounter Screen](#initial-encounter-screen)
  * [Feedback - Tell us what you think](#feedback---tell-us-what-you-think)
  * [Other Supporting Functionality](#other-supporting-functionality)
   
## 2. **[URN Lookup](#urn-lookup)**

  * [Duplicate URN](#duplicate-urn)
 
## 3. **[Recover URN](#recover-urn)**

## 4. **[URN status](#urn-status)**

 * [URN Issued](#urn-issued)
 * [URN Cancelled](#urn-cancelled)
 * [URN Expired](#urn-expired)
 * [URN about to Expire](#urn-about-to-expire)

## 5. **[Issue with Prescription, FP10SS or Voucher](#issue-with-prescription-fp10ss-or-voucher)**

## 6. **[Identification of Collecting Person](#identification-of-collecting-person)**

* [Patient Identification](#patient-identification)
* [Proxy Identification](#proxy-identification)

 
## Getting Started

Open this link to access the NPFS Issuance Portal [www.nationalpandemicfluservice.nhs.uk/issuance](https://www.nationalpandemicfluservice.nhs.uk/issuance).  
It may be advisable to create a bookmark if you will access the application frequently.

At any time you can safely use the **training** system to become familiar with the functions of the live system.  Any actions you take will not be reflected
in the live system and you will have no impact on services or patients. [training.nationalpandemicfluservice.nhs.uk/issuance](https://training.nationalpandemicfluservice.nhs.uk/issuance)

In order to use the NPFS Issuance Application the user must be been assigned a Collection Point Assistant Centre (CPA) role.


### Login screen

Enter your unique Username and Password.  These will be supplied by your Team Leader.

![][welcome-screen]

> Your password must be changed at the first login.  Full instructions are provided later in this guide.
>
> Your account will be locked out after 3 unsuccessful login attempts.  Your Team Leader will need to reset.


In order to discourage easy-to-guess passwords, the new password must either be a passphrase (preferred) or it should meet the following complexity requirements:

> The password must be at least 10 characters long.
>
> The password must contain at least one uppercase letter.
>
> The password must contain at least one number.
>
> The password must contain at least one special character (such as !,?,@,#,$,%,&,* and +)
> 
> A table showing a full list of special characters can be found at the following location:

[Special Character List](https://www.owasp.org/index.php/Password_special_characters)


### Select Your User Role

You may have multiple roles available.  Select the most appropriate role for the tasks that you need to complete.

![][issuance-role-screen]

> **Your Session** -  Confirms the username and role you are currently logged in as, as well as your login time and role once you have selected it.
>
> **Logout** - Displayed on all screens, click here to logout of system


### Initial Encounter Screen

This screen allows the Collection Point Assistant to select the appropriate option for an encounter:
The CPA should perform one of the following:

* Enter a URN number to search for details of any authorised antiviral if the URN is available 
* Select **Recover URN** search for details of any authorised by patient demographics if the URN is not available 
* Select Issue by Voucher to allow issuance of an antiviral if the patient presents a prescription or voucher 

![][initial-screen]

### Feedback - Tell us what you think

You can provide feedback on the Pandemic Flu service at any time whilst on the portal, by clicking the ”Provide feedback on the Pandemic Flu service” link on the right of every page.

This is important, and will help us improve the service offered.

This can be used either for feedback from your own experience, or for the patient you are talking to, for example if the questions are unclear for them.

![][feedback-tell-us-what-you-think]

This will allow you to enter in the type of feedback, including a free text field to provide specific information.

![][feedback-form]

You (or the patient if it is their feedback) can choose to be contacted about this feedback, or not.

If they choose to be contacted, the next page will ask for their name and contact details.


### Other Supporting Functionality

In addition to feedback there is a range of other supporting functionality which is available throughout any assessment these include:

* Language Support – the portal can be used in English or Welsh by selecting the appropriate link.
* Supplementary Pandemic Flu Information. A separate link is provided for information on flu symptoms for each country.


## URN Lookup

This option should be used if the person collecting the antiviral is able to present the URN number at the collection point.
Enter the URN that the person brings with them into the URN box and select **search**.

![][urn-search]

Following **Search** the details of the URN will be retrieved.

![][urn-retrieve]

### Duplicate URN

On rare occasions a duplicate URN may be issued by the NPFS system and more than one URN may be retrieved as a result of a URN Lookup. 

![][duplicate-urn]

If this occurs, the demographic details of the patient will be displayed at the point of searching for a URN.
You must select the record associated with the person attending for issuance - use the ID they have with them to confirm this.


## Recover URN

This option should be used if the person collecting the antivirals is not able to present the URN at the collection point. The URN can be recovered by searching on patient demographics.

Select **Recover URN** you will then be presented with the following screen. You should enter the postcode, birth date and gender for the patient which are mandatory fields. 

![][urn-recover]

Selecting **search** will recover the URN 

![][urn-recover-result]

It is important to check the patient details of the recovered URN.


## URN Status

When a URN is retrieved (either via URN Lookup or Recover URN) the status of the URN may be displayed such as Issued, expired or cancelled. 

The status will also be shown as a coloured label next to the URN number. The date of expiry, cancellation or issue can also be seen by 
hovering the mouse over the label.

If no label is shown the URN is valid and the antiviral can be issued.

### URN Issued

Each URN is only able to be used to collect one dose of antivirals - this is important for patient safety

If a URN has already been issued (i.e. antivirals collected) this will be shown by a coloured label next to the URN when you conduct a search on the system 
(either via URN Lookup or Recover URN). 

The date of issuance will also be displayed.

If the URN has been issued you will not be able to issue the antivirals

![][urn-issued]

### URN Cancelled

A previously issued URN may have been cancelled this may be due to a change of symptoms, an underlying health condition becoming apparent or some other reason.

If a URN has been cancelled this will be shown by a coloured label next to the URN when you perform a search (either via URN Lookup or Recover URN). 
The date of cancellation will be also displayed.

If a URN has been cancelled you will not be able to issue the antivirals

![][urn-cancelled]

### URN Expired

Each URN is only valid for 7 days - this is identified at the time of the completed assessment and is important for patient safety

If a URN has expired this will be shown by a coloured label next to the URN when you perform a search (either via URN Lookup or Recover URN). 
The date of expiry will be also displayed.

If a URN has expired you will not be able to issue the antivirals.

![][urn-expired]

### URN about to Expire

Each URN will expire after 7 days - this is identified at the time of the completed assessment and is important for patient safety.

If the URN is within 24 hours of the expiry date it will be shown by a coloured label next to the URN when you conduct a search on the system (either via URN Lookup or Recover URN)

The actual date of expiry can be seen by hovering the mouse over the expires soon label.

If a URN is marked expires soon you will be able to issue antivirals.

![][urn-about-to-expire]

## Issue with Prescription. FP10SS or Voucher

If the collector attends the collection point with a prescription or a voucher then antivirals can be issued.

![][issuance-voucher]

This can be done be selecting the **Issue by Voucher** button.

The collector of the antiviral will still need to provide evidence of identification. Following Issue by voucher you will be presented with the following additional fields
that need to be populated with details of the voucher.

## Identification of Collecting Person

Proof of identification must be provided for the patient who has been authorised for the antiviral. In addition if the antiviral is to be collected by a proxy (flu friend) they must 
also provide proof of identification.

If identification is not provided the antiviral cannot be issued. The need for identification evidence is stated during the assessment process.

## Patient Identification

Following retrieval of the URN the verification of the identity of the patient is mandatory.

You will be provided with the following field.

![][patient-id]

You should use the drop down menu to input the form of identification that has been provided to verify the patient’s identity and select **Continue**.

If it is the patient collecting the antiviral for themselves then **Patient** should be selected followed by **Continue**.

![][select-patient]

You will then be presented with confirmation of the antiviral and dose to be issued plus be required to enter the dispense reference (e.g. product, batch or serial number).

![][urn-dispense]

Then select **Finish** to complete the issuance with the option to start a new search

![][issuance-complete]

## Proxy Identification

If the antiviral is to be collected by a proxy (flu friend) not the patient then additional proof of identification needs to be recorded.

![][proxy-id]

Select proxy and the **Continue**.

You will then be required to populate the following details regarding the proxy collecting the antiviral on behalf of the patient. This includes the proof of identification 
rovided by the proxy.

![][proxy-details]

Following population of the Proxy details you will be asked to enter the dispense reference before completing the issuance.


[welcome-screen]: images/Issuance/Welcome_screen.png "Welcome Screen"
[issuance-role-screen]: images/Issuance/issuance_role_screen.png "Issuance Role Screen"
[initial-screen]: images/Issuance/Initial_screen.png "Initial Screen"
[feedback-tell-us-what-you-think]: images/feedback-tell-us-what-you-think.png "Feedback - Tell us what you think"
[feedback-form]: images/feedback-form.png "Feedback Form"
[urn-search]: images/Issuance/urn_search.png "URN Search"
[urn-retrieve]: images/Issuance/urn_retrieve.png "URN Retrieve"
[duplicate-urn]: images/Issuance/duplicate_urn.png "URN Retrieve"
[urn-recover]: images/Issuance/urn_recover.png "URN Recover"
[urn-recover-result]: images/Issuance/urn_recover_result.png "URN Recover Result"
[urn-issued]: images/Issuance/urn_issued.png "URN Issued"
[urn-expired]: images/Issuance/urn_expired.png "URN expired"
[urn-cancelled]: images/Issuance/urn_cancelled.png "URN Cancelled"
[urn-about-to-expire]: images/Issuance/urn_about_to_expire.png "URN about to expire"
[issuance-voucher]: images/issuance-voucher.png "Issuance Voucher"
[patient-id]: images/Issuance/patient_id.png "Patient id"
[select-patient]: images/Issuance/select_patient.png "Select Patient"
[urn-dispense]: images/Issuance/urn_dispense.png "URN Dispense"
[issuance-complete]: images/Issuance/issuance_complete.png "Issuance Complete"
[proxy-id]: images/Issuance/proxy_id.png "Proxy id"
[proxy-details]: images/Issuance/proxy_details.png "Proxy details"

















