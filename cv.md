# OLEG DUNAEV
### Jr Frontend Developer
---
&#127968; &nbsp; Russia, Saint-Petersburg  
&#128241; &nbsp;&nbsp;&nbsp;+7 (9XX)-XXX-XX-XX  
&#128231; &nbsp;&nbsp;yerolgit@gmail.com  
&#128490; &nbsp;&nbsp;&nbsp;Discord: 30Owls#8413  
&#128747; Telegram: https://t.me/Snailsloth  


---

#### About  
Hi, my name is Oleg.
4 years ago I had a short experience as a junior frontend developer.  
During this time I managed to work with html, css, sass, pug, js(beginner), vue js(beginner), node js(beginner), react(beginner).  
Unfortunately the circumstances gone in a way where I had to change what I do for a living.  
Now I want to get back to basics to remember everything I forget and start my way to become frontend developer.  

#### Code  

Codewars sign up code:  

```javascript
function multiply(a, b){
  return a * b
}
```  


Some old code example from my [old github](https://github.com/Snailsloth?tab=repositories) 

<details><summary>> IS RIGHT HERE <</summary>
<p>

```javascript
function getResults(body){
	const $ = cheerio.load(body);
	const vacansys = $('.vacancy-serp-item ');
	const results = [];

	vacansys.each((index, element) => {
		const result = $(element);
		const title = result.find('[data-qa="vacancy-serp__vacancy-title"]').text();
		const salary = result.find('[data-qa="vacancy-serp__vacancy-compensation"]').text();
		const link = result.find('a.bloko-link').attr('href');
		const responsibility = result.find('div[data-qa="vacancy-serp__vacancy_snippet_responsibility"]').text();
		const requirement = result.find('div[data-qa="vacancy-serp__vacancy_snippet_requirement"]').text();
		const employerRaw = result.find('a[data-qa="vacancy-serp__vacancy-employer"]');
		const employer = {
			name: employerRaw.text(),
			link: baseURL + employerRaw.attr('href')
		};
		const address = result.find('[data-qa="vacancy-serp__vacancy-address"]').text();
		const date = result.find('span.vacancy-serp-item__publication-date').text();

		results.push({
			title,
			salary,
			link,
			responsibility,
			requirement,
			employer,
			address,
			date
		});
	})

	return results;
}
```

</p>
</details>


#### Education  

* Saint Petersburg State Technological University of Plant Polymers, Department of Logistics
* RICE Univercity, python-programming-essentials
* cs50 harvard
* Wes Bos, Lea Verou and other awesome people and their resources\videos


#### Languages  

Russian: native.  
English: Pre-Intermediate (That's what the tests says), trying hard to learn atm.
Comfortable with reading technical documentation and understanding what people write in chat in English, but very little practice with voice communication.
