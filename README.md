# Personal Website

### A "Portfolio" Website to describe and express myself to potential employers.

This website is currently being developed using Microsoft Visual Studio Code. It utilizies basic HTML, CSS, and Javascript.
Project files are stored inside the "Port" folder (short for portfolio)

Full credit to Jaimie Wilson for one of the scripts and the Google Sheets Script used for the contact form.
The referenced repository can be found here:
https://github.com/jamiewilson/form-to-google-sheets

### Hosting
This website is not currently being hosted. I am exploring options, but given the mildly unprofessional nature of this project, it stands to reason that it serves better as experience than an acute representation of myelf.

To view this website, the current recommeded method is simply to clone this repository, open the "port" folder on Visual Studio Code, and run the website with the Live Server extension.

Visual Studio Code can be downloaded at: https://code.visualstudio.com
Once the installer has been run, navigate to the extensions tab. The only extensions used in this website are ".NET Install Tool" and "Live Server". After these have been installed, go to File -> Open Folder, and select the location of the port folder. The index.html and style.css will appear on the left column. Open the HTML file and right click anywhere, then select "Open with Live Server".

### Components
As aforementioned, this Website is built with HTML 5, CSS, and embedded JavaScript. Additional components include images, borrowed scripts from Jaimie Wilson, and several icons from fontawesome.com.

The site is simple; it consists of one page with multiple sections, rather than a different web page for each spot. The only external component is a Google Sheet that is linked to the contact form. When using the form, a "valid" email address is required, and when submitted, the name, email, and message are delivered to unique columns on a spreadsheet. This was made possible by the scripting provided by Wilson's public repository.

Moderate mobile support is provided. A sliding menu presents the sections to avoid clutter, and the images, sections, and font-sizes are all adjusted for smaller screens.

