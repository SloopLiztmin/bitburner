# netburner
Netburner Idle Game

TESTING TODO:
	hack() and sleep() in a script
		hack() seems to be working
			
		Sleep() seems to be working
	Creating the foreign server network doesn't seem to be working
		--Seems to be fixed 
	Script RAM Usage and corresponding terminal commands
	If a server has no more money available it cannot be hacked anymore
		Should work automatically...because your money gained percentage will be multiplied by 0
	When the game is loaded re-load all of the scripts in runningScripts
		- Seems to be working
	Update skill level on cycle
	If a script has bad syntax...it fucks everything up when you try to run it so fix that
		Try catch for script?
		Check that killing scripts still works fine (TESTED - LOoks to work fine)
		Check that if script has bad syntax it wont run at all and everthing works normally (Seems to work fine)
		Check if script throws during runtime it shuts down correctly (seems to work fine)
		
	Adjust leveling formula. Goes up way too high at first
		http://gamedev.stackexchange.com/questions/55151/rpg-logarithmic-leveling-formula
		- might be too slow now? 
		
	Scripts tab that shows script stats
		Seems to work, at least the basics (for online production)
	Script offline progress
	
	Delete a script from Active scripts when the WorkerScript is deleted
		Seems to work
		
	Server growth
		Implemented but it might need to be balance/formula readjusted
		
	ctrl+C functionality for all running command like hack(), analyze(), and tail 
		Implemented for hack() and analyze(). Seems to work

	Saving/Loading factions
		No errors thrown when saving/loading game at the start
		
	Scroll all the way down when something is post()ed
    
    Purchasing Servers
    
    Work
    Companies
    Add possible CompanyPositions for every Company
    Applying/working for companies
    
    Factions
    
    Change Company pages to display "apply for promotion" and other stuff when you are already employed there

    Augmentations
    
    rm command seems to work
    
    Make it so that a script cannot be edited if it is running
    
    + Traveling
        
    Script logging functionality? Logs to internal "log file" (property of script itself)
        Can see log with tail.
        Should add something where if you click it in the "Active Scripts" GUI you can see the logs too        
        
        Seems to work fine
Tasks TODO:
    Add Silhouette Criminal Faction 
    Factions Info page isn't formatted correctly
    
    Augmentations that decrease time to make programs
    
    New server hostname in Purchase Server Pop-up Box needs limits..don't think the ones set in HTML work
    
	Tutorial and help - INTERACTIVE TUTORIAL
	Secret Servers
	
	Hack time formula needs rebalancing I think, so does hack exp formula
	
    Create new menu page for purchased servers
    
    Gyms - Later..don't need for MVP
	
	Update CONSTANTS.HelpText
	Account for Max possible int when gaining exp (it will overflow)
	Text in script editor that says ("ctrl + x" to save and quit)
	
	OPTIMIZATION
		https://gamealchemist.wordpress.com/2013/05/01/lets-get-those-javascript-arrays-to-work-fast/