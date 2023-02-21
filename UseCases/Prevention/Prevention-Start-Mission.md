# Prevention Start Mission

<table>
  <tr>
    <th> Title </th>
    <th> Description </th>
  </tr>
  <tr>
    <td> Brief Description </td>
    <td>
      Use case of a user starting a mission. It starts when the user clicks on "Start Mission" and ends when the mission is in progress.
    </td>
  </tr>
  <tr>
    <td> Actors </td>
    <td>
      <ul>
          <li>User</li>
          <li>System</li>
          <li>Personnel</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td> Pre-Conditions </td>
    <td>
      <ul>
          <li>User is at Missions Screen</li>
          <li>There are available equipment and/or personnel for the mission</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td> Basic Flow </td>
    <td>
      <ol>
          <li>User clicks "Start Mission"</li>
          <li>A prompt is displayed for more details</li>
          <li>User sets equipment and/or people to go on the mission</li>
          <li>User sets type of mission</li>
          <li>User clicks "Start"</li>
          <li>Mission of specified type starts</li>
      </ol>
    </td>
  </tr>
  <tr>
    <td> Alternate/Exception Flows </td>
    <td>
      1b. <ol type="I">
        <li>A mission is scheduled to start at this time</li>
        <li>Continue at step 6</li>
      </ol>
      3b. <ol type="I">
        <li>The equipment and/or people are not available at that time</li>
        <li>User is prompted to select different equipment and/or personnel</li>
        <li>Continue at step 3</li>
      </ol>
    </td>
  <tr>
    <td> Post Conditions </td>
    <td>
        A mission is in progress.
    <td>
  </tr>
  <tr>
    <td>Supplemental Requirements</td>
    <td>None</td>
  </tr>
<table>
