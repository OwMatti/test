<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Navaja_SFActivity1</title>
    <link rel="stylesheet" href="style.css" type="text/css" />\
    <style>
    * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    }
    body {
        background-color:   gray;
    }
    .main-container {
        margin: auto;
        width: 900px;
        height: 870px;
        margin-top: 30px;
        display: flex;
        justify-content: center;


    }
    .container-1 {
        border: 2px solid white;
        border-radius: 5px;
        background-color: cornsilk;
    }
    .box-1 {
        text-align: center;
        margin: 20px 0px;
    }
    .box-2, .box-4 {
        margin-bottom: 20px;
    }
    .box-3, .box-5 {
        margin-left: 5px;
    } 

    .table1 {
        width: 100%;
        padding: 5px;
    }
    .table1 > tbody {

        padding: 10px;
    }
    .placeholderbox {
        width: 143px;
        border-radius: 3px;
    }
    .placeholderbox2 {
        width: 80%;
        border-radius: 3px;
    }
    form {
        font-size: 20px;
        font-family: "Source Sans Pro", sans-serif;
    }   

    .box-1 > h1 {
        margin-bottom: 10px;
    }

    .box-7 {
        text-align: center;
    }

    .submit {
        border-radius: 3px;
        width: 100px;
        height: 30px;

    }
    .submit:hover {
      background-color: blue;
      color: white;

    }
    .urlbox {
        width: 300px;
    }
    </style>
  </head>
  <body>
    <div class="main-container">
      <div class="container-1">
        <div class="box-1">
          <h1>Registration Form</h1>
        </div>
        <div class="box-2">
          <div class="align">
            <form>
              <table class="table1">
                <tbody>
                  <tr>
                    <td style="width: 190px">User id:</td>
                    <td>
                      <input
                        type="text"
                        placeholder="Username"
                        class="placeholderbox"
                      />
                    </td>
                  </tr>
                  <tr>
                    <td>Password:</td>
                    <td>
                      <input
                        type="password"
                        placeholder="Password"
                        class="placeholderbox"
                      />
                    </td>
                  </tr>
                  <tr>
                    <td>Name:</td>
                    <td>
                      <input
                        type="text"
                        placeholder="Given name"
                        class="placeholderbox"
                      />
                    </td>
                  </tr>
                  <tr>
                    <td>Birthday:</td>
                    <td><input type="date" class="placeholderbox" /></td>
                  </tr>
                  <tr>
                    <td>Age</td>
                    <td><input type="number" class="placeholderbox" /></td>
                  </tr>
                  <tr>
                    <td>Email Address:</td>
                    <td>
                      <input
                        type="email"
                        placeholder="example@gmail.com"
                        class="placeholderbox"
                      />
                    </td>
                  </tr>
                  <tr>
                    <td>Phone Number:</td>
                    <td>
                      <input
                        type="tel"
                        placeholder=" +639123456789"
                        class="placeholderbox"
                      />
                    </td>
                  </tr>
                  <tr>
                    <td>Sex:</td>
                    <td>
                      <input type="radio" />&nbsp;Male&nbsp;<input
                        type="radio"
                      />&nbsp;Female&nbsp;
                    </td>
                  </tr>
                </tbody>
              </table>
            </form>
          </div>
        </div>
        <div class="box-3">
          <h3>Home Address</h3>
        </div>
        <div class="box-4">
          <div class="align">
            <form>
              <table class="table1">
                <tbody>
                  <tr>
                    <td style="width: 190px">House #</td>
                    <td><input type="text" class="placeholderbox2" /></td>
                  </tr>
                  <tr>
                    <td>Street</td>
                    <td><input type="text" class="placeholderbox2" /></td>
                  </tr>
                  <tr>
                    <td>City</td>
                    <td><input type="text" class="placeholderbox2" /></td>
                  </tr>
                  <tr>
                    <td>Province</td>
                    <td><input type="text" class="placeholderbox2" /></td>
                  </tr>
                  <tr>
                    <td>Postal Code</td>
                    <td><input type="text" class="placeholderbox2" /></td>
                  </tr>
                  <tr>
                    <td>Is this your permanent address?</td>
                    <td style="text-align: center">
                      Yes&nbsp;<input
                        type="radio"
                        name="address"
                      />&nbsp;No&nbsp;<input type="radio" name="address" />
                    </td>
                  </tr>
                </tbody>
              </table>
            </form>
          </div>
        </div>
        <div class="box-5">
          <h3>Additional Info.</h3>
        </div>
        <div class="box-6">
          <div class="align">
            <form>
              <table class="table1">
                <tbody>
                  <tr>
                    <td style="width: 35%">Musical Instruments</td>
                    <td style="width: 50%">Rate your time spent</td>
                    <td style="width: 10%"><input type="range" /></td>
                  </tr>
                  <tr>
                    <td>Sports</td>
                    <td>Rate your time spent</td>
                    <td><input type="range" /></td>
                  </tr>
                  <tr>
                    <td>Computer Games</td>
                    <td>Rate your time spent</td>
                    <td><input type="range" /></td>
                  </tr>
                  <tr>
                    <td>Reading</td>
                    <td>Rate your time spent</td>
                    <td><input type="range" /></td>
                  </tr>
                  <tr>
                    <td>Favorite Photo</td>
                    <td><input type="file" /></td>
                  </tr>
                  <tr>
                    <td>Favorite Color</td>
                    <td><input type="color" /></td>
                  </tr>
                  <tr>
                    <td>Favorite time of the day</td>
                    <td><input type="time" /></td>
                  </tr>
                  <tr>
                    <td>Add your Facebook Url Here</td>
                    <td><input type="url" class="urlbox" /></td>
                  </tr>
                  <!-- <input type="hidden" /> -->
                </tbody>
              </table>
            </form>
          </div>
        </div>
        <div class="box-7">
          <input type="submit" value="Submit" class="submit" />
        </div>
      </div>
    </div>
  </body>
</html>
