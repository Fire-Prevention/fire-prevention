# Fighting System Suggestions

<table>
  <tr>
    <th> Title </th>
    <th> Description </th>
  </tr>
  <tr>
    <td> Brief Description </td>
    <td>
      Use case of system sending suggestions to the user to improve the extinguishing strategy. It starts when the system detects an improvement available and ends when the user is notified.
    </td>
  </tr>
  <tr>
    <td> Actors </td>
    <td>
      <ul>
          <li>User</li>
          <li>System</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td> Pre-Conditions </td>
    <td>
      <ul>
          <li>The propagation prediction is running</li>
          <li>The system has identified an action that can be taken to improve the extinguishing strategy</li>
          <li>The user is at Dashboard</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td> Basic Flow </td>
    <td>
      <ol>
          <li>System sends a notification to the user with the action to take</li>
          <li>The system offers pre-made missions for the user to start</li>
          <li>The system offers pre-made emergency alerts for the user to send</li>
      </ol>
    </td>
  </tr>
  <tr>
    <td> Alternate/Exception Flows </td>
    <td>
      2b. <ol type="I">
        <li>User clicks "Start Mission"</li>
        <li>Continue to Start Mission use case</li>
      </ol>
      3b. <ol type="I">
        <li>User clicks "Send Emergency Signal"</li>
        <li>Continue to Send Emergency Signal use case</li>
      </ol>
    </td>
  <tr>
    <td> Post Conditions </td>
    <td>
        None
    <td>
  </tr>
  <tr>
    <td>Supplemental Requirements</td>
    <td>None</td>
  </tr>
<table>
