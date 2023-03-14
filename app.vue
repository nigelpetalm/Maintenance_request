<template >
 
    <div class="heading">
      <h3 >Colsultant to Enter</h3>
    </div>
    <div class="container">
      <form action="action_page.php">
        <div class="row">
          <div class="col-25">
            <label for="fname">DATE</label>
          </div>
          <div class="col-75">
            <input class="input" type="date" id="fname" name="firstname" placeholder="Your name..">
          </div>
        </div>
        <div class="row">
          <div class="col-25">
            <label for="subject">Description of Request</label>
          </div>
          <div class="col-75">
            <textarea class="input" id="subject" name="subject" placeholder="Write something.." style="height:200px"></textarea>
          </div>
        </div>
        <div class="row">
          <div class="col-25">
            <label for="subject">Resolution of Request</label>
          </div>
          <div class="col-75">
            <textarea class="input" id="subject" name="subject" placeholder="Write something.." style="height:200px"></textarea>
          </div>
        </div>
        <div class="row">
          <div class="col-25">
            <label for="lname">Hours Worked</label>
          </div>
          <div class="col-75">
            <input type="number" id="lname" class="input">
          </div>
        </div>
        <div class="row">
          <div class="col-25">
            <label for="country">Completed</label>
          </div>
          <div class="col-75">
            <select id="country" name="country" class="input">
              <option value="australia">No</option>
              <option value="canada">Yes</option>
            </select>
          </div>
     
        </div>    
        <div class="row">
          <div class="col-25">
            <label for="country">Company Name</label>
          </div>
          <div class="col-75">
            <select id="country" name="country" class="input">
              <option value="australia">Surge</option>
              <option value="canada">Petalm Africa</option>
              <option value="usa">Huawei</option>
              <option value="microsoft">Microsoft</option>
            </select>
          </div>
        </div>
         <div class="row">
         <input  type="submit" value="Submit"> 
        </div>
      </form>
    </div>
    
    </template>
    
    <script >
    
          
        
    </script>
    
    <style> 
    
    body {
      background-image: linear-gradient(to right, rgba(217, 221, 223, 0), rgb(143, 212, 188));
    }
    
    .input{
      background-image: linear-gradient(to right, rgb(237, 244, 245), rgb(160, 240, 239));
      color: #000;
      font-size: large;
    }
    
    .heading{
      background-color: #04AA6D;
      margin: 15px;
    }
    
    h3{
      text-align: center;
      color:#f2f2f2;
      
    }
    
    .input[type=text], select, textarea{
      width: 100%;
      padding: 12px;
      border: 1px solid #ccc;
      border-radius: 4px;
      box-sizing: border-box;
      resize: vertical;
    }
    
    label {
      padding: 12px 12px 12px 0;
      display: inline-block;
    }
    
    input[type=submit] {
      background-color: #04AA6D;
      color: white;
      padding: 12px 20px;
      border: none;
      border-radius: 4px;
      cursor: pointer;
      float: right;
    }
    
    .container {
      border-radius: 5px;
      background-image: linear-gradient(to right, rgba(247, 250, 252, 0), rgb(122, 237, 199));
      padding: 20px;
    }
    
    .col-25 {
      float: left;
      width: 25%;
      margin-top: 6px;
    }
    
    .col-75 {
      float: left;
      width: 75%;
      margin-top: 6px;
    }
    
    .row:after {
      content: "";
      display: table;
      clear: both;
    }
    
    
    
    </style>
    
    