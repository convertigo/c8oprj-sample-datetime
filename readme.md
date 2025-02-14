


# datetime

How to use DateTime


For more technical informations : [documentation](./project.md)

- [Installation](#installation)
- [Mobile Application](#mobile-application)
    - [Pages](#pages)
        - [Page_datetime_button](#page_datetime_button)
        - [Page_datetime_popover](#page_datetime_popover)


## Installation

1. In your Convertigo Studio use `File->Import->Convertigo->Convertigo Project` and hit the `Next` button
2. In the dialog `Project remote URL` field, paste the text below:
   <table>
     <tr><td>Usage</td><td>Click the copy button</td></tr>
     <tr><td>To contribute</td><td>

     ```
     datetime=https://github.com/convertigo/c8oprj-sample-datetime.git:branch=master
     ```
     </td></tr>
     <tr><td>To simply use</td><td>

     ```
     datetime=https://github.com/convertigo/c8oprj-sample-datetime/archive/master.zip
     ```
     </td></tr>
    </table>
3. Click the `Finish` button. This will automatically import the __datetime__ project


## Mobile Application

NGX DateTime component usage.

### Pages

#### Page_datetime_button

<ul>
<li>Use of custom tag ion-datetime-button.</li>
<li>Datetime picker is in a Modal component.</li>
<li>Date value bound to a global variable component ("my_picked_date").</li>
<li>Date value is used to call a sequence that returns the provided date when the close modal button is clicked.</li>
</ul>
<br/>
<img src="doc/ion_datetime_button_modal.png" />

#### Page_datetime_popover

<ul>
<li>DateTime picker displayed by clicking the input.</li>
<li>Datetime picker is in a Popover component.</li>
<li>Date value is formatted in the input field ("dd MMM yyyy").</li>
<li>Unformatted Date value is used to call a sequence that returns the provided date on "ionChange" event of the input item (my_date value is declared in the Page class).</li>
<li>DateTime "ionChange" event is used to display value in a Toast component.</li>
</ul>
<br/>

<img src="doc/input_popover.png" />



