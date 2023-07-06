# GISA Testing Issues

This repository is for reporting bugs and issues uncovered when testing GISA's redistributable.

## To report an issue

1. Go to the [issues tab](https://github.com/NETL-RIC/GISA-testing-issues/issues) for this repository.
2. Click on "New Issue".
3. Enter a title and description of the bug, enhancement, or other issue being reported.
4. Select one or more labels using the "Labels" box to the right of the description box.
5. When finished, click "Submit New Issue".

## General guidance for reporting bugs / issues

* Include a description of what you were doing when the bug manifested. Provide enough detail for someone unfamiliar with the tool to recreate.
* If possible, provide a stacktrace of the issue. This is a block of text that will show up in the console window identifying where the python error occurred. See image below for example
  * Simply copy and paste this text into the issue description box.
  * Sometimes, a bug/error will cause a full crash, closing the console window. In these cases, you'll want to launch the module from the command prompt:
    1. open `cmd.exe`
    2. Navigate to the directory with the executable: type `cd <path>` where _<path>_ is the full path to the directory. Press _Enter_.
    3. Type the name of the executable, and press _Enter_ this will launch the executable, with the command prompt capturing the trackback on crash.
* Use labels for issues. If you encounter what you think is a bug, apply a "bug" label. Is there a feature missing that should be added? Apply the "enhancement" label.
* Expect followup questions; necessary details are often missed. Issues are akin to forum threads, with full and ongoing discussions being carried out for each issue.
* Expect to be asked to test fixes for any reported bugs. This will involve downloading a new version of the redistributable and recreating the conditions that originally caused the bug to manifest.
  * If the fix is confirmed, the associated issue is typically _Closed_, indicating that the issue has been dealt with.


## Example Traceback
![image](https://github.com/NETL-RIC/GISA-testing-issues/assets/4934597/6de1a063-a1a3-45a2-961b-f20f0c229d33)
