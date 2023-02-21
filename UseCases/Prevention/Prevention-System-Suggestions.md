# Prevention System Suggestions

<table>
  <tr>
    <th> Title </th>
    <th> Description </th>
  </tr>
  <tr>
    <td> Brief Description </td>
    <td>
      Use case of system sending suggestions to the user to reduce the risk of a fire. It starts when the system detects an improvement available and ends when the user checks it off as done.
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
          <li>The simulation has run at least once</li>
          <li>The risk score has been calculated</li>
          <li>The system has identified an action that can be taken to reduce the risk score</li>
          <li>The user is at Dashboard</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td> Basic Flow </td>
    <td>
      <ol>
          <li>System sends a notification to the user with the action to take, and the precentage of risk it will reduce</li>
          <li>The notification is displayed as a pending task</li>
          <li>The user takes appropriate action</li>
          <li>The user marks the task as done</li>
          <li>Continue at Update Risk Score use case</li>
      </ol>
    </td>
  </tr>
  <tr>
    <td> Alternate/Exception Flows </td>
    <td>
    </td>
  <tr>
    <td> Post Conditions </td>
    <td>
        None
    <td>
  </tr>
  <tr>
    <td>Supplemental Requirements</td>
    <td>Based on time-of-arrival, communication-loss, and risk-factor simularions. Make sure to mention that it takes input from the Calculate Risk levels use case.</td>
  </tr>
<table>
