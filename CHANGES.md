Rools - 0.4 released 2007/11/05
-------------------------------
* facts can include a range (Grant Mcinnes idea)
* Fixed examples on website
	
Rools - 0.3
-----------
* facts can now have a defined namespace
* fixed csv_test
* added load_xml_rules_as_string and load_rb_rules_as_string
* 100% test coverage
* Applied doc patch from John Mettraux
	
Rools - 0.2   released 2007/05/22
---------------------------------
* specifications have been created using RSpec
* fix bug #10985 regarding the support of rule extension
* fixed assertion of a fact within a rule
	
Rools - 0.1.6 released 2007/05/20
---------------------------------
* todo #1319 use Rails conventions for rules parameters.  
  WARNING: no more free for all.  
  The variable used in the rule has to match the define parameter (a Class type)
  therefore the variable has to be a lowercase singulr version of the parameter.  This is
  required now to support multiple facts
* todo #1318 expand assert to accept more than one object.  You can also use a fact notation
  to add facts and call evaluate
* todo #1283 rule priority completed
* todo #1286 added facts that can be asserted
* todo #1288 decision tables have been completed
	
Rools - 0.1.5  released 2007/04/27
----------------------------------
* todo #1282 Added unit tests for baseline
* todo #1283 Added rule priority (not completed)
* todo #1284 Added XML rule format
* todo #1286 Added facts support
* todo #1287 Added decision table capability
* todo #1288 Added logging capability to trace engine
* todo #1292 Major Rakefile upgrade for site auto-generation (Thanks to John Metttraux)
		
Rools - 0.1.4 released 2005/12/15
---------------------------------
* Removed "examples" folder since my RDoc kung-fu cannot be denied and the examples were redundant
* Added Rools::open to rools.rb
* Added pscp.rb to create SshPublishers on Win32 with PuttySCP
* Added Rools::RuleSet#assert return codes, :pass and :fail
* Added stop and fail methods to RuleSet, Rules, and DefaultParameterProc

Rools - 0.1.3
-------------
* Finished most documentation
* Tweaked the rakefile
		
Rools - 0.1.2
-------------
* Added RAKEFILE, README, CHANGELOG
	
Rools - 0.1.1
-------------
* Added RuleConsequenceError

