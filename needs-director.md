# Visit-counter for a Director

Scenario: Show patient visits during working days and holidays

  Given: that new patients have visited the hospital
  
  When: Director clicks on the "Show count" button
  
  Then: Display the total count of patients under Working days and holidays

Scenario: Compute parking slots to reserve for visiting specialists

  Given: we have the number of specialists visiting on a day
  
  When: Director wants to find the number of empty spaces
  
  Then: compute and display the number of empty spots available
