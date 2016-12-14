# deep_tracking_playground


Trackers have 2 states:
  -Tracking
  -Training
  
 During Tracking:
  -Initialize tracker
  -Until some stopping condition
    1. Load next image
    2. Detect next location

During Training:
  -Load datasets
  -Sample randomly from each dataset
  -Train according to some dogma
  
  Classes Needed:
  
  Tracker:
  
    Variables:
      -List of Datasets
      -Tracked Locations
      -Prev Image
    
    Methods:
      -Train
        Until some stopping condition
        
      -Initialize Tracker
      
      -Track
        -Given image find next location

  Dataset:
    Variables:
      Paths
      
   Method:
    Load dataset
