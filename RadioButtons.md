#Accessibility Notes

###Grouping Radio Buttons
[Refer Here](https://www.w3.org/TR/WCAG20-TECHS/ARIA17)

<h3>Some Title: Alert</h3>
  <div role="radiogroup" aria-labelledby="alert1">
    <p id="alert1">Send an alert when balance exceeds $3,000</p>
    <div>
      <span role="radio" aria-labelledby="a1r1" name="a1radio"></span>
      <span id="a1r1">Yes</span>
    </div>
    <div>
      <span role="radio" aria-labelledby="a1r2" name="a1radio"></span>
      <span id="a1r2">No</span>
    </div>
  </div>
  <div role="radiogroup" aria-labelledby="alert2">
    <p id="alert2">Send an alert when a charge exceeds $ 250</p>
    <div>
      <span role="radio" aria-labelledby="a2r1" name="a2radio"></span>
      <span id="a2r1">Yes</span>
    </div>
    <div>
      <span role="radio" aria-labelledby="a2r2" name="a2radio"></span>
      <span id="a2r2">No</span>
    </div>
  </div>
  <p><input type="submit" value="Continue" id="continue_btn" name="continue_btn" /></p>