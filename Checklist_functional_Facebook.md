 # Checklist functional Facebook (Log In, Sign Up, Forgot Password)  

| Type: | |#1| Smoke
        | |#2| Critical path
        | |#3| Extended
        | |#4| Acceptance

  ID	Component 	           Verification 	                Type 
LI-001	Log In(common verify)	   Correct values (email / password)	Smoke
LI-002		                   Correct values (phone / password)	Smoke
LI-003		                   Incorrect values (email / password)	Smoke
LI-004		                   Incorrect values (phone / password)	Smoke
LI-005		                   Correct values (email), 
                                   incorrect values (password)	        Smoke
LI-006		                   Incorrect values (email), 
                                   correct values (password)	        Smoke
LI-007		                   Incorrect values (phone), 
                                   correct values (password)	        Smoke
LI-008		                   Correct values (phone), 
                                   incorrect values (password)	        Smoke
LI-009		                   Empty field	                        Extended
LI-010		                   Filling in a one field (login)	Extended
LI-011		                   Filling in a one field (password)	Extended
LI-012		                   Working of buttons 
                                   (hide / show) password	        Smoke
LI-013		                   Working of button (Forgot Password)	Smoke
LI-014		                   Working of button 
                                   (Create New Account)	                Smoke
LI-015		                   Working of button (Create a Page)	Smoke
LI-016		                   Working of links in footer	        Critical path
LI-017		                   The ability to change location 
                                   scroll with the mouse, 
				   button (Page up/down, Home/End)	Smoke
LI-018		                   The use of keys and combination 
                                   (Ctrl+C, Ctrl+V, Enter)	        Smoke
			
SU-001	Sign Up (common verify)	Correct filling field 	Smoke
SU-002		Empty field	Extended
SU-003		Filling in the fields with passes optional items	Extended
SU-004		Filling in the fields with passes mandatory items	Smoke
SU-005		The ability to select a value from the list with the mouse pointer or arrows from the keyboard	Smoke
SU-006		Restart the page with the completed registration	Smoke
SU-007		Verification the registration (log out and log in)	Smoke
SU-008		Working of button (Sign Up) 	Smoke
SU-009		Working of button (Closed)	Smoke
SU-010		Working of link (Terms)	Critical path
SU-011		Working of link (Data Policy)	Critical path
SU-012		Working of link (Cookies Policy)	Critical path
SU-013		The ability to change location scroll with the mouse, button (Page up/down, Home/End)	Smoke
SU-014		The use of keys and combination (Ctrl+C, Ctrl+V, Enter)	Smoke
SU-015	Sign Up 
1) dropdown list	The ability to select a value from the list with the mouse pointer or arrows from the keyboard	Smoke
SU-016		Selecting a list item by pressing the match first letter on the keyboard	Smoke
SU-017		The ability input a values of manual 	Critical path
SU-018		Match text changes when using scrolling	Smoke
SU-019		The ability to change location scroll with the mouse, button (Page up/down, Home/End)	Smoke
SU-020		Sort on alphabet	Extended
SU-021	Sign Up 
2) radio button	Functioning (on/off)	Smoke
SU-022		There can't be less than two radio buttons	Extended
SU-023		By default, one radio button must be enabled	Extended
SU-024		Activation by clicking on both the symbol and the text	Smoke
SU-025	Sign Up (verify of input)
3) text field	Symbols (123abc!+-@^&*%#,./?абвABCАБВ)	Smoke
SU-026		Only spaces	Extended
SU-027		Spaces in the middle, before and after text	Smoke
SU-028		length (max / min)	Extended
SU-029		Entering tags	Extended
SU-030		Entering wildcards	Extended
SU-031		Entering a script	Extended
SU-032	Sign Up (verify of input)
4) email field	Symbols (123abc!@^&*%#,./?абвABCАБВ)	Smoke
SU-033		Only spaces	Extended
SU-034		Spaces in the middle, before and after text	Critical path
SU-035		With spaces in the domain / local part	Smoke
SU-036		Email without domain / local part	Extended
SU-037		With the use of @	Smoke
SU-038		Without using @	Critical path
SU-039		With multiple @@@	Extended
SU-040		Using a point in the domain / local part	Smoke
SU-041		Email with multiple points in the domain / local part	Critical path
SU-042		Without using a point in the domain / local part	Smoke
SU-043		Email with a hyphen in the domain / local part	Smoke
SU-044		Email without a hyphen in the domain / local part	Smoke
SU-045		Email with an underscore in the domain / local part	Critical path
SU-046		Email without an underscore in the domain / local part	Critical path
SU-047		Email with a Cyrillic domain name (login@домен.рф)	Extended
SU-048		Email length (max / min)	Extended
SU-049		Entering tags	Extended
SU-050		Entering wildcards	Extended
SU-051		Entering a script	Extended
SU-052	Sign Up (verify of input)
5) phone	Mustn't accept letters and special symbols (abc! @^&*%#,./?абвABCАБВ)	Smoke
SU-053		Entering punctuation marks (dot, floating point)	Extended
SU-054		Limit values (max/min)	Extended
SU-055		Including symbols ( + ; - ())	Smoke
SU-056		Without symbols (+;- () )	Smoke
SU-057		Only spaces	Extended
SU-058		Spaces in the middle, before and after text	Extended
SU-059		Entering tags	Extended
SU-060		Entering wildcards	Extended
SU-061		Entering a script	Extended
SU-062	Sign Up (verify of input)
6) password	Symbols (123abc!+-@^&*%#,./?абвABCАБВ)	Smoke
SU-063		Only spaces	Extended
SU-064		Spaces in the middle, before and after text	Smoke
SU-065		length (max / min)	Extended
SU-066		Entering tags	Extended
SU-067		Entering wildcards	Extended
SU-068		Entering a script	Extended

FP-001	Forgot Password
(common verify)	Correct values (email / number phone)	Smoke
FP-002		Incorrect values (email / number phone)	Smoke
FP-003		Empty field	Extended
FP-004		Working of button (Cancle)	Smoke
FP-005		Working of button (Search)	Smoke
FP-006		Working of button (Not You?)	Smoke
FP-007		Working of button (Continue)	Smoke
FP-008		Working of link (No longer have access to these?)	Extended
FP-009		Getting the code on email	Smoke
FP-010		Getting the code on phone	Smoke
FP-011		Correct code	Smoke
FP-012		Incorrect code	Smoke
FP-013		Without code	
FP-014		Working of link (Didn’t get a code?)	Smoke
FP-015		Correct (new password)	Smoke
FP-016		Incorrect (new password)	Smoke
FP-017		Working of button (hide / show) password	Smoke
FP-018		Working of button (symbol «?»)	Smoke
FP-019		Working of button (closed / OK)	Smoke
FP-020		Working of button (skip)	Smoke
FP-021	Forgot Password
1) radio button	Functioning (on/off)	Smoke
FP-022		There can't be less than two radio buttons	Extended
FP-023		By default, one radio button must be enabled	Extended
FP-024		Activation by clicking on both the symbol and the text	Smoke

