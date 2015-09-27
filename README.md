# jQuery-Autocomplete
The objective of the assignment is to create an autocomplete feature using HTML, CSS, jQuery/jQuery(UI) which is commonly used in search engines. Assignment is only worth 8%.

####Requirements:
1. [x] Implement basic functionality: when user types in abc, list all strings in datafile that contain abc anywhere in the strings.
	1. [x] +5 marks – when type in a, you should list all strings in the data file that contain a anywhere in the string.
	2. [x] +10 marks - use blue font to display the first matched substring and bold font for the remaining part of the suggestion. User types in ‘tab’, like ‘database systems’ will be shown.
	3. [x] +5 marks – use blue font display all the matched substring in each item
2. [x] Implement extended function: scrollable results. When displaying a long list of options, set the max-height for the autocomplete menu, scroll through the results. + 20 marks
3. [x] Implement extended function: a categorized search result. + 10 marks
	1. [x] +10 marks display the category name in red color.
	2. [x] +10 marks display items separately that don’t belong to any category
4. [x] Implement extended function: multiple values. Type something to see suggestions. Select a value, then continue typing to add more (automatically joined by ',').
	1. [x] +10 marks we can input multiple terms. For each term, the autocomplete function works
	2. [x] +10 marks all the input terms should be displayed in the input box
	3. [ ] +10 marks for every input term, can fulfill all the requirements as mentioned before. (biggest issue: match substring for multiple values)