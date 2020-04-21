# File naming conventions for Student_Project

## General goal
The most important thing is consistency and descriptivity, so that the name of the file immediately gives as much information as possible. This is done by using naming elements, so that files follow a pattern that is both human-readable and machine-friendly.

## Naming elements
Naming elements can contain:
	1. Project name: Student_Project
	2. Organization name/abbreviation: TUDelft, ErasmusMC, HollandPTC
	3. Subject
	4. Date or date range: For format always use YYYYMMDD, HHMMSS, or YYYYMMDDHHMMSS if needed.
	5. Experiment name/number
	6. Location or spatial coordinates
	7. Condition
	8. Version number
	9. Initials if needed, mostly for comments. Always in the form of LastnameInitial, e.g., PerkoZ.

## General rules:
	1. Always avoid all special characters, such as: ~ ! @ # $ % ^ & * ( ) + ` = { } | [ ] \ : " ; ' < > ? , /
	2. Do not use spaces. Use underscores (Input_File), dashes (Input-File), or camel case (InputFile)
	3. Naming elements should follow in order of importance, from general (most important) to specific (least important). E.g. use "ProjectName_WP3_TempMeasurement_20180930.xls" instead of "20180930_TempMeasurement_ProjectName_WP3.xls".
	4. Use leading zeros in sequential numbering, e.g., "001" instead of "1".
	5. Try to be reasonably short, but descriptive.
	6. When sharing as attachment or via portable device, prefix filenames with directory structure to provide extra context.

## Revision control for documents and reports (without version control system):
	1. Letters for different drafts, e.g.:
		a. _Rev0A - first draft (sent out to immediate supervisors)
		b. _Rev0B - second draft (sent out to internal collaborators)
		c. _Rev0C - third draft (sent out to external collaborators)
		d. _Rev0D,... - any further drafts
	2. Numbers for "final" formats, e.g., 0, 1, etc. E.g.:
		a. _Rev1: First final form
		b. _Rev1A: final form sent back to draft
		c. _Rev1B: second draft after first final form
		d. _Rev2: Second final form.
	3. Comments: "_RevX_LastnameInitial", e.g. "_Rev0A_DoeJ", "_Rev1_DoeJ"