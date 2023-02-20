# Prevention Delete Equipment

<table>
  <tr>
    <th> Title </th>
    <th> Description </th>
  </tr>
  <tr>
    <td> Brief Description </td>
    <td>
      Use case of user deleting equipment listed in the list of equipments. It starts with the user selecting an equipment from the list to delete and ends when the equipment no longer appears in the list.
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
          <li>One or more equipment are connected to the system</li>
          <li>Equipment appears in the list of equipments</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td> Basic Flow </td>
    <td>
      <ol>
          <li>User clicks the "Delete" button next to the equipment they want to delete</li>
          <li>System display a prompt "Are you sure?"</li>
          <li>User clicks "Yes"</li>
          <li>Equipment is deleted and removed from the list</li>
      </ol>
    </td>
  </tr>
  <tr>
    <td> Alternate/Exception Flows </td>
    <td>
      3b. <ol type="I">
        <li>User clicks "No"</li>
        <li>End case</li>
      </ol>
    </td>
  <tr>
    <td> Post Conditions </td>
    <td>
        The equipment no longer appears in the list of equipment available in the system.
    <td>
  </tr>
  <tr>
    <td>Supplemental Requirements</td>
    <td>None</td>
  </tr>
<table>
