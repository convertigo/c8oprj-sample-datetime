
# ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/core/images/project_color_16x16.png?raw=true "Project") datetime

How to use DateTime

<details><summary><span style="color:DarkGoldenRod"><i>Connectors</i></span></summary><blockquote><p>


## ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/connectors/images/sqlconnector_color_16x16.png?raw=true "SqlConnector") void

void connector, replace or don't use it

<details><summary><span style="color:DarkGoldenRod"><i>Transactions</i></span></summary><blockquote><p>


### ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/transactions/images/sqltransaction_color_16x16.png?raw=true "SqlTransaction") void

does nothing
</p></blockquote></details>
</p></blockquote></details>

<details><summary><span style="color:DarkGoldenRod"><i>Sequences</i></span></summary><blockquote><p>


## ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/sequences/images/genericsequence_color_16x16.png?raw=true "GenericSequence") data_by_date

Returns the 'date' variable

<span style="color:DarkGoldenRod">Variables</span>

<table>
<tr>
<th>
name
</th>
<th>
comment
</th>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/variables/images/variable_color_16x16.png?raw=true "  alt="RequestableVariable" >&nbsp;date
</td>
<td>

</td>
</tr>
</table>

</p></blockquote></details>

<details><summary><span style="color:DarkGoldenRod"><i>Mobile Application</i></span></summary><blockquote><p>


## ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/core/images/mobileapplication_color_16x16.png?raw=true "MobileApplication") Application

NGX DateTime component usage.

<details><summary><span style="color:DarkGoldenRod"><i>Pages</i></span></summary><blockquote><p>


<details><summary><b>Page_datetime_button</b> : <ul></summary><blockquote><p>


### ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/pagecomponent_color_16x16.png?raw=true "PageComponent") Page_datetime_button

<ul>
<li>Use of custom tag ion-datetime-button.</li>
<li>Datetime picker is in a Modal component.</li>
<li>Date value bound to a global variable component ("my_picked_date").</li>
<li>Date value is used to call a sequence that returns the provided date when the close modal button is clicked.</li>
</ul>
<br/>
<img src="doc/ion_datetime_button_modal.png" />
</p></blockquote></details>

<details><summary><b>Page_datetime_popover</b> : <ul></summary><blockquote><p>


### ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/pagecomponent_color_16x16.png?raw=true "PageComponent") Page_datetime_popover

<ul>
<li>DateTime picker displayed by clicking the input.</li>
<li>Datetime picker is in a Popover component.</li>
<li>Date value is formatted in the input field ("dd MMM yyyy").</li>
<li>Unformatted Date value is used to call a sequence that returns the provided date on "ionChange" event of the input item (my_date value is declared in the Page class).</li>
<li>DateTime "ionChange" event is used to display value in a Toast component.</li>
</ul>
<br/>
<img src="doc/input_popover.png" />
</p></blockquote></details>
</p></blockquote></details>
</p></blockquote></details>
