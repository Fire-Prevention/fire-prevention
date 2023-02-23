<table>
  <tr>
    <th> Title </th>
    <th> Description </th>
  </tr>
  <tr>
    <td> Brief Description </td>
    <td>
      This use case allows a registered user to log in to the system and access their account. It starts when the system  detects propagation near an antenna (of the known infrastructure) and ends when the result is stored.
    </td>
  </tr>
  <tr>
    <td> Actors </td>
    <td>
      <ul>
          <li>System</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td> Pre-Conditions </td>
    <td>
      <ul>
          <li>The user must be registered in the system with a valid email and password.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td> Basic Flow </td>
    <td>
      <ol>
          <li>The user navigates to the login page of the system</li>
          <li>The system displays the login form, which includes fields for entering the user's email and password</li>
          <li>The user enters their login and password in the respective fields</li>
          <li>The user clicks on the "Login" button</li>
          <li>The system validates the email and password entered by the user.</li>
          <li>If the login and password are correct, the system redirects the user to their dashboard or the main page of the system.</li>
      </ol>
    </td>
  </tr>
  <tr>
    <td> Alternate/Exception Flows </td>
    <td>
       5b. <ol type="I">
        <li> If the system detects that the user has entered an incorrect login or password, it displays an error message indicating that the email or password is incorrect.</li>
        <li>Continue at step 3</li>
      </ol>
    </td>
  <tr>
    <td> Post Conditions </td>
    <td>
        The user is logged in and can access the system.
    <td>
  </tr>
  <tr>
    <td>Supplemental Requirements</td>
    <td>None</td>
  </tr>
<table>
