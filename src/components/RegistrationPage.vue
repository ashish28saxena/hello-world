<template>
  
  <form>
  <div class="form-row">
    <div class="form-group col-md-6">
      <label for="inputEmail4">Email</label>
      <input type="email" class="form-control" id="inputEmail4" placeholder="Email">
    </div>
    <div class="form-group col-md-6">
      <label for="inputPassword4">Password</label>
      <input type="password" class="form-control" id="inputPassword4" placeholder="Password">
    </div>
  </div>
  <div class="form-group">
    <label for="inputAddress">Address</label>
    <input type="text" class="form-control" id="inputAddress" placeholder="1234 Main St">
  </div>
  <div class="form-group">
    <label for="inputAddress2">Address 2</label>
    <input type="text" class="form-control" id="inputAddress2" placeholder="Apartment, studio, or floor">
  </div>
  <div class="form-row">
    <div class="form-group col-md-6">
      <label for="inputCity">City</label>
      <select id="inputCity" class="form-control">
        
        <option value="">Select City</option>
      <option value="Alipur">Alipur</option>
      <option value="Bawana">Bawana</option>
      <option value="Central Delhi">Central Delhi</option>
      <option value="Delhi">Delhi</option>
      <option value="Deoli">Deoli</option>
      <option value="East Delhi">East Delhi</option>
      <option value="Karol Bagh">Karol Bagh</option>
      <option value="Najafgarh">Najafgarh</option>
      <option value="Nangloi Jat">Nangloi Jat</option>
      <option value="Narela">Narela</option>
      <option value="New Delhi">New Delhi</option>
      <option value="North Delhi">North Delhi</option>
      <option value="North East Delhi">North East Delhi</option>
      <option value="North West Delhi">North West Delhi</option>
      <option value="Pitampura">Pitampura</option>
      <option value="Rohini">Rohini</option>
      <option value="South Delhi">South Delhi</option>
      <option value="South West Delhi">South West Delhi</option>
      <option value="West Delhi">West Delhi</option>
      </select>
    </div>
    <div class="form-group col-md-4">
      <label for="inputState">State</label>
      <select id="inputState" class="form-control">
        <option selected>Choose...</option>
        <option value="AN">Andaman and Nicobar Islands</option>
    <option value="AP">Andhra Pradesh</option>
    <option value="AR">Arunachal Pradesh</option>
    <option value="AS">Assam</option>
    <option value="BR">Bihar</option>
    <option value="CH">Chandigarh</option>
    <option value="CT">Chhattisgarh</option>
    <option value="DN">Dadra and Nagar Haveli</option>
    <option value="DD">Daman and Diu</option>
    <option value="DL">Delhi</option>
    <option value="GA">Goa</option>
    <option value="GJ">Gujarat</option>
    <option value="HR">Haryana</option>
    <option value="HP">Himachal Pradesh</option>
    <option value="JK">Jammu and Kashmir</option>
    <option value="JH">Jharkhand</option>
    <option value="KA">Karnataka</option>
    <option value="KL">Kerala</option>
    <option value="LA">Ladakh</option>
    <option value="LD">Lakshadweep</option>
    <option value="MP">Madhya Pradesh</option>
    <option value="MH">Maharashtra</option>
    <option value="MN">Manipur</option>
    <option value="ML">Meghalaya</option>
    <option value="MZ">Mizoram</option>
    <option value="NL">Nagaland</option>
    <option value="OR">Odisha</option>
    <option value="PY">Puducherry</option>
    <option value="PB">Punjab</option>
    <option value="RJ">Rajasthan</option>
    <option value="SK">Sikkim</option>
    <option value="TN">Tamil Nadu</option>
    <option value="TG">Telangana</option>
    <option value="TR">Tripura</option>
    <option value="UP">Uttar Pradesh</option>
    <option value="UT">Uttarakhand</option>
    <option value="WB">West Bengal</option>
      </select>
    </div>
    <div class="form-group col-md-2">
      <label for="inputZip">Zip</label>
      <input type="text" class="form-control" id="inputZip">
    </div>
  </div>
  <div class="form-group">
    <div class="form-check">
      <input class="form-check-input" type="checkbox" id="gridCheck">
      <label class="form-check-label" for="gridCheck">
        chemis
      </label>
    </div>
  </div>

  <div class="form-check">
  <input class="form-check-input" type="checkbox" value="" id="defaultCheck1">
  <label class="form-check-label" for="defaultCheck1">
    math
  </label>
</div>
<div class="form-check">
  <input class="form-check-input" type="checkbox" value="" id="defaultCheck2" >
  <label class="form-check-label" for="defaultCheck2">
    Physic
  </label>
</div>

<div class="form-check">
  <input class="form-check-input" type="radio" name="exampleRadios" id="exampleRadios1" value="option1" checked>
  <label class="form-check-label" for="exampleRadios1">
    Male
  </label>
</div>
<div class="form-check">
  <input class="form-check-input" type="radio" name="exampleRadios" id="exampleRadios2" value="option2">
  <label class="form-check-label" for="exampleRadios2">
    Female
  </label>
</div>

  <button type="button" class="btn btn-primary">Sign Up</button>
</form>
</template>

<script>
export default {
  name:'RegistrationPage',
  data()
  {
    return {
      email:'',
      password:''
    }
  },
  methods:{
    login()
    {
      console.log(this.email);
      console.log(this.password);
      console.log('login form call')
    }
  }
}
</script>