# RankProgress
RankProgress Combines Requirement Tracking, Event Scheduling and Attendance to Ensure Rank Advancement.

Initial Setup
  Enter all the Scouts' Names and the Rank to which they are Advancing.
  Enter the Events you will have througout the Scheduled Year.
  Assign Requirements to each of the Events.
 
 Ongoing Use
  Enter the Attendance for the Event as it takes place.
  
  RankProgress Function
    RankProgress will mark Assigned each Requirement that is assigned to an Event. 
    RankProgress, (RP), will mark Completed the Requirements for each Scout that attended the Event.
    
    Actions:
    createScout
    createEvent
    createRank
    
    
    assignScoutToEvent
    assignRankToScout
    assignReqtoRank
    assignReqToEvent
    
    
    Tables:
    Scout
      rank
        requirements
    
    Rank
      requirement
      
      Event_Types
        meeting_Event
        outting_Event
        family_Week_Event
    
    Scheduled_Events
      scouts_attending
      requirements_assigned
      
      
        
