# Welcome
This is the repo for the LPR website.

## How to add publications
To prevent unintentional edits to the website source code, users cannot edit the main branch directly. To add new entries to the bibliography file, you will need to create a merge request. It's very easy and all the editing can be done through the Gitlab interface.

Follow these simple steps:
* Click on the `publication.bib` file in the root folder and start editing it (click on the blue `Edit` button).
* Add your citations using the following structure:
    ```
    @inproceedings{gallo2022mega, % First author's last name
                                % + year
                                % + project keyword
    archiveprefix = {arxiv}, % Do not change this
    eprint        = {NNNN.NNNN}, % Arxiv ID
    title         = {The Title: {U}se brackets to preserve capitalization, e.g., {3D}},
    author        = {List of authors},
    booktitle     = {Conference name},
    year          = {Year},
    website       = {Project website}
    }
    ```
    *NOTE:* To ensure consistency, for the conference name, pick the string from the top of the file.
* Leave all the options unchanged (make sure that `Start a new merge request with these changes` is checked) and hit `commit changes`.
* Optional: Edit the title and comments that the approver will see.
* Add Orazio Gallo and yourself to the assignees to make sure that notifications flow correctly.
* Hit `Create merge request`.

Questions? Email *[Orazio Gallo](ogallo@nvidia.com)*.