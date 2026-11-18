# Baggage Database Lab

An interactive version of the American Airlines baggage handling database activity.
Students define fields for Flight, Passenger, Ticket, and Baggage; name relationships;
and choose cardinalities at both ends. They then download a PNG containing their names
and their complete solution.

## Publish on GitHub Pages

1. Create a GitHub repository, or open the repository you want to use.
2. Upload `index.html` to the top level of the repository. Keep that exact filename.
   The page is self-contained; it does not need any other files.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select **main** (or the branch where you uploaded the page), choose **/(root)**,
   and click **Save**.
6. After GitHub finishes publishing, copy the website URL shown on the Pages settings
   screen and share that link with students.

For a free personal GitHub account, use a public repository for GitHub Pages.
The included `.nojekyll` file is optional and tells GitHub to serve the files directly.
Do not upload the ZIP itself; unzip it and upload its contents, or upload only `index.html`.

Official instructions:
https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Student use

- Enter Student 1’s full name. Student 2 is optional for pairs.
- Start with the four provided tables. Use **Add table** above the workspace to create
  additional tables with unique names. Each new table starts with four blank field rows.
- Add at least four distinct field names to each table.
- Use **Rename** or **Remove** on a student-added table to manage it. Removing a table
  asks for confirmation and also removes any relationships connected to that table.
  The four starter tables remain part of the activity.
- Use **Add relationship** to select two tables, name the connection, and specify
  cardinalities at both ends. Relationships can be edited or removed.
- Switch to **Diagram** to view the model. The full relationship list also appears below it.
- Add modeling notes if needed.
- Choose **Export PNG**, review the image, then choose **Download PNG**.
- Upload the downloaded image to the course assignment. The webpage does not submit it automatically.

## Working alone or in pairs

Pairs share one device and enter both names. This is not a simultaneous editing service.
Progress is saved in the current browser only. It does not sync between devices or browsers.
Names and solutions are not sent to a server by this application. Clearing browser data
or choosing **Start over** clears the saved solution. On a shared device, start over
before the next student or team begins.

## Teaching notes

The activity opens with blank fields and no suggested relationships. It does not include
an answer key or grade a model. Completion messages check entered field names and
connections, not the correctness of the design. Students can export a partial draft
after reviewing the warnings.

Saved work from the original four-table version is preserved when the page is replaced
at the same address in the same browser. Added tables, names, fields, and relationships
are saved together. The diagram grows to include every table.

The PNG includes the activity title, student names, local export date, all field rows,
the relationship diagram, full relationship details, both cardinalities, and any notes.

## Open without hosting

Open `index.html` in a modern browser. No installation, external libraries, or internet
connection is required by the page itself. For a class, the hosted GitHub Pages link is
the simplest way to distribute it. On narrow screens, the editing controls stack vertically
and the diagram can be scrolled horizontally.
