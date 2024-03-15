<table>
  <tr>
    <th>Views</th>
    <th>Components</th>
    <th>ViewModels</th>
  </tr>
  <tr>
    <td rowspan="5"><img src="../img/account_login.png"
     alt="Markdown Monster icon"
     style="margin-left: auto; margin-right: auto; width: 70%; display: block" /></td>
    <td >HeaderImage</td>
    <td >props.imgSrc <br>=> headerImgSrc 
  </tr>
  <tr>
    <td rowspan="2"> Text <br> Email <br> Email input <br> Password <br> Password Input</td>
    <td >props.property <br>=> email <br>=> password</td>
  </tr>
  <tr>
    <td>props.credentials <br>=> SetEmail <br>=> SetPassword</td>
    
  </tr>
  <tr>
    <td rowspan="2">Login</td>
    <td >props.label <br>=> Login </td>
  </tr>
  <tr>
    <td >props.handleClick <br>=> handleLogin </td>
  </tr>
  <tr>
    <td rowspan="8"><img src="../img/account_management.png"
     alt="Markdown Monster icon"
     style="margin-left: auto; margin-right: auto; width: 70%; display: block" /></td>
    <td >HeaderImage</td>
    <td >props.imgSrc <br>=> headerImgSrc 
</tr>
<tr>
    <td>userAvatar</td>
    <td >props.imgSrc => userImgURI</td>
  </tr>

  <tr>
    <td rowspan="2">userInfo</td>
    <td >props.name => userName</td>
  </tr>
  <tr>
    <td >props.email => userEmail</td>
  </tr>
  <tr>
    <td rowspan="3">accountManagagementButtons</td>
    <td >props.text => text</td>
  </tr>
  <tr>
    <td >props.image => imgSource</td>
  </tr>
  <tr>
    <td >props.handleClick => handleClick</td>
  </tr>
  <tr>
    <td>Logout</td>
    <td >props.handleClick => handleLogoutClick</td>
  </tr>
  <tr>
    <td rowspan="3"><img src="../img/account_saved.png"
     alt="Markdown Monster icon"
     style="margin-left: auto; margin-right: auto; width: 70%; display: block" /></td>
    <td>Saved Products</td>
    <td >ViewModelRow</td>
  </tr>
</table>
