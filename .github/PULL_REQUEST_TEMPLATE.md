*Issue #, if available:*

*Description of changes:*
     A new parameter was added --transform which causes cfn-lint to output the transformed template to a .json file in the same directory as the original template.

    Created a new method in the Template class which creates a new file containing the transformed template.

    The run_cli method was  updated to call the above mentioned method.

By submitting this pull request, I confirm that you can use, modify, copy, and redistribute this contribution, under the terms of your choice.
