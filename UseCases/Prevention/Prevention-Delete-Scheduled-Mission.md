# Prevention Delete Scheduled Mission

<table>
  <tr>
    <th> Title </th>
    <th> Description </th>
  </tr>
  <tr>
    <td> Brief Description </td>
    <td>
      Use case of user deleting a scheduled mission. It starts when the user clicks "Delete Mission" and ends when the mission no longer appears in the scheduled missions.
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
          <li>The user is in Missions Screen</li>
          <li>There are one or more scheduled missions</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td> Basic Flow </td>
    <td>
      <ol>
          <li>User clicks "Delete Mission"</li>
          <li>System displays a prompt "Are you sure?"</li>
          <li>User clicks "Yes"</li>
          <li>Mission is deleted</li>
          <li>Any personnel scheduled to participate, is notified of the change</li>
      </ol>
    </td>
  </tr>
  <tr>
    <td> Alternate/Exception Flows </td>
    <td>
      3b. <ol type="I">
        <li>User clicks "No"</li>
        <li>End Case</li>
        <li></li>
      </ol>
    </td>
  <tr>
    <td> Post Conditions </td>
    <td>
        The mission no longer appears in the scheduled missions and any equipment and/or personnel involved is now available for that time slot.
    <td>
  </tr>
  <tr>
    <td>Supplemental Requirements</td>
    <td>None</td>
  </tr>
<table>
