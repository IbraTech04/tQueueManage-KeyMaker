# keyMakerForTMQM
The program used to make product keys for TMQM
## How product keys for TMQM Work:
There are four main parts of a product key for TMQM: The date created, the first bundle of numbers, the second bundle of numbers, and they ASCII keycode total. The first bundle of letters does not matter as long as it is OEM

### Date Created
The date created contains two main parts: The day of the year, and the year itself. For example: 04420 would indicate the key was made on the 44th day of the year 2020. If they key being processed was made before 2019, the key is immediatly not valid

### Bundle One:
The first bundle is a bundle with 7 numbers that must add up to a number divisible by 7. Example: 8022682

### Bundle Two:
The second bundle is a bundle with 5 numbers that must add up to a number divisible by 5. Exammple: 05703

### ASCII KeyCodes
You will notice that at the end of any product key is an extra set of numbers. These numbers are the added total of the ASCII values of each character in the ProductOwner feild. Example: IBRAHIM adds up to 60
