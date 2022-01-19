## happy path
* greet
  - utter_greet
* mood_great
  - utter_happy

## sad path 1
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* affirm
  - utter_happy

## sad path 2
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* deny
  - utter_goodbye

## say goodbye
* goodbye
  - utter_goodbye

## bot challenge
* bot_challenge
  - utter_iamabot

## artifact
* artifact 
 - utter_artifact

## tasks
* tasks 
 - utter_tasks

## commit
* commit 
 - utter_commit

## priority
* priority 
 - utter_priority

 ## pull
* pull 
 - utter_pull

 ## push
* push 
 - utter_push

 ## sync
* sync 
 - utter_sync

  ## tool
* tool 
 - utter_tool

  ## followup
* followup 
 - utter_followup

  ## botservice
* botservice 
 - utter_botservice

   ## exception
* exception 
 - utter_exception

## interactive_story_1
* greet
    - utter_greet
* tasks

## New Story

* tasks
* tasks
* priority
* exception
* pull

## interactive_story_1
* greet
    - utter_greet
* priority
    - utter_priority
* pull
    - utter_pull
* commit
    - utter_commit
* exception
    - utter_exception
* goodbye
    - utter_goodbye
    - action_restart
