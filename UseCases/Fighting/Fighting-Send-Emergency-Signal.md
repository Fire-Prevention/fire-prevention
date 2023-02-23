# Fighting Send Emergency Signal

<table>
  <tr>
    <th> Title </th>
    <th> Description </th>
  </tr>
  <tr>
    <td> Brief Description </td>
    <td>
      Use case of user sending an emergency signal to the dispatched personnel. It starts when User clicks "Send Emergency Signal" and ends when the signal is sent and received by the personnel.
    </td>
  </tr>
  <tr>
    <td> Actors </td>
    <td>
      <ul>
          <li>System</li>
          <li>Personnel</li>
          <li>User</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td> Pre-Conditions </td>
    <td>
      <ul>
          <li>There is a reliable channel of communication for the signal to be sent</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td> Basic Flow </td>
    <td>
      <ol>
          <li>User needs to send an Emergency alert (eg. for evacuation)</li>
          <li>User clicks "Send Emergency Signal"</li>
          <li>User inputs the message to be sent</li>
          <li>The message is sent with priority to all personnel</li>
      </ol>
    </td>
  </tr>
  <tr>
    <td> Alternate/Exception Flows </td>
    <td>
      1b. <ol type="I">
        <li>System suggests (based on the simulation data) that an emergency signal should be sent</li>
        <li>Continue at step 2</li>
        <li></li>
      </ol>
      3b. <ol type="I">
        <li>The message is autofilled based on the system suggestions</li>
        <li>Continue at step 4</li>
    </td>
  <tr>
    <td> Post Conditions </td>
    <td>
        The message is sent to all the personnel that is dispatched prompting them to action (eg. evacuation).
    <td>
  </tr>
  <tr>
    <td>Supplemental Requirements</td>
    <td>None</td>
  </tr>
<table>
