# Visit-counter for a Facilities Manager

Scenario: Report visitor trends during a week of operation

  Given: history of visitor count of one week
  
  When: FM clicks on the "Generate Report" Button
  
  Then: Generate a report
  
Scenario: Alert when seating capacity is full

  Given: the seating capacity is full
  
  When: FM tries to allocate a parking space to a visitor.
  
  Then: Create an Alert to notify the manager with an appropriate message
  
Scenario: Show me location of empty parking spaces/seating

  Given: the system is updated as to the status(empty/filled)
  
  When: FM tries to allocate a parking space/seat to an incoming visitor.
  
  Then: mark empty spots with a Green color
