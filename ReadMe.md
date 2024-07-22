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


How can I verify the action worked or is working as expected.

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
	
