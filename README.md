<!DOCTYPE html>
<html>
<head>
<style>
  table, tr, td {
  border: 1px solid black;
  border-collapse: collapse;
  padding: 10px;  
  vertical-align: middle;
}
tr.hide_right > td, td.hide_right
     {
        border-right-style:hidden;
      }

      
</style>
</head>
<body>
<table style="width:100%">
    <tr>
        <td align="right"><b>Last Name</b></td>
          <td colspan="3">
              <textarea>Nakov</textarea>
          </td>
    </tr>
    <tr>
        <td align="right"><b>First Name</b></td>
          <td colspan="3">
            <textarea>Svetlin</textarea>
          </td>
    </tr>
    <tr>
        <td align="right"><b>Address</b></td>
          <td colspan="3">
            <textarea wrap="soft">17 Hristo Botev Str. floor 3, apt. 12
            </textarea>
          </td>
    </tr>
    <tr>
        <td align="right"><b>City</b></td>
          <td>
            <input type="text" name="city"/>
          </td>
          <td>State</td>
          <td>
              <input type="text" name="state"/>
          </td>
    </tr>
    <tr>
        <td align="right"><b>Zip/Postal Code</b></td>
          <td colspan="3">
            <input type="text" name="zipCode"/>
          </td>
    </tr>
    <tr>
        <td align="right"><b>Country</b></td>
          <td colspan="3">
              <select>
                <option value="Country">Bulgaria</option>
			  </select>
          </td>
    </tr>
    <tr>
        <td align="right"><b>Phone (country code,<br> area code, number)</b></td>
           <td colspan="3">
           <p text-align="justify",style="font-size:80%;">+(
           <input type="text2" value="359">)
           <input type="text2" value="88">  -
           <input type="text" value="8334343">     
        </td>
    </tr>
      <tr>
        <td align="right"><b>E-Mail</b></td>
          <td colspan="3">
            <input type="text" name="email"/>
          </td>
     <tr>
        <td align="right"><b>Birth Date</b></td>
           <td colspan="3">
           <p text-align="justify",style="font-size:80%;", font-family="Times New Roman">Month
           <input type="text3" value="06">  Day
           <input type="text3" value="14">  Year (4 digit)
           <input type="text2" value="1980">     
        </td>
    </tr>
  <tr>
        <td align="right"><b>Gender</b></td>
          <td colspan="3">
              <select>
                <option value="Gender">Male</option>
			  </select>
          </td>
    </tr>
    <tr>
        <td align="right"><b>Starting Date</b></td>
          <td colspan="3">
              <input type ="radio" name="Start" value="" checked>Spring 2006
              <input type ="radio" name="Start" value="">Summer 2006
          </td>
    </tr>
    <tr>
        <td align="right"><b>Comment/Questions</b></td>
          <td colspan="3">
            <textarea rows="4" cols="50">
Please send me more information about the lodging
            </textarea>
          </td>
    </tr>
</table>
<div style="background-color:lightgreen", align="center">
 <input type="submit" value="Submit">
 <input type="submit" align="center" value="Clear This Form">
</div>

</body>
</html>
