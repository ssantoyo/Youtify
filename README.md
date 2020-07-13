# Youtify

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)

## Overview
### Description
Youtify is a Youtube to Spotify playlist converter that automates the process of manually selectig songs and creating a playlist. 

### App Evaluation
- **Category:** Music/Entertainment
- **Mobile:** The app be primarly developed for mobile but would also be practicable on a computer. More features can be made on the mobile device.
- **Story:** User can transfer music from Youtube to Spotify wherever they are. 
- **Market:** Anyone who loves music and sees benefit in creating purely music playlist on spotify
- **Habit:** This app could be used as often or unoften as the user wanted depending on how many playlist they wsh to transfer, and what exactly they're looking turn into a Spotify playlist.
- **Scope:** First we would start with having people use the app for song transfer only, but can evolve in the future into transfering music from Spotify to Youtube. Potentially, adding music videos and song suggestions based off your transfers.

## Product Spec

### 1. User Stories (Required and Optional)

**Required FBU Must-have Stories**

* [ ] User can see app has multiple views
* [ ] User can log in/log out of your app as a user
* [ ] User can sign up with a new user profile
* [ ] Your app incorporates an external library to add visual polish
* [ ] Your app use an animation (doesn’t have to be fancy) (e.g. fade in/out, e.g. animating a view growing and shrinking)
* [ ] Your app uses gesture recognizers (e.g. double tap to like, e.g. pinch to scale) 
* [ ] Your app contains at least one more complex algorithm 
* [ ] Your app interact with a database (e.g. Parse) 
* [ ] Your app integrates with a SDK (e.g. Google Maps SDK, Facebook SDK)

**Required Must-have Stories**
* [x] User sees app icon in home screen and styled launch screen
* [ ] User can sign up to creat a new account using Parse authentication
* [ ] User can log in and log out of his or her account
* [ ] The current signed in user is persisted across app restarts
* [ ] User can view all their Youtube playlist
* [ ] User can pull to refresh the playlist on Youtube

**Optional Nice-to-have Stories**

* [fill in your required user stories here]
* ...

### 2. Screen Archetypes

* Login - Parse
   * User can login
   * User can sign up
* Login - Spotify and Youtube
   * User can Login
* TimeLine
   * User can see youtube playlist
   * User can see profile image
* Detail View
   * User can see all songs within selected playlist
   * User can being the transfer of playlist from Youtube to Spotify 

### 3. Navigation

**Tab Navigation** (Tab to Screen)

* Login/Sign up
* Music selection

**Flow Navigation** (Screen to Screen)

* Login/ Sign up
   * One time login and log out w/ persisted log in
* Music Selection
   * Selection of playlist and toggle song selection
 

## Wireframes
[Add picture of your hand sketched wireframes in this section]
<img src="" width=600>

### [BONUS] Digital Wireframes & Mockups

### [BONUS] Interactive Prototype

## Schema 
[This section will be completed in Unit 9]
### Models
[Add table of models]
### Networking
- [Add list of network requests by screen ]
- [Create basic snippets for each Parse network request]
- [OPTIONAL: List endpoints if using existing API such as Yelp]
