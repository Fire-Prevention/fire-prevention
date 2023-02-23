# Detection Verify Ignition Mission

<table>
  <tr>
    <th> Title </th>
    <th> Description </th>
  </tr>
  <tr>
    <td> Brief Description </td>
    <td>
      Use case of a mission in progress for the purpose of verifying a reported ignition. It starts when the user receives an ignition alert and ends when the ignition is verified as true or false.
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
          <li>An ignition has been reported (see Ignition Alarm use case)</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td> Basic Flow </td>
    <td>
      <ol>
          <li>During the mission the personnel and/or equipment (eg. drone) checks an area to verify the ignition</li>
          <li>The ignition is detected</li>
          <li>An ignition alert is sent out</li>
          <li>The system switches to Fighting conditions</li>
          <li>Mission ends</li>
      </ol>
    </td>
  </tr>
  <tr>
    <td> Alternate/Exception Flows </td>
    <td>
      2b. <ol type="I">
        <li>The ignition is not detected</li>
        <li>The false alarm is logged to the system</li>
        <li>Continue at step 5</li>
        <li></li>
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
