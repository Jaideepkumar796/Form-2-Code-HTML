Form-2-Code-HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <form>
        <table align="center" width="60%" cellpadding="5px" border="1">
            <tr>
                <th colspan="4"><h2>Registration Form</h2></th>
            </tr>
            <tr>
                <td><label for="t1">Student Name</label></td>
                <td><input id="t1" type="text" placeholder="Enter Your Father's Name"></td>
                <td><input id="t2" type="text" placeholder="Middle Name"></td>
                <td><input id="t3" type="text" placeholder="last Name"></td>
            </tr>
            <tr>
                <td><label for="t2">Father's Name</label></td>
                <td><input id="t2" type="text" placeholder="Enter Your Father's Name"></td>
                <td><label for="t3">Mother's Name</label></td>
                <td><input id="t3" type="text" placeholder="Enter Your Mother's Name"></td>
            </tr>
            <tr>
                <td><label for="t4">Date of Birth</label></td>
                <td><input id="t4" type="date" name="dob"></td>
            <td><label>Gender</label></td>
        <td>
          <label for="r1">Male</label><input id="r1" type="radio" name="gender">
          <label for="r2">Female</label><input id="r2" type="radio" name="gender">
        </td>    
            </tr>
            <tr>
             <td><label>Category</label></td>
        <td>
          <label>Gen</label><input type="radio" name="cat">
          <label>OBC</label><input type="radio" name="cat">
          <label>SC/ST</label><input type="radio" name="cat">
        </td>
             <td><label>Handicapped</label></td>
        <td>
          <label>Yes</label><input type="radio" name="hand">
          <label>No</label><input type="radio" name="hand">
        </td>
      </tr>
           <tr>
            <td><label>Ex-Serviceman</label></td>
        <td>
            <label>Yes</label><input type="radio" name="ser">
            <label>No</label><input type="radio" name="ser">
        </td>
            <td><label>EWS</label></td>
        <td>
            <label>Yes</label><input type="radio" name="ews">
            <label>No</label><input type="radio" name="ews">
        </td>
           </tr>
           <tr>
            <td><label for="t5">Email ID</label></td>
            <td><input id="t5" type="email"></td>
            <td><label for="t6">Mobile NO.</label></td>
            <td><input id="t6" type="text" maxlength="11"></td>
           </tr>
            <td>state</td>
            <td>
                <select>
                  <option>Select any Option</option> 
                  <option>Uttar Pardesh</option> 
                  <option>Madhya Pardesh</option>     
                </select>
            </td>      
            <td>city</td>
            <td>
               <select>
                <option>Prayagraj</option>
                <option>Kanpur</option>
                <option>Bhopal</option>
               </select>
            </td>
            <tr>
                <td>Upload Photo</td>
                <td><input type="file"></td>
                <td>Upload Signature</td>
                <td><input type="file"></td>
            </tr>
            <tr>
                <td></td>
                <td colspan="3" align="center">
                <input type="button" value="Submit">
                </td>
            </tr>
        </table>
    </form>
</body>
</html>
