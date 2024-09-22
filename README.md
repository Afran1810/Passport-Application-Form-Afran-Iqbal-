<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Passport Application Form</title>
</head>
<body>
    <form>
        <h1>PASSPORT APPLICATION-STAGE 1</h1>
        <h3><p>Before filling up the online application form read the guidelines carefully.</p></h3>
        <h4><p>Fields marked with(*)are mandatory</p></h4>
        <hr>
        <h3>Passport Application Information</h3>
        <p>
            Applying In:*
            <select name="Select your country" id="Select your country">
                <option value="Select your country">Select your country</option>
            </select>
        </p>
        <p>Application Type:<input type="" name="New Application" id="New Application"></p>
        <p>
            Passport Type:*
            <select name="Select passport type" id="Select passport type">
                <option value="Select">Select</option>
            </select>
        </p>
            <label>Delivery Type</label>
            <p>
                 Regular <input type="radio" name="Delivery Type" id="Regular"> Express <input type="radio" name="Delivery Type" id="Express">
            </p>
        <br>
        <h3>Personal Information</h3>
        <p>Applicant Name:* <input type="name" name="name" required></input> </p>
        <p>First part(Given name):* <input type="name" name="name" required></input> </p>
        <p>Second part(Surname):* <input type="name" name="name" required></input> </p>
        <br>
        <br>
        <label for="guardian">Guardian (Tick if legally adopted):</label>
        <input type="checkbox" id="guardian" name="guardian">
        <br>
            <p>Father's Name:* <input type="name" name="name" required></input> </p>
            <p>
                Father's Nationality:*
                <select name="Select nationality id="Select nationality">
                    <option value="Select">Select</option>
                </select>
            </p>
            <p>
                Father's Profession:*
                <select name="Select Profession" id="Select Profession">
                    <option value="Select">Select</option>
                </select>
            </p>
            <p>Mother's Name:* <input type="name" name="name" required></input> </p>
            <p>
                Mother's Nationality:*
                <select name="Select nationality id="Select nationality">
                    <option value="Select">Select</option>
                </select>
            </p>
            <p>
                Mother's Profession:*
                <select name="Select Profession" id="Select Profession">
                    <option value="Select">Select</option>
                </select>
            </p>
            <p>Spouse's Name: <input type="name" name="name"></input> </p>
            <p>
                Spouse's Nationality:
                <select name="Select nationality id="Select nationality">
                    <option value="Select">Select</option>
                </select>
            </p>
            <p>
                Spouse's Profession:
                <select name="Select Profession" id="Select Profession">
                    <option value="Select">Select</option>
                </select>
            </p>
            <p>
                Marital status:*
                <select name="Select status" id="Select status">
                    <option value="Select">Select</option>
                </select>
            </p>
            <p>
                Applicant's Profession:*
                <select name="Select Profession" id="Select Profession">
                    <option value="Select">Select</option>
                </select>
            </p>
            <p>
                Country of birth:
                <select name="Select Profession" id="Select Profession">
                    <option value="Select">Select</option>
                </select>
            </p>
            <br>
            <hr>
            <br>
            <p>Date of birth:* <input type="date" required></p>
            <legend>Gender:</legend>
            <p>Male <input type="radio" name="gender" id="Male"> Female <input type="radio" name="gender" id="Female"> Others<input type="radio" id="Others"></p>
            <p>Birth ID No:* <input type="number" name="number" required></input> </p>
            <p>National ID No:* <input type="number" name="number" required></input> </p>
            <p>Tax ID Number:* <input type="number" name="number" required></input> </p>
            <label>Height:*</label>
            <input type="text" id="height_cm" name="height_cm" placeholder="cm"> 
            <input type="text" id="height_inch" name="height_inch" placeholder="inch">
            <p>Religion:*<input type="text" id="text" required></p>
            <p>Email:*<input type="text" id="text" required></p>
            <br>
            <h3>Citizenship Information</h3>
            <p>
                Nationality:*
                <select name="Select Nationality" id="Select Nationality">
                    <option value="Select">Select</option>
                </select>
            </p>
            <p>
                Citizenship Status:*
                <select name="Select status" id="Select status">
                    <option value="Select">Select</option>
                </select>
            </p>
            <legend>Dual Citizenship:*</legend>
            <p>
                 Yes <input type="radio" name="dual_citizenship" id="Yas">No<input type="radio" name="dual_citizenship" id="No">
            </p>
            <br>
            <h3>Present Address</h3>
            <p>Village/House: <input type="name" name="name" required></input> </p>
            <p>Road/Block/Sector: <input type="name" name="name" required></input> </p>
            <p>
                District:*
                <select name="Select district" id="Select district">
                    <option value="Select">Select</option>
                </select>
            </p>
            <p>
                Police Station:*
                <select name="Select" id="Select">
                    <option value="Select">Select</option>
                </select>
            </p> 
            <p>
                Post Office:*
                <select name="Select" id="Select">
                    <option value="Select">Select</option>
                </select>
            </p>
            <br>
            <h3>Permanent Address</h3>
            <p>Village/House: <input type="name" name="name" required></input> </p>
            <p>Road/Block/Sector: <input type="name" name="name" required></input> </p>
            <p>
                District:*
                <select name="Select district" id="Select district">
                    <option value="Select">Select</option>
                </select>
            </p>
            <p>
                Police Station:*
                <select name="Select" id="Select">
                    <option value="Select">Select</option>
                </select>
            </p> 
            <p>
                Post Office:*
                <select name="Select" id="Select">
                    <option value="Select">Select</option>
                </select>
            </p>
            <input type="submit" name="submit" value="Save now and continue in future" id="submit">
            <input type="submit" name="submit" value="Save and exit" id="submit">
    </form>
</body>
</html>
