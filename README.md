Answers to Lab:

{
     "familiy_array":[

			{"name":"Mom",
			 "age":"60",
			 "quality": "loving",
			 "appearance":
			 		{"eyes":"brown",
			 		 "hair":"medium"
			 		}
			 },
			 
			 {"name":"Dad",
			 "age":"59",
			 "quality": "Strong",
			 "appearance":
			 		{"eyes":"brown",
			 		 "hair":"bald"
			 		}
			 },
			 {"name":"Bro",
			 "age":"24",
			 "quality": "entreprenurial",
			 "appearance":
			 		{"eyes":"brown",
			 		 "hair":"short"
			 		}
			 }
			 
			 
 ]
 }

 { "family_nested_objects":
 		{"mom":
 			"age":"60",
 			"quality":"loving",
 			"appearance":
 				{"eyes":"brown",
 				"hair":"medium"}
 				}
 				},

 				{"Dad":
 			"age":"59",
 			"quality":"Strong",
 			"appearance":
 				{"eyes":"brown",
 				"hair":"bald"}
 				},

 				{"brother":
 			"age":"24",
 			"quality":"entreprenurial",
 			"appearance":
 				{"eyes":"brown",
 				"hair":"short"}

 		}

 }















| Title | Type | Duration | Name | City |
| --- | --- | --- | --- | --- |
| JSON | Lab | 1:15 | Yuliya Kaleda | NYC |


# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) JSON Lab

<!--  OUTSTANDING
1. This lab should be re-worked to focus more on the structure of JSON API returns: http://stackoverflow.com/questions/12806386/standard-json-api-response-format

-->

## Introduction

> ***Note:*** _This should be done independently._

In this lab, you will be creating JSON files that will provide information about your family members. You will have to create two files that will have the same information about your family members but will have a different structure. After you created the files, go to [JSON Beautifier](http://codebeautify.org/jsonviewer) to validate your JSON syntax.

## Exercise  

#### Requirements

- create a file "family_array" that will have an array as a root element:

	* it should have as many objects as there are members in your family
	* each member should have four attributes: name, age, quality the member can be best described with and appearance that will be an object itself
	* appearance should have two attributes: eyes (color) and hair (short/long)


- create a file "family_nested_objects" that will have an object as a root element:

	* it will have as many objects as there are members in your family
	* each nested object should have a key that will be the person's name
	* each member should have 3 attributes: age, quality the member can be best described with and appearance that will be an object itself
	* appearance should have two attributes: eyes (color) and hair (short/long)

**Bonus**:

- Research APIs for companies you are interested in and look through the documentation to explore the JSON structure they use


## Resources:
- [JSON docs](http://www.json.org/)
