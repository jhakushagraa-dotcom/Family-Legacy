DR. HARI'S LEGACY — FAMILY TREE PROTOTYPE UPDATE

Contents:
- index.html: homepage
- branch.html: family branch tree, member profile preview, and Add Family Member form
- assets/: family photographs

PUBLISHING TO YOUR EXISTING GITHUB REPOSITORY (mylegacy)
1. Extract this ZIP on your computer.
2. Upload/replace index.html and branch.html in the ROOT of your repository.
3. Upload the contents of the assets folder into the existing root-level assets folder, allowing the new files to be added/replaced. Keep all filenames and folder structure.
4. Commit the changes. GitHub Pages will redeploy automatically.

IMPORTANT CURRENT LIMITATIONS
- The Add Family Member form is a front-end prototype. Entries are stored in the current browser only (localStorage), not shared with other family members/devices.
- The common ID/password and secure editing are intentionally deferred, as requested.
- Edit Member currently displays a notice that protected editing will be connected later.
- Member photo upload is currently limited to 10 MB in this browser-only prototype. The earlier 1 GB target requires backend storage and will be revisited when the shared database is implemented.
- This first tree prototype supports one spouse and children for the selected branch. Children are sorted oldest-first when a valid DOB is supplied.
- The adult View Family action is shown only for members whose calculated age is 18 or older. Multi-branch navigation for newly added members is a later enhancement.

AGE RULE
Age is calculated from the complete date of birth against the device's current date. A missing DOB displays: "Your age will be determined by your given DOB."

DESIGN
Antique gold relationship labels and controls; warm ivory names and profession; muted ivory metadata; dark archival theme.
