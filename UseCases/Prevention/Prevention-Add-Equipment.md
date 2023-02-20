# Prevention Add Equipment

<table>
  <tr>
    <th> Title </th>
    <th> Description </th>
  </tr>
  <tr>
    <td> Brief Description </td>
    <td>
      Use case of user adding equipment to the system. It starts when user clicks add equipment and ends when the equipment has been successfully added and can be accessed.
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
          <li>User must be at Equipment's Screen</li>
          <li>Equipment must be functional</li>
          <li>Equipment must be connected to the Network</li>
          <li>System must be connect to the Network</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td> Basic Flow </td>
    <td>
      <ol>
          <li>User clicks on "Add Equipment" Button</li>
          <li>A form appears with fields related to the equipment (Name, Serial Number, Type, etc.)</li>
          <li>User fills in the form fields</li>
          <li>User connects to the equipment from  a list of available equipment</li>
          <li>User clicks "Add"</li>
          <li>Equipment is connected successfully</li>
      </ol>
    </td>
  </tr>
  <tr>
    <td> Alternate/Exception Flows </td>
    <td>
      4b. <ol type="I">
        <li>The equipment is not visible in the list</li>
        <li>User can click "Scan again"</li>
        <li>End Case</li>
      </ol>
      6b. <ol type="I">
        <li>Connection fails</li>
        <li>End Case</li>
        <li></li>
        <li></li>
      </ol>
    </td>
  <tr>
    <td> Post Conditions </td>
    <td>
        The equipment is added to the system and can be accessed from all related lists of equipment.
    <td>
  </tr>
  <tr>
    <td>Supplemental Requirements</td>
    <td>We need to identify what kind of equipment the system supports and what network they use to connect (WiFi, Bluetooth, etc.)</td>
  </tr>
<table>
