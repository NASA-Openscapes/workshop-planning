---
name: Request and Reserve Workshop Jupyter Hub
about: Reserve a window of time and password for your workshop
title: "[Reserve Workshop] <brief description>"
labels: "workshop"
assignees:
  - ateucher
---
<!--
Use this issue to reserve access to the NASA JupyterHub for a workshop Hub URL: https://workshop.openscapes.2i2c.cloud.

Please see the [documentation on openscapes.cloud](https://openscapes.cloud/password-access.html) for detailed instructions.

See current reserved times here: <https://docs.google.com/spreadsheets/d/1Y4qzqWLsKHTNzuQi-fOaHGud0Ld_q1GHAzhS9-grV7Q/edit?usp=sharing> (look at NASA tab),
and add your workshop information.  
*I cannot see the spreadsheet.*: Reach out to Andy so he can add you to the Openscapes group that has edit access.
-->

**Describe the event**
Short description is fine. Please include a link to the workshop website if you have one.

**Event Start Date/Time	and Event End Date/Time**

**Reset Date**
By default the password will be reset and participants' home directories erased seven days after the workshop ends. 
If you want the participants to have more or less access than the default of seven days, please specify here.

**Number of Participants**
Roughly.

**Resources that Participant Need**

1. What RAM will participants typically need? 2Gb (default), 4Gb, more? This is selected in the dropdown and knowing what you will need, helps us make sure the hub is adequately provisioned.
2. Confirm that the image you will be using is sufficient for your needs (i.e., has the packages and sufficient versions you need), or that you have created an image that can be used by participants
3. Are there any special storage needs? Like will participants need access to large shared files? Do you anticipate that participants might download lots (10s of Gb or more) of data? If so, we will work with you on how best to do that in the workshop. We have a S3 scratch bucket and a shared drive so that we don't have 10s of copies of big data sets.

**Once we confirm**

Add your event in the [workshop spreadsheet](https://docs.google.com/spreadsheets/d/1Y4qzqWLsKHTNzuQi-fOaHGud0Ld_q1GHAzhS9-grV7Q/edit?usp=sharing). 
Your event password will be live on the "Password Change Date" in column 1 in the spreadsheet.

**Checkboxes for organizer and hub POC**

- [ ] **Hub POC**: Sent confirmation to organizer (a comment in this issue thread is fine)
- [ ] **Organizer**: Submit a ticket by email to 2i2c for the workshop [as per instructions](https://openscapes.cloud/password-access.html), cc'ing hub POC.
- [ ] **Hub POC**: Confirm `[Event]` issue opened by 2i2c in response to ticket ([example](https://github.com/2i2c-org/infrastructure/issues/5466))
- [ ] **Organizer**: Two weeks before event. I have tested the default hub images on the nmfs-openscapes.2i2c.cloud hub or conferred with hub POC on plan for a workshop specific image.
- [ ] **Organizer**: In the week before the event (or when POC indicates password should be live). I tested that the workshop password works and images work.
- [ ] **Hub POC**: After event, put in a 2i2c ticket to remove the participants directories, cleared shared-public, and reset password.
- [ ] **Organizer**: After the event, open an issue
