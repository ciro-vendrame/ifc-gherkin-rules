| File name | Expected result | Error | Description |
|-------|---------|--------|-------|
| pass-alb002-alignment-layout| success |    | Files for fails generated by generate_fails.py, includes more information (or add more extended here/summarized in generate python?)|
| fail-alb002-scenario01-nested_attributes_IfcAlignment| fail | The instance IfcAlignment is nesting two instances of IfcAlignmentHorizontal, two instances of IfcAlignmentVertical and two of IfcAlignmentCant. The instance IfcAlignment #906 is not nesting anything | Error is descriptive or exactly the error in pytest? If exactly, multiple rows for errors in each file? New file for each error?  |
| fail-alb002-scenario02-two_alignments| fail | The following 2 instances were encountered: IfcAlignment #23, IfcAlignment #906 | For IfcAlignmentHorizontal, IfcAlignmentVertical and IfcAlignmentCant|    
| fail-alb002-scenario03-no_direction| fail | The instance #906=IfcAlignment is nesting #907=IfcWall | Includes errors for scenario 2 |
| fail-alb002-scenario04-alignment_segments| fail | The instance (s) #28=IfcAlignmentHorizontal is assigned to #906=IfcWall | @todo IfcAlignmentVertical, IfcAlignmentCant. As well as empty list/typo's?   |