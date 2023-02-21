# Prevention Schedule Mission

<table>
  <tr>
    <th> Title </th>
    <th> Description </th>
  </tr>
  <tr>
    <td> Brief Description </td>
    <td>
      Use case of user scheduling a mission to start at a specific time. It starts when the user clicks "Schedule Mission" and ends when the mission is scheduled.
    </td>
  </tr>
  <tr>
    <td> Actors </td>
    <td>
      <ul>
          <li>System</li>
          <li>User</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td> Pre-Conditions </td>
    <td>
      <ul>
          <li>User is at "Missions Screen"</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td> Basic Flow </td>
    <td>
      <ol>
          <li>User clicks "Schedule mission"</li>
          <li>A prompt is displayed for more details</li>
          <li>User sets time and place of the mission</li>
          <li>User sets equipment and/or people to go on the mission</li>
          <li>User sets type of mission</li>
          <li>User clicks "Save"</li>
          <li>The mission is added to the schedule</li>
      </ol>
    </td>
  </tr>
  <tr>
    <td> Alternate/Exception Flows </td>
    <td>
     4b. <ol type="I">
        <li>The equipment and/or people are not available at that time</li>
        <li>User is prompted to pick a different time</li>
        <li>Continue at step 3</li>
      </ol>
    </td>
  <tr>
    <td> Post Conditions </td>
    <td>
        The new mission is added to the schedule.
    <td>
  </tr>
  <tr>
    <td>Supplemental Requirements</td>
    <td>None</td>
  </tr>
<table>
