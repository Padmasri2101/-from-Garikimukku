# -from-Garikimukku

<h1>PadmaSri Garikimukku </h1>
<h6>Paradise</h6>
<b>Hyderabadi biryani</b>(also known as Hyderabadi dum biryani) is a style of biryani originating from the kitchens of the Nizams of the erstwhile Hyderabad State with <b>basmati rice and meat</b> (mostly mutton).
<br>
 Originating in the kitchens of the Nizam of Hyderabad, it combines elements of Hyderabadi and Mughlai cuisines.<b>Hyderabad biryani is a key dish in Hyderabadi cuisine</b> and it is so famous that the dish is considered synonymous with the city of Hyderabad.
 ---
 <h3>Fav dishes at paradise</h3>
 1. Chicken briyani<br>
 2. chicken 65<br>
 3. mutton curry<br>




 * Tankbund<br>
 * Charminar<br>
 * Luminipark<br>

 [linkofMyMedia](MyMedia.md)

 ---

 <h2>Tables</h2>
 
| Book Name | Reason why you recommend it| author name |
|--------|-------------|-------------|
|The Buried gaint |I absolutely love this book.t’s essentially about memory and forgetting. It’s about terrible atrocities that have happened between different groups of people |by Kazuo Ishiguro|
|Harry potter|The novels chronicle the lives of a young wizard, Harry Potter, and his friends Hermione Granger and Ron Weasley, all of whom are students at Hogwarts School of Witchcraft and Wizardry. |J.K. Rowling|
|The Great Indian Novel|This is a satirical novel it is a fictional work that tells the story of the Mahabharata, a famous Indian epic. The book recasts and resets the story in the context of the Indian Independence Movement and the first three decades of post-independence.|Shashi Tharoor | 


---

<h2>Quotes</h2>


> "If you want to shine like a sun, first burn like a sun" - *APJ Abdul Kalam*<br>
> "To succeed, you must have tremendous perseverance, tremendous will" - *Swami Vivekananda*

---
<h2>Code Fencing</h2>

This Node.js example code reads a csv file from a file path using the fs module and a comma as a delimiter. 

```

const fileSystem = require("fs"); 
const { parse } = require("csv-parse"); 

const readCSV = filePath => {
	fileSystem.createReadStream(filePath) <br>
		.pipe(parse({
			delimiter: ",",
			from_line: 2
		}))
		.on("data", function(row) {
			console.log(row);
		})
} 

```
[read and parse a CSV file](https://code.pieces.app/collections/node-js)





