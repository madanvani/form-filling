<!---  HTML --->
<!DOCTYPE html>
<html>

<head>
    <link rel="stylesheet" href="app.css">
</head>

<body>
    <div class="container">
        <div class="row">
            <div class="containercol-sm-12 col-12">
                <div class="card">
                    <h1 class="heading" id="title">
                        Application For permission To Date Your Daughter
                    </h1>
                    <p class="para margin2" id="description"><b>Note:</b>Form is to be completed at last 21 days prior to date </p>
                    <!--- personal details    -->
                    <fieldset class="margin2">
                        <!-- square brocket form comimg by using this-->
                        <legend>
                            Personal Details
                        </legend>
                        <div>
                            <label id="name-label" for="name">Name:</label>
                            <input type="text" required id="name" name="user_name" placeholder="Enter name here">
                        </div>

                        <div class="margin">
                            <label for="Address">Address:</label>
                            <input id="address" type="Address" name="Address" placeholder="Enter address here">
                        </div>
                        <div class="margin">
                            <label for="email">Email:</label>
                            <input id="email" type="email" name="email" placeholder="Enter email here">
                        </div>
                        <div class="margin">
                            <label for="phonenumber-label">phone number:</label>
                            <input id="phonenumber" type="phone" name="phonenumber" placeholder="Enter 10 digit number">
                        </div>
                        <div class="margin">
                            <label for="IQ-label">IQ:</label>
                            <input id="IQ" type="number" name="IQ" placeholder="Enter iq here">
                        </div>
                        <!-- radio buttons-->
                        <div class="margin">
                            <label for="Gender">Gender:-</label>
                            <p>
                                <input class="margin3" type="radio" name="gender" value="male" checked>male<br>

                                <input class="margin3" type="radio" name="gender" value="female" checked>female<br>

                                <input class="margin3" type="radio" name="gender" value="other" checked>other<br>

                            </p>
                            <label for="date of Proposed Outing">date of Proposed Outing:</label>
                            <input type="date" name="bday">
                        </div>
                    </fieldset>

                    <fieldset class="margin2">
                        <label>Check All The Apply</label>
                        <p>
                            <input type="checkbox" name="tattoo" value="tattoo">I have tattoos and/or piercings<br>
                            <input type="checkbox" name="tattoo" value="tattoo">I am more than 2 years older than my daughter<br>
                            <input type="checkbox" name="tattoo" value="tattoo">I own a ponel van or V8 ute<br>
                            <input type="checkbox" name="tattoo" value="tattoo">I work full-time<br>
                            <input type="checkbox" name="tattoo" value="tattoo">My parents are rich<br>
                            <input type="checkbox" name="tattoo" value="tattoo">Is the daate at a well lit public location<br>

                        </p>
                    </fieldset>
                    <!-- drop down menu-->
                    <fieldset class="margin2">
                        <div>
                            <label for="Political Persuasion">Political Persuasion: </label>
                            <select id="dropdown">
                                <option value="left">
                                    left wing</option>
                                <option value="right">
                                    right wing</option>
                                <option value="conservative">
                                    conservative</option>
                                <option value="Nazi">
                                    Nazi</option>
                            </select> <label for="politics">Eduction Level</label>
                        </div>
                        <div>
                            <label for="Eduction level">Eduction level</label>
                            <select id="dropdown">
                                <option value="university">
                                    university</option>
                                <option value="college">
                                    college</option>
                                <option value="High School">
                                    High School</option>
                                <option value="None">
                                    None</option>
                            </select>

                        </div>

                    </fieldset>
                    <!-- Text areas-->
                    <div>
                        <fieldset class="margin2">
                            <legend>Eassy Section</legend>
                            <label>
                                <p>resaon why im mad and care about your daughter </p>
                                <textarea id="msg" name="user_message" rows="4" cols="50" placeholder="Enter Text Here"></textarea>
                            </label>
                            <label>
                                <p>Please upload contact details for 2 refernces</p>
                                <textarea id="msg" name="contacts_message" rows="4" cols="50" placeholder="Enter Text Here"></textarea>
                            </label>

                            <p class="para1">Upload Police Clearance Certificate,Bank Statement and Medical Certificates here:
                                <button class="button">Attach Files</button>
                            </p>
                        </fieldset>
                        <div class="button3">
                            <button class="button2">please Consider As your Alludu</button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</body>

</html>




<!--  CSS-->
@import url('https://fonts.googleapis.com/css2?family=Bree+Serif&family=Caveat:wght@400;700&family=Lobster&family=Monoton&family=Open+Sans:ital,wght@0,400;0,700;1,400;1,700&family=Playfair+Display+SC:ital,wght@0,400;0,700;1,700&family=Playfair+Display:ital,wght@0,400;0,700;1,700&family=Roboto:ital,wght@0,400;0,700;1,400;1,700&family=Source+Sans+Pro:ital,wght@0,400;0,700;1,700&family=Work+Sans:ital,wght@0,400;0,700;1,700&display=swap');

.container {
    background-color: lightyellow;

    padding: 55px;
    background-size: cover;
}

.card {
    background-color: white;
    border-radius: 10px;
}

.heading {
    margin: 20px;
    text-align: center;
}

.margin {
    margin-top: 8px;
}

.margin2 {
    margin: 35px;
}

.margin3 {
    margin-bottom: 10px;
}

.button {
    background-color: red;
    font-size: 20px;
    border-width: 0px;
    color: white;
}

.para1 {
    font-size: 18px;
    font-family: roboto;
    font-weight: bold;
}

.button2 {
    background-color: red;
    font-size: 20px;
    border-width: 0px;
    color: white;
    margin-bottom: 40px;

}

.button3 {
    text-align: center;
}
