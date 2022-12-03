1.Who are you? What do you like building?

HI I'm Gopi.K 

2.Do you own a PC and have a good internet connection? Let's hear those specs
  Having windows system with proper bandwidth
3. What programming languages have you messed around with?
    Javascript
    react
4. Are you more into front-end or back-end? (If you're into web development).
    Front end

- Find the longest word in a string.

const wordcalculate = (inputString) => {
  var word =inputString.split(" ").reduce((longerString, currentString) => {
        return currentString.length > longerString.length
          ? currentString
          : longerString;
      }, " ");
  return word;
};
console.log(wordcalculate("The quick brown fox jumped over the lazy dog"));





- Repeat a string `n` times.
 
 console.log('abcd'.repeat(25));
 
- Remove duplicates in an array
  
 new Set([1, 20, 3, 1, 3, 3])

- Remove falsy values

 
const filtedreddata = [42, "everything", "", 2, false, "everything"].filter(value => Boolean(value));
console.log(filtedreddata) 

- Truncate a string

 
