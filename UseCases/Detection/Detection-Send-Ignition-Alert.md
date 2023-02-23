# Send Ignition Alert

<table>
  <tr>
    <th> Title </th>
    <th> Description </th>
  </tr>
  <tr>
    <td> Brief Description </td>
    <td>
      Use case of system sending an ignition alert after an ignition has been verified. It starts when an igniton is verified and ends when the alert has been sent to all configured contacts (and platforms).
    </td>
  </tr>
  <tr>
    <td> Actors </td>
    <td>
      <ul>
          <li>System</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td> Pre-Conditions </td>
    <td>
      <ul>
          <li>There are contacts in the configuration file</li>
          <li>An ignition has been verified</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td> Basic Flow </td>
    <td>
      <ol>
          <li>The system sends an alert about the location of the detected fire</li>
      </ol>
    </td>
  </tr>
  <tr>
    <td> Alternate/Exception Flows </td>
    <td>
      None
    </td>
  <tr>
    <td> Post Conditions </td>
    <td>
        Contacts have been alerted about the detected fire.
    <td>
  </tr>
  <tr>
    <td>Supplemental Requirements</td>
    <td>This one is a bit small maybe merge it with another use case</td>
  </tr>
<table>
