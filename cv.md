# Tatsiana Danilovich
------------
![myPhoto](/img/myPhoto.jpg)
### _My Contact Info:_

**Location:**   Minsk, Belarus  
**Phone:** +375 29 6-830-840  
**E-mail:** tan.danilovich@gmail.com  
**GitHub:** [TanyaDanilovich](https://github.com/TanyaDanilovich)  
**Discord:** TanyaD#2474  

-------


### _About myself:_

I want to learn Front-End Development in RSSchool

### _Skills and Proficiency:_

  * HTML, CSS (Basics)
  * JavaScript (Basics)
  * Git, GitHub
  * Python (Basics)
  * VS Code
  * Adobe Photoshop
  * Adobe Lightroom

### _Code example:_

**Kata from Codewars:** [Fake Binary](https://www.codewars.com/kata/fake-binary/javascript)
>Given a string of digits, you should replace any digit below 5 with '0' and any digit 5 and above with '1'. 
>Return the resulting string.
```
function fakeBin(x) {
	let y = '';
	let char = 0;
	while (char < +x.length) {
		((Number(x[char])) < 5) ? y = y + '0' : y = y + '1';
		char++;
	}
	return y;
}
```