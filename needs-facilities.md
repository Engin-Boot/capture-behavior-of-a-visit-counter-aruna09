# Visit-counter for a Facilities Manager

Scenario: Report visitor trends during a week of operation

  Given: the history of visitor count of atleast one week
  
  When: Facilities Manager clicks on the "Generate Report" Button
  
  Then: A report is generated with a graph/pie chart to  indicate the total number of visitors along with a tally of the type of vehicle(two wheeler/four wheeler) 
  

Scenario: Alert when seating capacity is full

  Given: the seating capacity is full
  
  When: Facilities Manager tries to allocate a parking space/seat to an incoming visitor.
  
  Then: Create an Alert to notify the manager with an appropriate message
  
  
Scenario: Show me location of empty parking spaces/seating

  Given: the system is updated as to the status(empty/filled) and the location of the parking space/seating
  
  When: Facilities Manager tries to allocate a parking space/seat to an incoming visitor.
  
  Then: Indicate empty spots with a Green colour and occupied spots with Red colour
