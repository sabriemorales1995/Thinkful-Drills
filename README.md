# Wise-person-Drill

function wisePerson(wiseType, whatToSay) {
 return `A wise ${wiseType} once said: \"${whatToSay}\".`;
 
  // your code here
}

/* From here down, you are not expected to 
   understand.... for now :)  
   
   
   Nothing to see here!
   
*/

// tests

function testWisePerson() {
  const wiseType = 'goat';
  const whatToSay = 'hello world';
  const expected = 'A wise ' + wiseType + ' once said: "' + whatToSay + '".';
  const actual = wisePerson(wiseType, whatToSay);
  if (expected === actual) {
    console.log('SUCCESS: `wisePerson` is working');
  } else {
    console.log('FAILURE: `wisePerson` is not working');
  }
}

testWisePerson();
