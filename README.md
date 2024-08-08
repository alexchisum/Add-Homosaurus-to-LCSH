The normalization rules in the Norm Rules folder can be used to add Homosaurus terms to corresponding LCSH terms to bibliographic records in Alma.

Copy and paste the text from these four files and save as four normalization rules in the Alma MDE. Next, convert the normalization rules to four normalization processes in Alma configuration.

After you've created normalization processes, create a set of bib records containing the LCSH terms. 

The list of terms can be found in the LCSH_exactMatch_prefLabel column in the Homosaurus_lcshMatches Excel spreadsheet. In Alma Analytics create a report that identifies bibs containing these subject terms. Use the Titles subject area and run a filter on Subjects; paste your LCSH terms into this filter. Be sure to add a column for MMS ID. Save your report.

Next, create an Itemized set based on this report using the "Add items to set - from Analytics" function.

Finally, run your four normalization processes as jobs on the set you created. This will supplement any LCSH terms in the 650 $a with corresponding Homosaurus terms.
