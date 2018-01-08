# PTO
simple web application to track PTO accumulated and used.
Requirements:
	Display total PTO accumulated, in hours, days
	Display total PTO taken, in hours, days
	
	Given I have at least X hours of PTO accumulated
	When I make a request to take X hours off
	Then I should see the PTO Taken increase by x
	And I should see the PTO Accumulated decrease by x.


	Given I do not have X hours of PTO accumulated
	When I make a request to take X hours off
	Then I should see a message "Only [PTO remaining is available] and X hours were requested, request is denied."

	Eventually move towards more features.
