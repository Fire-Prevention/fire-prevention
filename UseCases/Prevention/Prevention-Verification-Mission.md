# Prevention Verification Mission

<table>
  <tr>
    <th> Title </th>
    <th> Description </th>
  </tr>
  <tr>
    <td> Brief Description </td>
    <td>
      Use case of a mission in progress for the purpose of verifying a reported event. It starts when the mission is in progress and ends when a report is made, marking the event as verified and true, or verified and false.
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
          <li>A mission has already started (see Start Mission Use Case)</li>
          <li>An event has been reported for verification</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td> Basic Flow </td>
    <td>
      <ol>
          <li>During the mission the personnel and/or equipment (eg. drone) checks an area to verify the reported event (eg. installation of a new fire hydrant completed)</li>
          <li>Once verified the personnel that checked the validity of the claim reports it back to the system as true</li>
          <li>The system registers the new event to the system as suitable (eg. add fire hydrant to the water source map)</li>
          <li>Mission ends</li>
      </ol>
    </td>
  </tr>
  <tr>
    <td> Alternate/Exception Flows </td>
    <td>
      2b. <ol type="I">
        <li>The personnel reports it back as false</li>
        <li>Continue at step 4</li>
        <li></li>
      </ol>
      2c. <ol type="I">
        <li>The event cannot be verified as true or false</li>
        <li>Notify the user</li>
        <li>Continue at step 4</li>
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
    <td>This is to verify general things, like the existence of new equipment, new structural assets, damage, etc.</td>
  </tr>
<table>
