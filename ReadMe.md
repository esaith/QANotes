# QA Notes

## Acceptance Criteria
Precondition/Action: When no minimaps exist.
<br> Action: AND Do something, if applicable
<br> PostCondition: THEN Y should occur
 
<br> Example
<br> WHEN user selects a floorplan
<br> AND the user select a hotspot
<br> THEN the hotspot image shows

<br> Think of ways of how it should function (positive testing). Think of ways of how it should not function (negative testing)

## Testing Notes
<br>Steps I took to verify enhancement is complete or bug is fixed.
<br>
<br>Step 1. I did this
<br>Step 2. I did that.
<br>Step 3. I set up X
<br>Step 4. Now tested Y because X is now available.

<br>Bug Fix

<br>What is the bug?
<br>-- Learn its history and functionality. If you don't know the product or enhancement then it becomes difficult to test.

<br>Understand requirements.

<br>Reproducing
<br>Can I reproduce this in live or the environment where the issue is occurring?

<br>Verifying Fix
<br>Can I verify bug is fixed in the testing environment (RT, UAT)

<br>Regression
<br>Can I verify the fix did not affect anything else on the page or app? Does all other functionality within the app still work? How about similar components within the page or app still work as expected.
<br>-- For example, if there is an issue in a popup modal, do other popup modals have a similar issue? Or making sure that after the fix, all other popups work as expected.
<br>-- Check enhancement testing. 

<br><br>Enhancement

<br><br>Straight on case
<br>Does the enhancement work as expected? Is all the functionality there and does it work within a reasonable amount of time? 
<br>-- Is the UI/UX correct? Correct colors, buttons, sizing of components?

<br><br>Button
 <br>-- Does the button have good static look? (No action on button, no mouse events, no hover)
 <br>-- Does button have good hover UI?
 <br>-- Does button have good click UI?
 <br>-- Does button have good disable UI?
 <br>   -- Can button be disabled?
 <br>	-- Can button be enabled?
 <br>	-- Is there a way to break the disable when it shouldn't be disabled.
<br>	-- Is ther a way to disable when its enabled?
<br>-- Is the responsiveness of the button acceptable after clicking the button?
  <br>  -- That is, an action may take a long time to complete but the button should appear to respond and end its action almost immediately. 
  <br>  -- If a long action occurs, then the button should probably be disabled to prevent spamming of that button.	
    

<br><br><br>How can I verify the action worked or is working as expected.
<br>

# General Actions
  1. If action is taking longer than 500 ms (1/2 second), then should there be a loading spinner?

## Button Actions
<ol>
  <li>Is there a button animation on button click?</li>
  <li>Is there a notification that something actually occurred?
    <ol>
      <li>e.g. A toast or UI event to confirm something happened </li>      
    </ol>
  </li>
  <li>Would a tooltip be beneficial?
     <ol>
       <li>Explain why a button/action is disabled and how to enabled it</li>
   	   <li>How to test or verify action occurred or at least a link to a wiki for a further explanation</li>   	   
     </ol>
  </li>
  <li>Should there be a warning modal? 
    <ol>
   	  <li>A. e.g. Yes/No, "Are you sure"</li>
    </ol>
  </li>
</ol>

## Inputs
<ol>
  <li>What type of input is it?
    <ol>
     <li>Text? Is there or should there be a character limit?</li>
	    <li>Number? Is there a max or min value to that number? 2^32</li>
	    <li>Telephone #?  Is there a way it should be presented? e.g.  (813)316-0000 or 813.316.0000 or 1.813.316.0000</li>    
     <li>Text Area (large text input spanning multiple lines)
      <ol>
	      <li>Is there is a text limit? e.g. 500 characters?</li>
       <li>Is there height or width limit of the box?</li>
      </ol>
     </li>
     </ol>
   </li>
 </ol>

 ## Files
 <ol>
  <li>Is there a size limit?
   <ol>
    <li>400KB? 1MB? 10 MB?</li>
   </ol>
  </li>
  <li>Is there a file type requirement?
    <ol>
      <li>e.g. Only .jpg, or .jpeg, or .png, etc</li>
    </ol>
   </li>
  <li>Number of files limit? 
   <ol>
     <li>only 1?</li>
     <li>Allow multiple?</li>
     <li>Is there a max limit?</li>
   </ol>
  </li>
	</ol>
	
