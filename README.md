Original App Design Project - (Update 4/28/22)

I have to redo my app. However, please find below gif showing progress.
===
# I made some pretty good headway. see gif and project updates https://github.com/users/RebelBobby/projects/2
 below.
# military_transition_guide to complement https://www.militarytransition.vet/

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)

## Overview
### Description
An app to complement the above website which I donated to veteran service offices. There will be buttons which give access to a checklist guiding a soon separating service member at key timeframes counting down from 18 months.

### App Evaluation
[Evaluation of your app across the following attributes]
- **Category:** An interactive checklist guide
- **Mobile:** Mobile only but can link to website for another reference.
- **Story:** It allows a user to enter a guide applicable to how far along they are from exiting the military.
- **Market:** Military members.
- **Habit:** Daily reference.
- **Scope:** It could be given to transitioning service members during their military outprocessing appointments.

## Product Spec

### 1. User Stories

**Required Must-have Stories**


* App opens with requirements
* User checks off completed items
* User can add new items
* User can download list
* User can delete items


**Optional Nice-to-have Stories**

* Stories of successful or unsuccessful transitions out of the military.

### 2. Screen Archetypes

* A dashboard of all the key timeframes
   * Select a time frame
	* Enter checklist
	* Edit or add items
	* Back to main


### 3. Navigation
**Flow Navigation** 

* Select timeframe
* Edit/update milestones
* Download list
* Go back to main


## Wireframes
<img src="wireframe.jpg" width=600>

[BONUS] Digital Wireframes & Mockups
<img src="Bonus.png" width=100>
<img src="Bonus1.png" width=100>



## Progress
I made some pretty good headway. I just have to continue to plug away at the content.
<img src="progress3.gif" width=600>

### Models
#### Post

   | Property      | Type     | Description |
   | ------------- | -------- | ------------|
   | View task       | String   | List displayed to user  |
   | Add task    | String | Author adds task |
   | Download    | .txt file| User can dowload list |
   | Delete   | Delete| User can delete a list |

### Networking
#### List of network requests by screen
   - This app wont interact with a database.


#### [OPTIONAL:] Existing API Endpoints
##### Still planning. Need to incorparate project said above project milestones

https://github.com/users/RebelBobby/projects/2


<img src="project.png" width=500>

- Base URL - See project.

   HTTP Verb | Endpoint | Description
   ----------|----------|------------
    `GET`    | /inwork | still planning



   
