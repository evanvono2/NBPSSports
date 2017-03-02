# nbpsSports
an app

To-Do List:


1. 

1] Create basic storyboard structure
  - Main menu: embedded in nav control with top right button with social/tweet function, tab Bar on bottom to toggle between 2 views:
    - Main Hub (default): Contains dynamic tableView 
    - Twitter feed: webView hooked to link of NBPS Athletics Twitter Feed, loading circle starts animation
    
  
    - Sports Score Views: dynamic UITableViewControllers(embedded in Navigation Controllers), with slide menu button
      - Content of each score cell varies by sport; Will be sorted by date going oldest to newest downwards
        - Sections in tableView dynamic: section for previous games, for upcoming (use NSDate for range within 1 week) 
          - Header for games in future (not including upcoming) separate setion+header for each upcoming cell, title = date
2] Integrate Firebase
  - New Feed SSH?
  - Create New Account
    - Create JSON Hierarchy for each sport
    - Users
      - Administrators: Edit scores, log in through email or google using Firebase Auth
        - User emails stored in database, by pending/approved
      - Access to data is public but changing permissions are for accounts only
      
  - Integrate Football
  


3] Enhance UI
  - Color Palate:
    - Navigation Bar Tint: 
    - Navigation Bar Button Tint:
    - Score Cell Background:
    - 
    - Slide Menu:
      - Cell Tint:
      - Text Tint:
    - Default Backgrounds:
    - 
  
