## Setup and Use of Trailbase

### Running Trailbase

To run the application, use the command below in the Terminal:

`./trail run`

To access it in the browser, run the application (above) and then switch to the _Ports_ tab. Here select the _Open in Browser_ button next to the forwarded address button for the port 4000. Once you do this, you **must** append `/_/admin` to the URL in the Browser for you to get the login page.

**NB:** To access the Trailbase server from multiple computers (i.e., in a group setting, or when developing from a different Codespace), you MUST change the Visibility of the port from Private to Public BEFORE opening it in the browser. To do this, you should right click on the Port 4000 row, select _Port Visibility_ and then _Public_.

If the port 4000 line item is missing in the _Ports_ tab, select _Add Port_ and type in 4000. Then follow the instructions above for public visibility and opening in the browser.

To change the default user password (substituting the provided password with the new one):

`./trail user change-password admin@localhost s3cur3P4ssw0rd`

### Using Trailbase

Once you have Trailbase at the login screen, you can log in with the below default credentials, or any changed value, per the above.

Tables can be modelled interactively in the Table & View Browser (first tab, looks like a stacked cylinder), code can be written directly in the _SQL Editor_ (pencil on paper tab), and an ERD can be seen (mini ERD graph tab).

Somewhat minimal documentation is available at https://trailbase.io/getting-started/install


### Credentials
```
Username: admin@localhost
Password: s3cur3P4ssw0rd
```